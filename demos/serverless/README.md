# Amazon Chime SDK 서버리스 데모

이 데모는 [Chime SDK 브라우저 데모](https://github.com/aws/amazon-chime-sdk-js/tree/main/demos/browser)를 서버리스 애플리케이션으로 배포하는 방법을 보여줍니다.

> **주의**: 이 데모 애플리케이션을 배포하면 Amazon Chime SDK를 포함한 AWS 서비스 사용료가 청구됩니다.

## 사전 요구사항

### 필수 소프트웨어

* Node.js 18 이상
* npm 8.6.0 이상

### AWS CLI 도구 설치

* [AWS CLI 설치](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv1.html)
* [AWS SAM CLI 설치](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-sam-cli-install.html)

## 배포 방법

### 기본 미팅 앱 배포

다음 명령어는 Lambda와 API Gateway를 포함한 CloudFormation 스택을 생성합니다.

```bash
cd demos/serverless
npm install
npm run deploy -- -r ap-northeast-2 -b <배포-버킷명> -s <스택명> -a meeting
```

### 서울 리전에 완전한 기능으로 배포

미디어 캡처와 라이브 트랜스크립션을 포함한 전체 기능 배포:

```bash
cd demos/serverless
npm install
npm run deploy -- \
  -r ap-northeast-2 \
  -b <배포-버킷명> \
  -o <캡처-버킷-prefix> \
  -s <스택명> \
  -a meeting \
  -m https://meetings-chime.ap-northeast-2.amazonaws.com \
  --chime-sdk-media-pipelines-region ap-northeast-2 \
  --chime-sdk-media-pipelines-endpoint https://media-pipelines-chime.ap-northeast-2.amazonaws.com
```

### 배포 옵션

| 옵션 | 설명 | 필수 |
|------|------|------|
| `-r, --region` | 배포할 AWS 리전 (예: ap-northeast-2) | ✓ |
| `-b, --s3-bucket` | 배포 아티팩트를 저장할 S3 버킷명 | ✓ |
| `-s, --stack-name` | CloudFormation 스택명 | ✓ |
| `-a, --application` | 배포할 애플리케이션 (meeting, meetingReadinessChecker) | |
| `-o, --capture-output-prefix` | 미디어 캡처용 S3 버킷 prefix | |
| `-m, --chime-sdk-meetings-endpoint` | Chime SDK Meetings 엔드포인트 | |
| `--chime-sdk-media-pipelines-region` | Media Pipelines 제어 리전 | |
| `--chime-sdk-media-pipelines-endpoint` | Media Pipelines 엔드포인트 | |
| `-e, --event-bridge` | EventBridge 통합 활성화 | |
| `-i, --opt-in-regions` | 추가 미디어 캡처 리전 (쉼표로 구분) | |

## 주요 기능

### 미디어 캡처

미디어 캡처를 사용하려면 `-o` 옵션으로 S3 버킷 prefix를 지정하세요. 각 리전에 `<prefix>-<region>` 형식의 버킷이 자동 생성됩니다.

```bash
npm run deploy -- \
  -r ap-northeast-2 \
  -b <배포-버킷> \
  -o <캡처-버킷-prefix> \
  -s <스택명> \
  -a meeting
```

**Service-Linked Role 생성 (최초 1회)**:
```bash
aws iam create-service-linked-role --aws-service-name mediapipelines.chime.amazonaws.com
```

자세한 내용은 [서비스 연결 역할 생성 가이드](https://docs.aws.amazon.com/chime-sdk/latest/dg/create-pipeline-role.html)를 참조하세요.

### 라이브 커넥터 (스트리밍)

라이브 커넥터 기능을 사용하면 미팅을 실시간으로 방송할 수 있습니다. 기본 레이아웃은 세로형(Vertical)이며 FHD 해상도입니다. 재생 URL은 [HLS 플레이어](https://www.hlsplayer.net/)에서 사용할 수 있습니다.

다양한 레이아웃 설정은 [공식 문서](https://docs.aws.amazon.com/chime-sdk/latest/APIReference/API_media-pipelines-chime_CreateMediaLiveConnectorPipeline.html)를 참조하세요.

### 라이브 트랜스크립션

실시간 음성-텍스트 변환 기능을 사용하려면 Service-Linked Role을 생성하세요:

```bash
aws iam create-service-linked-role --aws-service-name transcription.chime.amazonaws.com
```

자세한 내용은 [라이브 트랜스크립션 가이드](https://docs.aws.amazon.com/chime/latest/dg/meeting-transcription.html)를 참조하세요.

### 미팅 준비 상태 확인 앱

네트워크 및 디바이스 준비 상태를 확인하는 앱:

```bash
npm run deploy -- \
  -r ap-northeast-2 \
  -b <배포-버킷> \
  -s <스택명> \
  -a meetingReadinessChecker
```

## 배포된 리소스

### Lambda 함수

| 함수 | 엔드포인트 | 기능 |
|------|-----------|------|
| ChimeSdkJoinLambda | `/join` | 미팅 생성 및 참석자 추가 |
| ChimeSdkEndLambda | `/end` | 미팅 종료 |
| ChimeSdkStartCaptureLambda | `/startCapture` | 미팅 녹화 시작 |
| ChimeSdkEndCaptureLambda | `/endCapture` | 미팅 녹화 중지 |
| ChimeSdkStartLiveConnectorLambda | `/startLiveConnector` | 라이브 스트리밍 시작 |
| ChimeSdkEndLiveConnectorLambda | `/endLiveConnector` | 라이브 스트리밍 중지 |
| ChimeSdkStartTranscriptionLambda | `/start_transcription` | 실시간 트랜스크립션 시작 |
| ChimeSdkStopTranscriptionLambda | `/stop_transcription` | 트랜스크립션 중지 |

### 기타 리소스

* **DynamoDB 테이블**: 미팅 정보 저장 (TTL 24시간)
* **SQS 큐**: 미팅 알림 수신
* **CloudWatch Logs**: 브라우저 로그 및 미팅 이벤트
* **CloudWatch Dashboard**: 미팅 성공률, 브라우저/OS 통계, 실패 분석

## 미팅 대시보드

서버리스 데모는 CloudWatch Logs를 사용하여 미팅 이벤트를 시각화합니다.

### 대시보드 보기

1. 위의 배포 스크립트를 실행하여 `meeting` 데모를 배포합니다.
2. [CloudWatch 콘솔](https://console.aws.amazon.com/cloudwatch/)을 엽니다.
3. 왼쪽 메뉴에서 **대시보드**를 선택합니다.
4. 미팅 이벤트 대시보드를 선택합니다.
5. 미팅 성공률, 플랫폼 정보, 운영 데이터를 확인할 수 있습니다.

### 특정 참석자 이벤트 검색

1. 대시보드 하단의 위젯에서 검색 방법을 확인합니다.
2. **Logs Insights**로 이동하여 로그 그룹을 선택합니다.
3. 다음 쿼리로 특정 참석자의 이벤트를 검색합니다:

```
filter attributes.attendeeId = "your_attendee_id"
```

## 애플리케이션 업데이트

SDK가 업데이트되면 배포된 애플리케이션도 업데이트해야 합니다.

> **중요**: 업데이트 시 원래 배포할 때 사용한 것과 동일한 버킷명과 스택명을 사용하세요. 그렇지 않으면 새로운 리소스가 생성되어 추가 비용이 발생할 수 있습니다.

```bash
cd demos/serverless
npm run deploy -- \
  -r ap-northeast-2 \
  -b <원래-버킷명> \
  -s <원래-스택명> \
  -a meeting \
  -m https://meetings-chime.ap-northeast-2.amazonaws.com \
  --chime-sdk-media-pipelines-region ap-northeast-2 \
  --chime-sdk-media-pipelines-endpoint https://media-pipelines-chime.ap-northeast-2.amazonaws.com
```

## 리소스 정리

불필요한 비용 발생을 방지하려면 사용 후 CloudFormation 스택과 S3 버킷을 삭제하세요.

### CloudFormation 스택 삭제

[AWS 콘솔](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/cfn-console-delete-stack.html) 또는 [AWS CLI](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-cli-deleting-stack.html) 사용:

```bash
aws cloudformation delete-stack --stack-name <스택명> --region ap-northeast-2
```

### S3 버킷 삭제

```bash
# 배포 버킷
aws s3 rb s3://<배포-버킷명> --force --region ap-northeast-2

# 캡처 버킷 (사용한 경우)
aws s3 rb s3://<캡처-버킷-prefix>-ap-northeast-2 --force --region ap-northeast-2
```

## 지원 리전

### Chime SDK Meetings

* ap-south-1 (뭄바이)
* ap-northeast-1 (도쿄)
* ap-northeast-2 (서울)
* ap-southeast-1 (싱가포르)
* ap-southeast-2 (시드니)
* ca-central-1 (캐나다)
* eu-central-1 (프랑크푸르트)
* eu-west-2 (런던)
* us-east-1 (버지니아 북부)
* us-west-2 (오레곤)
* us-gov-east-1, us-gov-west-1

[전체 리전 목록](https://docs.aws.amazon.com/chime-sdk/latest/dg/sdk-available-regions.html)

### Chime SDK Media Pipelines

* ap-south-1, ap-northeast-1, ap-northeast-2, ap-southeast-1, ap-southeast-2
* ca-central-1
* eu-central-1, eu-west-2
* us-east-1, us-west-2

[Media Pipelines 리전](https://docs.aws.amazon.com/chime-sdk/latest/dg/sdk-available-regions.html#sdk-media-pipelines)

## 문제 해결

### "Meeting not found" 오류

미팅이 만료되었지만 DynamoDB에 레코드가 남아있는 경우:

```bash
aws dynamodb delete-item \
  --table-name <테이블명> \
  --key '{"Title": {"S": "<미팅-제목>"}}' \
  --region ap-northeast-2
```

최신 코드는 만료된 미팅을 자동으로 정리합니다.

### "Credential should be scoped to a valid region" 오류

배포 시 `-m` 옵션으로 올바른 리전 엔드포인트를 지정했는지 확인하세요.

## 면책 조항

Amazon Chime SDK 미팅을 녹화할 때는 전자 통신 녹음 관련 법률 및 규정을 준수해야 합니다. 녹화 중임을 모든 참가자에게 적절히 알리고 동의를 받는 것은 귀하와 최종 사용자의 책임입니다.

## 라이선스

Apache-2.0

## 참고 자료

* [Amazon Chime SDK 개발자 가이드](https://docs.aws.amazon.com/chime-sdk/latest/dg/what-is-chime-sdk.html)
* [Amazon Chime SDK JavaScript](https://github.com/aws/amazon-chime-sdk-js)
* [CloudWatch Logs Insights](https://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/AnalyzingLogData.html)
