# Amazon Chime SDK for JavaScript

[Amazon Chime SDK 프로젝트 보드](https://github.com/orgs/aws/projects/12)

[Amazon Chime SDK React 컴포넌트](https://github.com/aws/amazon-chime-sdk-component-library-react)

<a href="https://www.npmjs.com/package/amazon-chime-sdk-js"><img src="https://img.shields.io/npm/v/amazon-chime-sdk-js?style=flat-square"></a>
<a href="https://github.com/aws/amazon-chime-sdk-js/actions?query=workflow%3A%22Deploy+Demo+App+Workflow%22"><img src="https://github.com/aws/amazon-chime-sdk-js/workflows/Deploy%20Demo%20App%20Workflow/badge.svg"></a>

## Amazon Chime SDK로 구동되는 영상 통화, 음성 통화, 메시징, 화면 공유 애플리케이션 구축

Amazon Chime SDK는 개발자가 웹 또는 모바일 애플리케이션에 메시징, 오디오, 비디오, 화면 공유 기능을 빠르게 추가할 수 있는 실시간 통신 컴포넌트 세트입니다.

개발자는 AWS의 글로벌 통신 인프라를 기반으로 애플리케이션에서 매력적인 경험을 제공할 수 있습니다. 예를 들어, 환자가 건강 문제에 대해 의사와 원격으로 상담할 수 있도록 건강 애플리케이션에 비디오를 추가하거나, 공중 전화망과 통합하기 위한 맞춤형 오디오 프롬프트를 만들 수 있습니다.

Amazon Chime SDK for JavaScript는 AWS 계정에서 생성한 미팅 세션 리소스에 연결하여 작동합니다. SDK에는 미팅 세션 구성, 오디오 및 비디오 장치 나열 및 선택, 화면 공유 시작 및 중지, 볼륨 변경과 같은 미디어 이벤트 발생 시 콜백 수신, 오디오 음소거 및 비디오 타일 바인딩과 같은 미팅 기능 제어 등 웹 애플리케이션에서 맞춤형 통화 및 협업 경험을 구축하는 데 필요한 모든 것이 포함되어 있습니다.

React 애플리케이션을 구축하는 경우, 오디오 및 비디오 회의 애플리케이션에서 사용되는 일반적인 웹 인터페이스를 위한 클라이언트 측 상태 관리 및 재사용 가능한 UI 컴포넌트를 제공하는 [Amazon Chime SDK React 컴포넌트 라이브러리](https://github.com/aws/amazon-chime-sdk-component-library-react) 사용을 고려하세요. Amazon Chime은 네이티브 모바일 애플리케이션 개발을 위한 [Amazon Chime SDK for iOS](https://github.com/aws/amazon-chime-sdk-ios) 및 [Amazon Chime SDK for Android](https://github.com/aws/amazon-chime-sdk-android)도 제공합니다.

[Amazon Chime SDK 프로젝트 보드](https://github.com/orgs/aws/projects/12)는 모든 저장소에 걸친 커뮤니티 기능 요청의 상태를 캡처합니다. 보드의 열에 대한 설명은 이 [가이드](https://aws.github.io/amazon-chime-sdk-js/modules/projectboard.html)에 나와 있습니다.

## 리소스

- [Amazon Chime SDK 개요](https://aws.amazon.com/chime/chime-sdk/)
- [Amazon Chime 애플리케이션 및 SDK의 보안 이해](https://aws.amazon.com/blogs/business-productivity/understanding-security-in-the-amazon-chime-application-and-sdk/)
- [가격](https://aws.amazon.com/chime/chime-sdk/pricing/)
- [지원 브라우저](https://docs.aws.amazon.com/chime-sdk/latest/dg/meetings-sdk.html#mtg-browsers)
- [시작 가이드](https://github.com/aws/amazon-chime-sdk-js/blob/main/guides/20_Builders_Journey.md)
- [개발자 가이드](https://docs.aws.amazon.com/chime-sdk/latest/dg/meetings-sdk.html)
- [Control Plane API 참조](https://docs.aws.amazon.com/chime-sdk/latest/APIReference/welcome.html)
- [자주 묻는 질문 (FAQ)](https://aws.github.io/amazon-chime-sdk-js/modules/faqs.html)

## 블로그 게시물

아래 외에도 [Amazon Chime SDK에 대한 모든 블로그 게시물](https://aws.amazon.com/blogs/business-productivity/tag/amazon-chime-sdk/) 목록이 있습니다.

### 프론트엔드

- [오디오 및 공유 콘텐츠 변환](https://aws.amazon.com/blogs/business-productivity/transforming-audio-and-shared-content-in-the-amazon-chime-sdk-for-javascript/)
- [AWS Amplify로 Amazon Chime SDK 애플리케이션 빠르게 시작하기](https://aws.amazon.com/blogs/business-productivity/quickly-launch-an-amazon-chime-sdk-application-with-aws-amplify/)

### 풀스택 및 PSTN

- [Amazon Chime SDK 미팅 콘텐츠 캡처](https://aws.amazon.com/blogs/business-productivity/capture-amazon-chime-sdk-meetings-using-media-capture-pipelines/)
- [Amazon Chime SDK 미팅 이벤트로 모니터링 및 문제 해결](https://aws.amazon.com/blogs/business-productivity/monitoring-and-troubleshooting-with-amazon-chime-sdk-meeting-events/)
- [Amazon Chime SDK 메시징 애플리케이션에 미팅 기능 구축](https://aws.amazon.com/blogs/business-productivity/build-meeting-features-into-your-amazon-chime-sdk-messaging-application/)
- [Amazon Chime SDK를 사용하여 자동 아웃바운드 통화 알림 생성](https://aws.amazon.com/blogs/business-productivity/using-the-amazon-chime-sdk-to-create-automated-outbound-call-notifications/)
- [Amazon Chime SDK로 음성 메뉴 및 통화 라우팅 구축](https://aws.amazon.com/blogs/business-productivity/building-voice-menus-and-call-routing-with-the-amazon-chime-sdk/)

### 메시징

- [채널 플로우를 사용하여 Amazon Chime SDK 메시징의 메시지에서 욕설 및 민감한 콘텐츠 제거](https://aws.amazon.com/blogs/business-productivity/use-channel-flows-to-remove-profanity-and-sensitive-content-from-messages-in-amazon-chime-sdk-messaging/)
- [자동 조정 및 감정 분석 블로그 (Kinesis Data Streams 사용 예제)](https://aws.amazon.com/blogs/business-productivity/automated-moderation-and-sentiment-analysis-with-amazon-chime-sdk-messaging)
- [Amazon Chime SDK 메시징으로 iOS 및 Android에서 채팅 애플리케이션 구축](https://aws.amazon.com/blogs/business-productivity/build-chat-applications-in-ios-and-android-with-amazon-chime-sdk-messaging/)
- [Amazon Chime SDK 메시징으로 애플리케이션에 채팅 기능 구축](https://aws.amazon.com/blogs/business-productivity/build-chat-features-into-your-application-with-amazon-chime-sdk-messaging/)
- [Amazon Chime SDK 메시징과 ID 공급자 통합](https://aws.amazon.com/blogs/business-productivity/integrate-your-identity-provider-with-amazon-chime-sdk-messaging/)
- [공지사항용 읽기 전용 채팅 채널 생성](https://aws.amazon.com/blogs/business-productivity/creating-read-only-chat-channels-for-announcements-with-amazon-chime-sdk-messaging/)
- [Amazon Chime SDK 메시징을 사용한 실시간 협업](https://aws.amazon.com/blogs/business-productivity/real-time-collaboration-using-amazon-chime-sdk-messaging/)
- [라이브 스트리밍 채팅 애플리케이션 구축](https://aws.amazon.com/blogs/business-productivity/build-a-live-streaming-chat-application-using-amazon-ivs-and-amazon-chime-sdk)

### 미디어 파이프라인

- [미디어 캡처 파이프라인을 사용하여 Amazon Chime SDK 미팅 캡처](https://aws.amazon.com/blogs/business-productivity/capture-amazon-chime-sdk-meetings-using-media-capture-pipelines/)
- [Amazon Chime SDK, 스트리밍용 라이브 커넥터 출시](https://aws.amazon.com/blogs/business-productivity/amazon-chime-sdk-launches-live-connector-for-streaming/)

### 웨비나 및 비디오

- [웨비나: Amazon Chime SDK를 사용한 교실 경험 만들기](https://www.youtube.com/watch?v=S8T-0xfvXJ8)

## JavaScript SDK 가이드

다음 개발자 가이드는 기술 청중을 위한 특정 주제를 다룹니다.

- [API 개요](https://aws.github.io/amazon-chime-sdk-js/modules/apioverview.html)
- [자주 묻는 질문 (FAQ)](https://aws.github.io/amazon-chime-sdk-js/modules/faqs.html)
- [콘텐츠 공유](https://aws.github.io/amazon-chime-sdk-js/modules/contentshare.html)
- [품질, 대역폭 및 연결성](https://aws.github.io/amazon-chime-sdk-js/modules/qualitybandwidth_connectivity.html)
- [Simulcast](https://aws.github.io/amazon-chime-sdk-js/modules/simulcast.html)
- [미팅 이벤트](https://aws.github.io/amazon-chime-sdk-js/modules/meetingevents.html)
- [애플리케이션에 Amazon Voice Focus 및 Echo Reduction 통합](https://aws.github.io/amazon-chime-sdk-js/modules/amazonvoice_focus.html)
- [나가는 비디오 스트림에 프레임별 처리 추가](https://aws.github.io/amazon-chime-sdk-js/modules/videoprocessor.html)
- [나가는 비디오 스트림에 배경 필터링 추가](https://aws.github.io/amazon-chime-sdk-js/modules/backgroundfilter_videofx_processor.html)
- [우선순위 기반 비디오 다운링크 정책을 사용하여 제한된 대역폭에 비디오 적응](https://aws.github.io/amazon-chime-sdk-js/modules/prioritybased_downlink_policy.html)
- [클라이언트 이벤트 수집](https://aws.github.io/amazon-chime-sdk-js/modules/clientevent_ingestion.html)
- [콘텐츠 보안 정책](https://aws.github.io/amazon-chime-sdk-js/modules/contentsecurity_policy.html)
- [다양한 비디오 레이아웃에 대한 비디오 품질 관리](https://aws.github.io/amazon-chime-sdk-js/modules/videolayout.html)

## 마이그레이션 가이드

- [V1.0에서 V2.0으로 마이그레이션](https://aws.github.io/amazon-chime-sdk-js/modules/migrationto_2_0.html)
- [V2.0에서 V3.0으로 마이그레이션](https://aws.github.io/amazon-chime-sdk-js/modules/migrationto_3_0.html)

## 개발자 가이드

다음 개발자 가이드는 Amazon Chime SDK를 더 광범위하게 다룹니다.

- [메시징 개발자 가이드](https://docs.aws.amazon.com/chime-sdk/latest/dg/using-the-messaging-sdk.html)
- [미디어 파이프라인 개발자 가이드](https://docs.aws.amazon.com/chime-sdk/latest/dg/media-pipelines.html)

## 예제

- [Amazon Chime SDK 샘플](https://github.com/aws-samples/amazon-chime-sdk) — Amazon Chime SDK 샘플 저장소
- [미팅 데모](https://github.com/aws/amazon-chime-sdk-js/tree/main/demos/browser) — 로컬 서버가 있는 브라우저 미팅 애플리케이션
- [서버리스 미팅 데모](https://github.com/aws/amazon-chime-sdk-js/tree/main/demos/serverless) — 독립형 서버리스 미팅 애플리케이션
- [Single JS](https://github.com/aws-samples/amazon-chime-sdk/tree/main/utils/singlejs) — SDK를 단일 `.js` 파일로 번들링하는 스크립트
- [전사 및 미디어 캡처 데모](https://github.com/aws-samples/amazon-chime-media-capture-pipeline-demo) - 전사 및 미디어 캡처 기능을 시연하는 데모
- [가상 교실](https://aws.amazon.com/blogs/business-productivity/building-a-virtual-classroom-application-using-the-amazon-chime-sdk/) — Electron 및 React로 구축된 온라인 교실
- [라이브 이벤트](https://aws.amazon.com/blogs/opensource/how-to-deploy-a-live-events-solution-built-with-the-amazon-chime-sdk/) — 대화형 라이브 이벤트 솔루션
- [Amazon Chime SDK 스마트 비디오 전송 데모](https://aws.amazon.com/blogs/business-productivity/amazon-chime-sdk-smart-video-sending-demo/) — 최대 250명의 미팅 참석자 풀에서 최대 25개의 비디오 타일을 동적으로 표시하는 방법을 보여주는 데모
- [Amazon Chime SDK 및 Amazon Connect 통합](https://aws.amazon.com/blogs/business-productivity/build-a-video-contact-center-with-amazon-connect-and-amazon-chime-sdk/) — Amazon Connect 및 Amazon Chime SDK로 비디오 컨택 센터 구축
- [장치 통합](https://aws.amazon.com/blogs/business-productivity/using-the-amazon-chime-sdk-for-3rd-party-devices/) — 타사 장치용 Amazon Chime SDK 사용
- [메시징](https://aws.amazon.com/blogs/business-productivity/build-chat-features-into-your-application-with-amazon-chime-sdk-messaging/) — Amazon Chime SDK 메시징으로 애플리케이션에 채팅 기능 구축
- [부하 테스트 애플리케이션](https://aws.amazon.com/blogs/business-productivity/load-testing-applications-built-with-the-amazon-chime-sdk/) — 오디오-비디오 통신 애플리케이션 부하 테스트 도구

### PSTN 오디오 예제

- [PSTN 다이얼 인](https://github.com/aws-samples/chime-sipmediaapplication-samples) — SIP 미디어 애플리케이션을 사용하여 Amazon Chime SDK 미팅에 PSTN 다이얼 인 기능 추가
- [아웃바운드 통화 알림](https://github.com/aws-samples/amazon-chime-sma-outbound-call-notifications) — SIP 미디어 애플리케이션으로 미팅 알림 전송 및 실시간 결과 수신
- [진행 중인 통화 업데이트](https://github.com/aws-samples/amazon-chime-sma-update-call) - API 호출을 통해 진행 중인 SIP 미디어 애플리케이션 통화 업데이트

## 문제 해결 및 지원

README에 제공된 리소스를 검토하고 Chime SDK for JavaScript 개발 방법에 대한 지침은 [클라이언트 문서](https://aws.github.io/amazon-chime-sdk-js/)를 사용하세요. 또한 [이슈 데이터베이스](https://github.com/aws/amazon-chime-sdk-js/issues) 및 [FAQ](https://aws.github.io/amazon-chime-sdk-js/modules/faqs.html)를 검색하여 문제가 이미 해결되었는지 확인하세요. 그렇지 않은 경우 제공된 템플릿을 사용하여 [이슈](https://github.com/aws/amazon-chime-sdk-js/issues/new/choose)를 작성해 주세요.

블로그 게시물 [Amazon Chime SDK 미팅 이벤트로 모니터링 및 문제 해결](https://aws.amazon.com/blogs/business-productivity/monitoring-and-troubleshooting-with-amazon-chime-sdk-meeting-events/)에서는 Amazon CloudWatch에 로깅하여 미팅 이벤트를 사용하여 애플리케이션 문제를 해결하는 방법에 대해 자세히 설명합니다.

더 많은 질문이 있거나 비즈니스 지원이 필요한 경우 [AWS 고객 지원](https://pages.awscloud.com/GLOBAL-aware-GC-Amazon-Chime-SDK-2020-reg.html)에 문의할 수 있습니다. 지원 플랜은 [여기](https://aws.amazon.com/premiumsupport/plans/?nc=sn&loc=1)에서 검토할 수 있습니다.

## WebRTC 리소스

Amazon Chime SDK for JavaScript는 대부분의 최신 브라우저에서 지원되는 실시간 통신 API인 WebRTC를 사용합니다. 다음은 WebRTC에 대한 일반적인 리소스입니다.

- [WebRTC 기초](https://www.html5rocks.com/en/tutorials/webrtc/basics/)
- [WebRTC Org - 시작하기, 프레젠테이션, 샘플, 튜토리얼, 책 및 기타 리소스](https://webrtc.github.io/webrtc-org/start/)
- [고성능 브라우저 네트워킹 - WebRTC (브라우저 API 및 프로토콜)](https://hpbn.co/webrtc/)
- [MDN - WebRTC API](https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API)

## 설치

Node.js 버전 18 이상이 있는지 확인하세요. Node 20을 권장하고 지원합니다.

기존 애플리케이션에 Amazon Chime SDK for JavaScript를 추가하려면 npm에서 직접 패키지를 설치하세요:

```
npm install amazon-chime-sdk-js --save
```

Amazon Chime SDK for JavaScript는 ES2015를 대상으로 하며, 이는 지원되는 모든 브라우저와 완전히 호환됩니다.

## 설정

### 미팅 세션

클라이언트 애플리케이션에서 미팅 세션을 생성합니다.

```js
import {
  ConsoleLogger,
  DefaultDeviceController,
  DefaultMeetingSession,
  LogLevel,
  MeetingSessionConfiguration
} from 'amazon-chime-sdk-js';

const logger = new ConsoleLogger('MyLogger', LogLevel.INFO);
const deviceController = new DefaultDeviceController(logger);

// 서버 측 Chime API의 응답이 필요합니다. 자세한 내용은 아래를 참조하세요.
const meetingResponse = /* CreateMeeting API 작업의 응답 */;
const attendeeResponse = /* CreateAttendee 또는 BatchCreateAttendee API 작업의 응답 */;
const configuration = new MeetingSessionConfiguration(meetingResponse, attendeeResponse);

// 아래 사용 예제에서 이 meetingSession 객체를 사용합니다.
const meetingSession = new DefaultMeetingSession(
  configuration,
  logger,
  deviceController
);
```

#### 서버 애플리케이션에서 응답 받기

AWS SDK, AWS 명령줄 인터페이스(AWS CLI) 또는 REST API를 사용하여 API 호출을 수행할 수 있습니다. 이 섹션에서는 서버 애플리케이션(예: Node.js)에서 JavaScript용 AWS SDK를 사용합니다.
자세한 내용은 [Amazon Chime SDK API 참조](https://docs.aws.amazon.com/chime-sdk/latest/APIReference/welcome.html)를 참조하세요.

> ⚠️ 서버 애플리케이션에는 Amazon Chime SDK for JavaScript가 필요하지 않습니다.

```js
const AWS = require('aws-sdk');
const { v4: uuid } = require('uuid');

// Chime API의 리전으로 "us-east-1"을 사용하고 엔드포인트를 설정해야 합니다.
const chime = new AWS.ChimeSDKMeetings({ region: 'us-east-1' });

const meetingResponse = await chime
  .createMeeting({
    ClientRequestToken: uuid(),
    MediaRegion: 'us-west-2', // 미팅을 생성할 리전을 지정합니다.
  })
  .promise();

const attendeeResponse = await chime
  .createAttendee({
    MeetingId: meetingResponse.Meeting.MeetingId,
    ExternalUserId: uuid(), // 참석자를 애플리케이션에서 관리하는 ID에 연결합니다.
  })
  .promise();
```

이제 `meetingResponse` 및 `attendeeResponse` 객체를 클라이언트 애플리케이션으로 안전하게 전송합니다.
이러한 객체에는 Amazon Chime SDK for JavaScript를 사용하는 클라이언트 애플리케이션이 미팅에 참가하는 데 필요한 모든 정보가 포함되어 있습니다.

createMeeting()의 MediaRegion 매개변수 값은 미팅을 생성하는 사용자와 가장 가까운 미디어 리전 중 하나로 설정하는 것이 이상적입니다. 구현은 [Amazon Chime SDK 미디어 리전 문서](https://docs.aws.amazon.com/chime-sdk/latest/dg/chime-sdk-meetings-regions.html)의 '가장 가까운 미디어 리전 선택' 주제에서 찾을 수 있습니다.

### 메시징 세션

Amazon Chime SDK for Messaging에서 메시지를 수신하려면 클라이언트 애플리케이션에서 메시징 세션을 생성합니다.

```js
import { ChimeSDKMessagingClient } from '@aws-sdk/client-chime-sdk-messaging';

import {
  ConsoleLogger,
  DefaultMessagingSession,
  LogLevel,
  MessagingSessionConfiguration,
} from 'amazon-chime-sdk-js';

const logger = new ConsoleLogger('SDK', LogLevel.INFO);

// AWS 또는 Amazon Chime API를 호출하기 전에 AWS 자격 증명을 구성해야 합니다.
const chime = new ChimeSDKMessagingClient({ region: 'us-east-1'});

const userArn = /* userArn */;
const sessionId = /* sessionId */;
const configuration = new MessagingSessionConfiguration(userArn, sessionId, undefined, chime);
const messagingSession = new DefaultMessagingSession(configuration, logger);
```

메시징 세션에 연결할 때 프리페치 기능을 활성화하려면 아래 코드를 따르세요.
프리페치 기능은 웹소켓 연결 시 CHANNEL_DETAILS 이벤트를 전송하며, 여기에는 채널, 채널 메시지, 채널 멤버십 등에 대한 정보가 포함됩니다. 프리페치 정렬 순서는 `prefetchSortBy`로 조정할 수 있으며, `unread`(설정하지 않은 경우 기본값) 또는 `lastMessageTimestamp`로 설정할 수 있습니다.

```js
configuration.prefetchOn = Prefetch.Connect;
configuration.prefetchSortBy = PrefetchSortBy.Unread;
```

## 빌드 및 테스트

```
git fetch --tags https://github.com/aws/amazon-chime-sdk-js
npm run build
npm run test
```

`npm run test`를 처음 실행한 후 `npm run test:fast`를 사용하여 테스트 스위트 속도를 높일 수 있습니다.

버전 관리 메타데이터를 올바르게 생성하기 위해 태그를 가져옵니다.

`npm run test`를 실행한 후 브라우저에서 `coverage/index.html`을 열어 코드 커버리지 결과를 확인합니다.

`npm run test`를 실행하고 테스트가 실행되지만 커버리지 보고서가 생성되지 않는 경우 리소스 정리 문제가 있을 수 있습니다. Mocha v4.0.0 이상에서는 테스트 실행이 완료될 때 Mocha 프로세스가 강제 종료되지 않도록 구현이 변경되었습니다.

예를 들어, 단위 테스트에 `DefaultVideoTransformDevice`가 있는 경우 `await device.stop();`을 호출하여 리소스를 정리하고 이 문제가 발생하지 않도록 해야 합니다. [Mocha 문서](https://mochajs.org/#asynchronous-code)에서 `done();` 사용법도 살펴볼 수 있습니다.

## 문서 생성

JavaScript API 참조 문서를 생성하려면 다음을 실행하세요:

```
npm run build
npm run doc
```

그런 다음 브라우저에서 `docs/index.html`을 엽니다.

## 의심되는 취약점 보고

이 프로젝트에서 잠재적인 보안 문제를 발견한 경우 [취약점 보고 페이지](https://aws.amazon.com/security/vulnerability-reporting/)를 통해 AWS/Amazon Security에 알려주시기 바랍니다.
공개 GitHub 이슈를 생성하지 **마세요**.

## 사용법

- [장치](#장치)
- [세션 시작](#세션-시작)
- [오디오](#오디오)
- [비디오](#비디오)
- [화면 및 콘텐츠 공유](#화면-및-콘텐츠-공유)
- [참석자](#참석자)
- [모니터링 및 알림](#모니터링-및-알림)
- [세션 중지](#세션-중지)
- [미팅 준비 검사기](#미팅-준비-검사기)
- [오디오 프로필 선택](#오디오-프로필-선택)
- [메시징 세션 시작](#메시징-세션-시작)
- [애플리케이션 메타데이터 제공](#애플리케이션-메타데이터-제공)

### 장치

> 참고: 세션을 시작하기 전에 마이크, 스피커 및 카메라를 선택해야 합니다.

**사용 사례 1.** 오디오 입력, 오디오 출력 및 비디오 입력 장치를 나열합니다. 브라우저가 마이크 및 카메라 권한을 요청합니다.

`forceUpdate` 매개변수를 true로 설정하면 캐시된 장치 정보가 삭제되고 장치 레이블 트리거가 호출된 후 업데이트됩니다. 경우에 따라 빌더는 권한 대화 상자 트리거를 지연해야 합니다(예: 보기 전용 모드로 미팅에 참가할 때). 나중에 장치 레이블을 표시하기 위해 권한 프롬프트를 트리거할 수 있습니다. `forceUpdate`를 지정하면 이를 수행할 수 있습니다.

```js
const audioInputDevices = await meetingSession.audioVideo.listAudioInputDevices();
const audioOutputDevices = await meetingSession.audioVideo.listAudioOutputDevices();
const videoInputDevices = await meetingSession.audioVideo.listVideoInputDevices();

// MediaDeviceInfo 객체의 배열
audioInputDevices.forEach(mediaDeviceInfo => {
  console.log(`Device ID: ${mediaDeviceInfo.deviceId} Microphone: ${mediaDeviceInfo.label}`);
});
```

**사용 사례 2.** `MediaDeviceInfo` 객체의 `deviceId`를 전달하여 오디오 입력 및 오디오 출력 장치를 선택합니다.
먼저 `listAudioInputDevices` 및 `listAudioOutputDevices`를 호출해야 합니다.

```js
const audioInputDeviceInfo = /* meetingSession.audioVideo.listAudioInputDevices의 배열 항목 */;
await meetingSession.audioVideo.startAudioInput(audioInputDeviceInfo.deviceId);

const audioOutputDeviceInfo = /* meetingSession.audioVideo.listAudioOutputDevices의 배열 항목 */;
await meetingSession.audioVideo.chooseAudioOutput(audioOutputDeviceInfo.deviceId);
```

**사용 사례 3.** `MediaDeviceInfo` 객체의 `deviceId`를 전달하여 비디오 입력 장치를 선택합니다.
먼저 `listVideoInputDevices`를 호출해야 합니다.

참석자의 카메라 옆에 LED 표시등이 있는 경우 카메라에서 캡처 중임을 나타내는 표시등이 켜집니다.
비디오 공유를 시작할 때 비디오 입력 장치를 선택하는 것이 좋습니다.

```js
const videoInputDeviceInfo = /* meetingSession.audioVideo.listVideoInputDevices의 배열 항목 */;
await meetingSession.audioVideo.startVideoInput(videoInputDeviceInfo.deviceId);

// 비디오 입력을 중지합니다. 이전에 선택한 카메라에 LED 표시등이 켜져 있으면
// 카메라가 더 이상 캡처하지 않음을 나타내는 표시등이 꺼집니다.
await meetingSession.audioVideo.stopVideoInput();
```

**사용 사례 4.** 업데이트된 장치 목록을 수신하려면 장치 변경 관찰자를 추가합니다.
예를 들어, 컴퓨터와 Bluetooth 헤드셋을 페어링하면 헤드셋을 포함한 장치 목록과 함께 `audioInputsChanged` 및 `audioOutputsChanged`가 호출됩니다.

`audioInputMuteStateChanged` 콜백을 사용하여 이를 지원하는 브라우저 및 운영 체제에서 기본 하드웨어 음소거 상태를 추적할 수 있습니다.

```js
const observer = {
  audioInputsChanged: freshAudioInputDeviceList => {
    // MediaDeviceInfo 객체의 배열
    freshAudioInputDeviceList.forEach(mediaDeviceInfo => {
      console.log(`Device ID: ${mediaDeviceInfo.deviceId} Microphone: ${mediaDeviceInfo.label}`);
    });
  },

  audioOutputsChanged: freshAudioOutputDeviceList => {
    console.log('Audio outputs updated: ', freshAudioOutputDeviceList);
  },

  videoInputsChanged: freshVideoInputDeviceList => {
    console.log('Video inputs updated: ', freshVideoInputDeviceList);
  },

  audioInputMuteStateChanged: (device, muted) => {
    console.log('Device', device, muted ? 'is muted in hardware' : 'is not muted');
  },
};

meetingSession.audioVideo.addDeviceChangeObserver(observer);
```

### 세션 시작

**사용 사례 5.** 세션을 시작합니다. 오디오를 들으려면 장치와 스트림을 `<audio>` 요소에 바인딩해야 합니다.
세션이 시작되면 참석자와 대화하고 들을 수 있습니다.
마이크와 스피커를 선택했는지 확인하고("장치" 섹션 참조), 최소한 한 명의 다른 참석자가 세션에 참가했는지 확인하세요.

```js
const audioElement = /* HTMLAudioElement 객체 예: document.getElementById('audio-element-id') */;
meetingSession.audioVideo.bindAudioElement(audioElement);

const observer = {
  audioVideoDidStart: () => {
    console.log('Started');
  }
};

meetingSession.audioVideo.addObserver(observer);

meetingSession.audioVideo.start();
```

**사용 사례 6.** 세션 수명 주기 이벤트(연결 중, 시작 및 중지)를 수신하려면 관찰자를 추가합니다.

> 참고: `meetingSession.audioVideo.removeObserver(observer)`를 호출하여 관찰자를 제거할 수 있습니다.
> 컴포넌트 기반 아키텍처(예: React, Vue 및 Angular)에서는 컴포넌트가 마운트될 때 관찰자를 추가하고 마운트 해제될 때 제거해야 할 수 있습니다.

```js
const observer = {
  audioVideoDidStart: () => {
    console.log('Started');
  },
  audioVideoDidStop: sessionStatus => {
    // 자세한 내용은 "세션 중지" 섹션을 참조하세요.
    console.log('Stopped with a session status code: ', sessionStatus.statusCode());
  },
  audioVideoDidStartConnecting: reconnecting => {
    if (reconnecting) {
      // 예: WiFi 연결이 끊어졌습니다.
      console.log('Attempting to reconnect');
    }
  },
};

meetingSession.audioVideo.addObserver(observer);
```

### 오디오

> 참고: 지금까지 장치 및 세션 수명 주기 이벤트를 수신하기 위해 관찰자를 추가했습니다.
> 다음 사용 사례에서는 실시간 API 메서드를 사용하여 볼륨 표시기를 보내고 받고 음소거 상태를 제어합니다.

**사용 사례 7.** 오디오 입력을 음소거 및 음소거 해제합니다.

```js
// 음소거
meetingSession.audioVideo.realtimeMuteLocalAudio();

// 음소거 해제
const unmuted = meetingSession.audioVideo.realtimeUnmuteLocalAudio();
if (unmuted) {
  console.log('Other attendees can hear your audio');
} else {
  // 아래의 realtimeSetCanUnmuteLocalAudio 사용 사례를 참조하세요.
  console.log('You cannot unmute yourself');
}
```

**사용 사례 8.** 로컬 마이크가 음소거되었는지 확인하려면 자체 음소거 상태를 추적하는 대신 이 메서드를 사용하세요.

```js
const muted = meetingSession.audioVideo.realtimeIsLocalAudioMuted();
if (muted) {
  console.log('You are muted');
} else {
  console.log('Other attendees can hear your audio');
}
```

**사용 사례 9.** 음소거 해제를 비활성화합니다. 사용자가 스스로 음소거를 해제하지 못하도록 하려면(예: 프레젠테이션 중) 자체 음소거 해제 가능 상태를 추적하는 대신 이러한 메서드를 사용하세요.

```js
meetingSession.audioVideo.realtimeSetCanUnmuteLocalAudio(false);

// 선택 사항: 강제 음소거.
meetingSession.audioVideo.realtimeMuteLocalAudio();

const unmuted = meetingSession.audioVideo.realtimeUnmuteLocalAudio();
console.log(`${unmuted} is false. You cannot unmute yourself`);
```

**사용 사례 10.** 특정 참석자의 볼륨 변경을 구독합니다. 이를 사용하여 실시간 볼륨 표시기 UI를 구축할 수 있습니다.

```js
import { DefaultModality } from 'amazon-chime-sdk-js';

// 이것은 귀하의 참석자 ID입니다. 다른 참석자의 ID를 구독할 수도 있습니다.
// 세션에서 다른 참석자 ID를 검색하는 방법에 대한 예는 "참석자" 섹션을 참조하세요.
const presentAttendeeId = meetingSession.configuration.credentials.attendeeId;

meetingSession.audioVideo.realtimeSubscribeToVolumeIndicator(
  presentAttendeeId,
  (attendeeId, volume, muted, signalStrength) => {
    const baseAttendeeId = new DefaultModality(attendeeId).base();
    if (baseAttendeeId !== attendeeId) {
      // 자세한 내용은 "화면 및 콘텐츠 공유" 섹션을 참조하세요.
      console.log(`The volume of ${baseAttendeeId}'s content changes`);
    }

    // 필드의 null 값은 변경되지 않았음을 의미합니다.
    console.log(`${attendeeId}'s volume data: `, {
      volume, // 0과 1 사이의 분수
      muted, // 부울
      signalStrength, // 0 (신호 없음), 0.5 (약함), 1 (강함)
    });
  }
);
```

**사용 사례 11.** 특정 참석자의 음소거 또는 신호 강도 변경을 구독합니다. 이를 사용하여 음소거 또는 신호 강도 변경에 대한 UI만 구축할 수 있습니다.

```js
// 이것은 귀하의 참석자 ID입니다. 다른 참석자의 ID를 구독할 수도 있습니다.
// 세션에서 다른 참석자 ID를 검색하는 방법에 대한 예는 "참석자" 섹션을 참조하세요.
const presentAttendeeId = meetingSession.configuration.credentials.attendeeId;

// 음소거 변경 추적
meetingSession.audioVideo.realtimeSubscribeToVolumeIndicator(
  presentAttendeeId,
  (attendeeId, volume, muted, signalStrength) => {
    // volume, muted 및 signalStrength 필드의 null 값은 변경되지 않았음을 의미합니다.
    if (muted === null) {
      // 음소거 상태가 변경되지 않았으므로 볼륨 및 signalStrength 변경을 무시합니다.
      return;
    }

    // 음소거 상태 변경됨
    console.log(`${attendeeId}'s mute state changed: `, {
      muted, // 부울
    });
  }
);

// 신호 강도 변경 추적
meetingSession.audioVideo.realtimeSubscribeToVolumeIndicator(
  presentAttendeeId,
  (attendeeId, volume, muted, signalStrength) => {
    // volume, muted 및 signalStrength 필드의 null 값은 변경되지 않았음을 의미합니다.
    if (signalStrength === null) {
      // signalStrength가 변경되지 않았으므로 볼륨 및 음소거 변경을 무시합니다.
      return;
    }

    // 신호 강도 변경됨
    console.log(`${attendeeId}'s signal strength changed: `, {
      signalStrength, // 0 (신호 없음), 0.5 (약함), 1 (강함)
    });
  }
);
```

**사용 사례 12.** 가장 활발한 발언자를 감지합니다. 예를 들어, 사용 가능한 경우 활발한 발언자의 비디오 요소를 확대할 수 있습니다.

```js
import { DefaultActiveSpeakerPolicy } from 'amazon-chime-sdk-js';

const activeSpeakerCallback = attendeeIds => {
  if (attendeeIds.length) {
    console.log(`${attendeeIds[0]} is the most active speaker`);
  }
};

meetingSession.audioVideo.subscribeToActiveSpeakerDetector(
  new DefaultActiveSpeakerPolicy(),
  activeSpeakerCallback
);
```

### 비디오

> 참고: Chime SDK 용어에서 비디오 타일은 참석자 ID, 비디오 스트림 등을 포함하는 객체입니다. 애플리케이션에서 비디오를 보려면 타일을 `<video>` 요소에 바인딩해야 합니다.
>
> - 타일이 제거될 때까지 동일한 비디오 요소에 타일을 바인딩해야 합니다.
> - 로컬 비디오 타일은 `localTile` 속성을 사용하여 식별할 수 있습니다.
> - 동일한 원격 참석자가 비디오를 다시 시작하면 새 타일 ID로 타일이 생성됩니다.
> - 미디어 캡처 파이프라인은 미팅 세션에 의존하여 참석자 정보를 가져옵니다. `this.meetingSession.audioVideo.start();`를 호출한 후 `startLocalVideoTile`을 호출하기 전에 `audioVideoDidStart` 이벤트가 수신될 때까지 기다리세요.

**사용 사례 13.** 비디오 공유를 시작합니다. 로컬 비디오 요소는 수평으로 뒤집힙니다(미러 모드).

```js
const videoElement = /* HTMLVideoElement 객체 예: document.getElementById('video-element-id') */;

// 카메라를 선택했는지 확인하세요. 이 사용 사례에서는 첫 번째 장치를 선택합니다.
const videoInputDevices = await meetingSession.audioVideo.listVideoInputDevices();

// 카메라 LED 표시등이 켜져 현재 캡처 중임을 나타냅니다.
// 자세한 내용은 "장치" 섹션을 참조하세요.
await meetingSession.audioVideo.startVideoInput(videoInputDevices[0].deviceId);

const observer = {
  // videoTileDidUpdate는 새 타일이 생성되거나 tileState가 변경될 때마다 호출됩니다.
  videoTileDidUpdate: tileState => {
    // 참석자 ID가 없는 타일과 다른 참석자의 타일을 무시합니다.
    if (!tileState.boundAttendeeId || !tileState.localTile) {
      return;
    }

    meetingSession.audioVideo.bindVideoElement(tileState.tileId, videoElement);
  }
};

meetingSession.audioVideo.addObserver(observer);

meetingSession.audioVideo.startLocalVideoTile();
```

**사용 사례 14.** 비디오 공유를 중지합니다.

```js
const videoElement = /* HTMLVideoElement 객체 예: document.getElementById('video-element-id') */;

let localTileId = null;
const observer = {
  videoTileDidUpdate: tileState => {
    // 참석자 ID가 없는 타일과 다른 참석자의 타일을 무시합니다.
    if (!tileState.boundAttendeeId || !tileState.localTile) {
      return;
    }

    // videoTileDidUpdate는 startLocalVideoTile을 호출하거나 tileState가 변경될 때도 호출됩니다.
    // tileState.active는 인터넷 연결이 좋지 않거나 사용자가 비디오 타일을 일시 중지했거나 비디오 타일이 처음 도착했을 때 false일 수 있습니다.
    console.log(`If you called stopLocalVideoTile, ${tileState.active} is false.`);
    meetingSession.audioVideo.bindVideoElement(tileState.tileId, videoElement);
    localTileId = tileState.tileId;
  },
  videoTileWasRemoved: tileId => {
    if (localTileId === tileId) {
      console.log(`You called removeLocalVideoTile. videoElement can be bound to another tile.`);
      localTileId = null;
    }
  }
};

meetingSession.audioVideo.addObserver(observer);

meetingSession.audioVideo.stopLocalVideoTile();

// 비디오 입력을 중지합니다. 이전에 선택한 카메라에 LED 표시등이 켜져 있으면
// 카메라가 더 이상 캡처하지 않음을 나타내는 표시등이 꺼집니다.
await meetingSession.audioVideo.stopVideoInput();

// 선택 사항: 세션에서 로컬 타일을 제거할 수 있습니다.
meetingSession.audioVideo.removeLocalVideoTile();
```

**사용 사례 15.** 한 명의 참석자 비디오 보기(예: 1:1 세션).

```js
const videoElement = /* HTMLVideoElement 객체 예: document.getElementById('video-element-id') */;

const observer = {
  // videoTileDidUpdate는 새 타일이 생성되거나 tileState가 변경될 때마다 호출됩니다.
  videoTileDidUpdate: tileState => {
    // 참석자 ID가 없는 타일, 로컬 타일(귀하의 비디오) 및 콘텐츠 공유를 무시합니다.
    if (!tileState.boundAttendeeId || tileState.localTile || tileState.isContent) {
      return;
    }

    meetingSession.audioVideo.bindVideoElement(tileState.tileId, videoElement);
  }
};

meetingSession.audioVideo.addObserver(observer);
```

**사용 사례 16.** 최대 25명의 참석자 비디오를 봅니다. 애플리케이션에 25개의 비디오 요소가 있고 빈 셀은 사용 중임을 의미한다고 가정합니다.

```js
/*
  아무도 비디오를 공유하지 않음                예: 9개의 참석자 비디오 (9개의 빈 셀)

  다음 사용 가능:                            다음 사용 가능:
  videoElements[0]                           videoElements[7]
  ╔════╦════╦════╦════╦════╗                 ╔════╦════╦════╦════╦════╗
  ║  0 ║  1 ║  2 ║  3 ║  4 ║                 ║    ║    ║    ║    ║    ║
  ╠════╬════╬════╬════╬════╣                 ╠════╬════╬════╬════╬════╣
  ║  5 ║  6 ║  7 ║  8 ║  9 ║                 ║    ║    ║  7 ║  8 ║    ║
  ╠════╬════╬════╬════╬════╣                 ╠════╬════╬════╬════╬════╣
  ║ 10 ║ 11 ║ 12 ║ 13 ║ 14 ║                 ║ 10 ║    ║ 12 ║ 13 ║ 14 ║
  ╠════╬════╬════╬════╬════╣                 ╠════╬════╬════╬════╬════╣
  ║ 15 ║ 16 ║ 17 ║ 18 ║ 19 ║                 ║ 15 ║ 16 ║ 17 ║ 18 ║ 19 ║
  ╠════╬════╬════╬════╬════╣                 ╠════╬════╬════╬════╬════╣
  ║ 20 ║ 21 ║ 22 ║ 23 ║ 24 ║                 ║ 20 ║ 21 ║ 22 ║ 23 ║ 24 ║
  ╚════╩════╩════╩════╩════╝                 ╚════╩════╩════╩════╩════╝
 */
const videoElements = [
  /* 애플리케이션의 25개 HTMLVideoElement 객체 배열 */
];

// index-tileId 쌍
const indexMap = {};

const acquireVideoElement = tileId => {
  // 이미 바인딩된 경우 동일한 비디오 요소를 반환합니다.
  for (let i = 0; i < 25; i += 1) {
    if (indexMap[i] === tileId) {
      return videoElements[i];
    }
  }
  // 다음 사용 가능한 비디오 요소를 반환합니다.
  for (let i = 0; i < 25; i += 1) {
    if (!indexMap.hasOwnProperty(i)) {
      indexMap[i] = tileId;
      return videoElements[i];
    }
  }
  throw new Error('no video element is available');
};

const releaseVideoElement = tileId => {
  for (let i = 0; i < 25; i += 1) {
    if (indexMap[i] === tileId) {
      delete indexMap[i];
      return;
    }
  }
};

const observer = {
  // videoTileDidUpdate는 새 타일이 생성되거나 tileState가 변경될 때마다 호출됩니다.
  videoTileDidUpdate: tileState => {
    // 참석자 ID가 없는 타일, 로컬 타일(귀하의 비디오) 및 콘텐츠 공유를 무시합니다.
    if (!tileState.boundAttendeeId || tileState.localTile || tileState.isContent) {
      return;
    }

    meetingSession.audioVideo.bindVideoElement(
      tileState.tileId,
      acquireVideoElement(tileState.tileId)
    );
  },
  videoTileWasRemoved: tileId => {
    releaseVideoElement(tileId);
  },
};

meetingSession.audioVideo.addObserver(observer);
```

**사용 사례 17.** 변경 시 모든 원격 비디오 소스를 알기 위해 관찰자를 추가합니다.

```js
const observer = {
  remoteVideoSourcesDidChange: videoSources => {
    videoSources.forEach(videoSource => {
      const { attendee } = videoSource;
      console.log(
        `An attendee (${attendee.attendeeId} ${attendee.externalUserId}) is sending video`
      );
    });
  },
};

meetingSession.audioVideo.addObserver(observer);
```

모든 원격 비디오 소스를 알기 위해 아래 메서드를 호출할 수도 있습니다:

> 참고: `getRemoteVideoSources` 메서드는 `getAllRemoteVideoTiles`와 다릅니다.
> `getRemoteVideoSources`는 볼 수 있는 모든 원격 비디오 소스를 반환하는 반면,
> `getAllRemoteVideoTiles`는 실제로 보고 있는 것을 반환합니다.

```js
const videoSources = meetingSession.audioVideo.getRemoteVideoSources();
videoSources.forEach(videoSource => {
  const { attendee } = videoSource;
  console.log(`An attendee (${attendee.attendeeId} ${attendee.externalUserId}) is sending video`);
});
```

### 화면 및 콘텐츠 공유

> 참고: 귀하 또는 다른 참석자가 콘텐츠(화면 캡처, 비디오 파일 또는 기타 MediaStream 객체)를 공유하면
> 콘텐츠 참석자(attendee-id#content)가 세션에 참가하고 일반 참석자가 비디오를 공유하는 것처럼 콘텐츠를 공유합니다.
>
> 예를 들어, 귀하의 참석자 ID가 "my-id"인 경우 `meetingSession.audioVideo.startContentShare`를 호출하면
> 콘텐츠 참석자 "my-id#content"가 세션에 참가하고 콘텐츠를 공유합니다.

**사용 사례 18.** 화면 공유를 시작합니다.

```js
import { DefaultModality } from 'amazon-chime-sdk-js';

const observer = {
  videoTileDidUpdate: tileState => {
    // 참석자 ID가 없는 타일과 비디오를 무시합니다.
    if (!tileState.boundAttendeeId || !tileState.isContent) {
      return;
    }

    const yourAttendeeId = meetingSession.configuration.credentials.attendeeId;

    // tileState.boundAttendeeId는 "attendee-id#content" 형식입니다.
    const boundAttendeeId = tileState.boundAttendeeId;

    // "attendee-id#content"에서 참석자 ID를 가져옵니다.
    const baseAttendeeId = new DefaultModality(boundAttendeeId).base();
    if (baseAttendeeId === yourAttendeeId) {
      console.log('You called startContentShareFromScreenCapture');
    }
  },
  contentShareDidStart: () => {
    console.log('Screen share started');
  },
  contentShareDidStop: () => {
    // Chime SDK는 미팅당 2개의 동시 콘텐츠 공유를 허용합니다.
    // startContentShareFromScreenCapture 또는 startContentShare를 호출할 때 두 명의 참석자가 이미 콘텐츠를 공유하고 있으면 이 메서드가 호출됩니다.
    console.log('Screen share stopped');
  },
};

meetingSession.audioVideo.addContentShareObserver(observer);
meetingSession.audioVideo.addObserver(observer);

// 브라우저가 사용자에게 화면을 선택하라는 메시지를 표시합니다.
const contentShareStream = await meetingSession.audioVideo.startContentShareFromScreenCapture();
```

공유자를 위해 콘텐츠 공유 스트림을 표시하려면 DefaultVideoTile의 `connectVideoStreamToVideoElement`를 사용하여 반환된 콘텐츠 공유 스트림을 비디오 요소에 바인딩할 수 있습니다.

```js
DefaultVideoTile.connectVideoStreamToVideoElement(contentShareStream, videoElement, false);
```

**사용 사례 19.** 화면 선택 대화 상자를 지원하지 않는 환경에서 화면 공유를 시작합니다(예: Electron).

```js
const sourceId = /* 창 또는 화면 ID 예: Electron의 DesktopCapturerSource 객체 ID */;

await meetingSession.audioVideo.startContentShareFromScreenCapture(sourceId);
```

**사용 사례 20.** `file` 유형의 `<input>` 요소에서 비디오 파일 스트리밍을 시작합니다.

```js
const videoElement = /* HTMLVideoElement 객체 예: document.getElementById('video-element-id') */;
const inputElement = /* HTMLInputElement 객체 예: document.getElementById('input-element-id') */;

inputElement.addEventListener('change', async () => {
  const file = inputElement.files[0];
  const url = URL.createObjectURL(file);
  videoElement.src = url;
  await videoElement.play();

  const mediaStream = videoElement.captureStream(); /* Firefox의 경우 mozCaptureStream 사용 예: videoElement.mozCaptureStream(); */
  await meetingSession.audioVideo.startContentShare(mediaStream);
  inputElement.value = '';
});
```

**사용 사례 21.** 화면 또는 콘텐츠 공유를 중지합니다.

```js
const observer = {
  contentShareDidStop: () => {
    console.log('Content share stopped');
  },
};

meetingSession.audioVideo.addContentShareObserver(observer);

await meetingSession.audioVideo.stopContentShare();
```

**사용 사례 22.** 최대 2명의 참석자 콘텐츠 또는 화면을 봅니다. Chime SDK는 미팅당 2개의 동시 콘텐츠 공유를 허용합니다.

```js
import { DefaultModality } from 'amazon-chime-sdk-js';

const videoElementStack = [
  /* 애플리케이션의 2개 HTMLVideoElement 객체 배열 */
];

// tileId-videoElement 맵
const tileMap = {};

const observer = {
  videoTileDidUpdate: tileState => {
    // 참석자 ID가 없는 타일과 비디오를 무시합니다.
    if (!tileState.boundAttendeeId || !tileState.isContent) {
      return;
    }

    const yourAttendeeId = meetingSession.configuration.credentials.attendeeId;

    // tileState.boundAttendeeId는 "attendee-id#content" 형식입니다.
    const boundAttendeeId = tileState.boundAttendeeId;

    // "attendee-id#content"에서 참석자 ID를 가져옵니다.
    const baseAttendeeId = new DefaultModality(boundAttendeeId).base();
    if (baseAttendeeId !== yourAttendeeId) {
      console.log(`${baseAttendeeId} is sharing screen now`);

      // 사용 가능한 경우 이미 바인딩된 비디오 요소를 가져오거나 바인딩되지 않은 요소를 사용합니다.
      const videoElement = tileMap[tileState.tileId] || videoElementStack.pop();
      if (videoElement) {
        tileMap[tileState.tileId] = videoElement;
        meetingSession.audioVideo.bindVideoElement(tileState.tileId, videoElement);
      } else {
        console.log('No video element is available');
      }
    }
  },
  videoTileWasRemoved: tileId => {
    // 사용하지 않는 비디오 요소를 해제합니다.
    const videoElement = tileMap[tileId];
    if (videoElement) {
      videoElementStack.push(videoElement);
      delete tileMap[tileId];
    }
  },
};

meetingSession.audioVideo.addObserver(observer);
```

### 참석자

**사용 사례 23.** 참석자 출석 변경을 구독합니다. 참석자가 세션에 참가하거나 떠날 때
콜백은 `presentAttendeeId` 및 `present`(부울)를 받습니다.

```js
const attendeePresenceSet = new Set();
const callback = (presentAttendeeId, present) => {
  console.log(`Attendee ID: ${presentAttendeeId} Present: ${present}`);
  if (present) {
    attendeePresenceSet.add(presentAttendeeId);
  } else {
    attendeePresenceSet.delete(presentAttendeeId);
  }
};

meetingSession.audioVideo.realtimeSubscribeToAttendeeIdPresence(callback);
```

**사용 사례 24.** 참석자 출석 및 볼륨 변경을 구독하여 간단한 명단을 만듭니다.

```js
import { DefaultModality } from 'amazon-chime-sdk-js';

const roster = {};

meetingSession.audioVideo.realtimeSubscribeToAttendeeIdPresence((presentAttendeeId, present) => {
  if (!present) {
    delete roster[presentAttendeeId];
    return;
  }

  meetingSession.audioVideo.realtimeSubscribeToVolumeIndicator(
    presentAttendeeId,
    (attendeeId, volume, muted, signalStrength) => {
      const baseAttendeeId = new DefaultModality(attendeeId).base();
      if (baseAttendeeId !== attendeeId) {
        // 선택 사항: 명단에 콘텐츠 참석자(attendee-id#content)를 포함하지 마세요.
        // 자세한 내용은 "화면 및 콘텐츠 공유" 섹션을 참조하세요.
        return;
      }

      if (roster.hasOwnProperty(attendeeId)) {
        // 필드의 null 값은 변경되지 않았음을 의미합니다.
        roster[attendeeId].volume = volume; // 0과 1 사이의 분수
        roster[attendeeId].muted = muted; // 부울
        roster[attendeeId].signalStrength = signalStrength; // 0 (신호 없음), 0.5 (약함), 1 (강함)
      } else {
        // 참석자를 추가합니다.
        // 선택 사항: 서버 애플리케이션에서 참석자 이름과 같은 더 많은 데이터를 가져와 여기에 설정할 수 있습니다.
        roster[attendeeId] = {
          attendeeId,
          volume,
          muted,
          signalStrength,
        };
      }
    }
  );
});
```

### 모니터링 및 알림

**사용 사례 25.** 비트레이트, 패킷 손실 및 대역폭과 같이 Chime SDK에서 처리한 WebRTC 메트릭을 수신하려면 관찰자를 추가합니다. 사용 가능한 더 많은 메트릭은 `AudioVideoObserver`를 참조하세요.

```js
const observer = {
  metricsDidReceive: clientMetricReport => {
    const metricReport = clientMetricReport.getObservableMetrics();

    const {
      videoPacketSentPerSecond,
      videoUpstreamBitrate,
      availableOutgoingBitrate,
      availableIncomingBitrate,
      audioSpeakerDelayMs,
    } = metricReport;

    console.log(
      `Sending video bitrate in kilobits per second: ${
        videoUpstreamBitrate / 1000
      } and sending packets per second: ${videoPacketSentPerSecond}`
    );
    console.log(
      `Sending bandwidth is ${availableOutgoingBitrate / 1000}, and receiving bandwidth is ${
        availableIncomingBitrate / 1000
      }`
    );
    console.log(`Audio speaker delay is ${audioSpeakerDelayMs}`);
  },
};

meetingSession.audioVideo.addObserver(observer);
```

**사용 사례 26.** 알림을 수신하려면 관찰자를 추가합니다. 이러한 알림을 사용하여 사용자에게 연결 문제를 알릴 수 있습니다.

```js
const observer = {
  connectionDidBecomePoor: () => {
    console.log('Your connection is poor');
  },
  connectionDidSuggestStopVideo: () => {
    console.log('Recommend turning off your video');
  },
  videoSendDidBecomeUnavailable: () => {
    // Chime SDK는 미팅당 총 25개의 동시 비디오를 허용합니다.
    // 더 많은 비디오를 공유하려고 하면 이 메서드가 호출됩니다.
    // 사용 가능해지는 시기를 확인하려면 아래의 videoAvailabilityDidChange를 참조하세요.
    console.log('You cannot share your video');
  },
  videoAvailabilityDidChange: videoAvailability => {
    // 이미 비디오를 공유하고 있는 경우에도 canStartLocalVideo는 true입니다.
    if (videoAvailability.canStartLocalVideo) {
      console.log('You can share your video');
    } else {
      console.log('You cannot share your video');
    }
  },
};

meetingSession.audioVideo.addObserver(observer);
```

### 세션 중지

**사용 사례 27.** 세션을 떠납니다.

```js
import { MeetingSessionStatusCode } from 'amazon-chime-sdk-js';

const observer = {
  audioVideoDidStop: sessionStatus => {
    const sessionStatusCode = sessionStatus.statusCode();
    if (sessionStatusCode === MeetingSessionStatusCode.Left) {
      /*
       * meetingSession.audioVideo.stop()을 호출했습니다.
       */
      console.log('You left the session');
    } else {
      console.log('Stopped with a session status code: ', sessionStatusCode);
    }
  },
};

meetingSession.audioVideo.addObserver(observer);

meetingSession.audioVideo.stop();
```

**사용 사례 28.** 세션이 종료되었을 때 알림을 받으려면 관찰자를 추가합니다.

```js
import { MeetingSessionStatusCode } from 'amazon-chime-sdk-js';

const observer = {
  audioVideoDidStop: sessionStatus => {
    const sessionStatusCode = sessionStatus.statusCode();
    if (sessionStatusCode === MeetingSessionStatusCode.MeetingEnded) {
      /*
        - 귀하(또는 다른 사람)가 서버 애플리케이션에서 DeleteMeeting API 작업을 호출했습니다.
        - 삭제된 미팅에 참가하려고 시도했습니다.
        - 5분 이상 미팅에 오디오 연결이 없습니다.
        - 미팅 시간이 24시간을 초과합니다.
        자세한 내용은 https://docs.aws.amazon.com/chime-sdk/latest/dg/mtgs-sdk-mtgs.html을 참조하세요.
      */
      console.log('The session has ended');
    } else {
      console.log('Stopped with a session status code: ', sessionStatusCode);
    }
  },
};

meetingSession.audioVideo.addObserver(observer);
```

### 미팅 준비 검사기

**사용 사례 29.** 미팅 준비 검사기를 초기화합니다.

```js
import { DefaultMeetingReadinessChecker } from 'amazon-chime-sdk-js';

// 아래 사용 예제에서 이 meetingReadinessChecker 객체를 사용합니다.
const meetingReadinessChecker = new DefaultMeetingReadinessChecker(logger, meetingSession);
```

**사용 사례 30.** 미팅 준비 검사기를 사용하여 로컬 검사를 수행합니다.

```js
import { CheckAudioInputFeedback } from 'amazon-chime-sdk-js';

const audioInputDeviceInfo = /* meetingSession.audioVideo.listAudioInputDevices의 배열 항목 */;
const audioInputFeedback = await meetingReadinessChecker.checkAudioInput(audioInputDeviceInfo.deviceId);

switch (audioInputFeedback) {
  case CheckAudioInputFeedback.Succeeded:
    console.log('Succeeded');
    break;
  case CheckAudioInputFeedback.Failed:
    console.log('Failed');
    break;
  case CheckAudioInputFeedback.PermissionDenied:
    console.log('Permission denied');
    break;
}
```

**사용 사례 31.** 미팅 준비 검사기를 사용하여 오디오, 비디오 및 콘텐츠 공유와 같은 엔드 투 엔드 검사를 수행합니다.

```js
import {
  CheckAudioConnectivityFeedback,
  CheckContentShareConnectivityFeedback,
  CheckVideoConnectivityFeedback
} from 'amazon-chime-sdk-js';

// 오디오 연결 테스트
const audioDeviceInfo = /* meetingSession.audioVideo.listAudioInputDevices의 배열 항목 */;
const audioFeedback = await meetingReadinessChecker.checkAudioConnectivity(audioDeviceInfo.deviceId);
console.log(`Feedback result: ${CheckAudioConnectivityFeedback[audioFeedback]}`);

// 비디오 연결 테스트
const videoInputInfo = /* meetingSession.audioVideo.listVideoInputDevices의 배열 항목 */;
const videoFeedback = await meetingReadinessChecker.checkVideoConnectivity(videoInputInfo.deviceId);
console.log(`Feedback result: ${CheckVideoConnectivityFeedback[videoFeedback]}`);

// 콘텐츠 공유 연결 테스트
const contentShareFeedback = await meetingReadinessChecker.checkContentShareConnectivity();
console.log(`Feedback result: ${CheckContentShareConnectivityFeedback[contentShareFeedback]}`);
```

**사용 사례 32.** 미팅 준비 검사기를 사용하여 TCP 및 UDP와 같은 네트워크 검사를 수행합니다.

```js
import {
  CheckNetworkUDPConnectivityFeedback,
  CheckNetworkTCPConnectivityFeedback,
} from 'amazon-chime-sdk-js';

// UDP 네트워크 연결 테스트
const networkUDPFeedback = await meetingReadinessChecker.checkNetworkUDPConnectivity();
console.log(`Feedback result: ${CheckNetworkUDPConnectivityFeedback[networkUDPFeedback]}`);

// TCP 네트워크 연결 테스트
const networkTCPFeedback = await meetingReadinessChecker.checkNetworkTCPConnectivity();
console.log(`Feedback result: ${CheckNetworkTCPConnectivityFeedback[networkTCPFeedback]}`);
```

### 오디오 프로필 선택

**사용 사례 33.** 음성 또는 음악에 최적화하도록 메인 오디오 입력의 오디오 품질을 설정합니다:

모노 채널로 풀밴드 음성에 대한 메인 오디오 입력의 오디오 비트레이트를 최적화하려면 다음 설정을 사용하세요:

```js
meetingSession.audioVideo.setAudioProfile(AudioProfile.fullbandSpeechMono());
```

**사용 사례 34.** 음성 또는 음악에 최적화하도록 콘텐츠 공유 오디오의 오디오 품질을 설정합니다:

모노 채널로 풀밴드 음악에 대한 콘텐츠 공유 오디오의 오디오 비트레이트를 최적화하려면 다음 설정을 사용하세요:

```js
meetingSession.audioVideo.setContentAudioProfile(AudioProfile.fullbandMusicMono());
```

**사용 사례 35.** 스테레오 오디오 송수신

콘텐츠 또는 메인 오디오 입력을 통해 스테레오 채널이 있는 오디오 스트림을 보낼 수 있습니다.

스테레오 채널이 있는 오디오 스트림에 대한 메인 오디오 입력 및 출력을 최적화하려면 다음 설정을 사용하세요:

```js
meetingSession.audioVideo.setAudioProfile(AudioProfile.fullbandMusicStereo());
```

스테레오 채널이 있는 오디오 스트림에 대한 콘텐츠 공유 오디오를 최적화하려면 다음 설정을 사용하세요:

```js
meetingSession.audioVideo.setContentAudioProfile(AudioProfile.fullbandMusicStereo());
```

**사용 사례 36.** 중복 오디오

버전 3.18.2부터 SDK는 패킷 손실을 감지하면 오디오 품질에 미치는 영향을 줄이기 위해 서버로 중복 오디오 데이터를 보내기 시작합니다. 중복 오디오 패킷은 활성 오디오(즉, 음성 또는 음악)가 포함된 패킷에 대해서만 전송됩니다. 이로 인해 감지된 패킷 손실량에 따라 오디오에서 소비하는 대역폭이 일반 양의 최대 3배까지 증가할 수 있습니다. SDK는 5분 동안 패킷 손실을 감지하지 못한 경우 중복 데이터 전송을 자동으로 중지합니다.

이 기능을 사용하려면 콘텐츠 보안 정책의 `worker-src` 지시문 아래에 `blob:`이 있어야 합니다.
이것이 없으면 중복 오디오 데이터를 보낼 수 없습니다.

이 기능은 현재 Firefox에서 지원되지 않습니다.
Safari 16.1 이상에서 중복 오디오를 성공적으로 보낼 수 있었습니다. 15.6.1도 지원을 광고하지만 테스트되지 않았습니다.
Chrome은 M96 버전부터 중복 오디오 지원을 광고합니다.

참석자 오디오에 대해 이 기능을 비활성화하려면 다음을 사용할 수 있습니다:

```js
meetingSession.audioVideo.setAudioProfile(new AudioProfile(null, false));
```

비트레이트 최적화를 사용하고 오디오 중복성을 비활성화하려면 아래 줄을 사용할 수 있습니다.
아래 예에서는 fullbandSpeechMono만 사용하지만 사용 사례에 따라 fullbandMusicMono 및 fullbandMusicStereo를 사용할 수 있습니다.

```js
meetingSession.audioVideo.setAudioProfile(AudioProfile.fullbandSpeechMono(false));
```

콘텐츠 공유 오디오에 대해 이 기능을 비활성화하려면 다음 중 하나를 사용할 수 있습니다:

```js
meetingSession.audioVideo.setContentAudioProfile(new AudioProfile(null, false));
```

비트레이트 최적화를 사용하고 오디오 중복성을 비활성화하려면 아래 줄을 사용할 수 있습니다.
아래 예에서는 fullbandSpeechMono만 사용하지만 사용 사례에 따라 fullbandMusicMono 및 fullbandMusicStereo를 사용할 수 있습니다.

```js
meetingSession.audioVideo.setContentAudioProfile(AudioProfile.fullbandSpeechMono(false));
```

기능을 비활성화하는 옵션이 있지만 향상된 오디오 품질을 위해 활성화된 상태로 유지하는 것이 좋습니다.
비활성화할 수 있는 한 가지 이유는 고객에게 매우 엄격한 대역폭 제한이 있는 경우입니다.

### 메시징 세션 시작

**사용 사례 37.** 이벤트(연결 중, 시작, 중지 및 메시지 수신)를 수신하도록 관찰자를 설정하고 메시징 세션을 시작합니다.

> 참고: `messagingSession.removeObserver(observer)`를 호출하여 관찰자를 제거할 수 있습니다.
> 컴포넌트 기반 아키텍처(예: React, Vue 및 Angular)에서는 컴포넌트가 마운트될 때 관찰자를 추가하고 마운트 해제될 때 제거해야 할 수 있습니다.

```js
const observer = {
  messagingSessionDidStart: () => {
    console.log('Session started');
  },
  messagingSessionDidStartConnecting: reconnecting => {
    if (reconnecting) {
      console.log('Start reconnecting');
    } else {
      console.log('Start connecting');
    }
  },
  messagingSessionDidStop: event => {
    console.log(`Closed: ${event.code} ${event.reason}`);
  },
  messagingSessionDidReceiveMessage: message => {
    console.log(`Receive message type ${message.type}`);
  },
};

messagingSession.addObserver(observer);
await messagingSession.start();
```

### 애플리케이션 메타데이터 제공

Amazon Chime SDK for JavaScript를 사용하면 빌더가 미팅 세션 구성에 애플리케이션 메타데이터를 제공할 수 있습니다. 이 필드는 선택 사항입니다. Amazon Chime은 애플리케이션 메타데이터를 사용하여 미팅 상태 추세를 분석하거나 일반적인 오류를 식별하여 미팅 경험을 개선합니다.

> ⚠️ 개인 식별 정보(PII)를 전달하지 마세요.

**사용 사례 38.** 미팅 세션 구성에 애플리케이션 메타데이터를 제공합니다.

```js
import { MeetingSessionConfiguration, ApplicationMetadata } from 'amazon-chime-sdk-js';

const createMeetingResponse = // CreateMeeting API 응답.
const createAttendeeResponse = // CreateAttendee API 응답.
const meetingSessionConfiguration = new MeetingSessionConfiguration(
  createMeetingResponse,
  createAttendeeResponse
);

meetingSessionConfiguration.applicationMetadata = ApplicationMetadata.create({
  appName: 'AppName',
  appVersion: '1.0.0'
});
```

#### 허용되는 애플리케이션 메타데이터 제약 조건

```js
// appName은 1-32자 사이여야 합니다.
// appName은 다음 정규식을 충족해야 합니다:
// /^[a-zA-Z0-9]+[a-zA-Z0-9_-]*[a-zA-Z0-9]+$/g
appName: string;

// appVersion은 1-32자 사이여야 합니다.
// appVersion은 시맨틱 버전 관리 형식을 따라야 합니다.
// https://semver.org/
appVersion: string;
```

## 고지 사항

이 SDK를 통한 Amazon Voice Focus, 배경 흐림 및 배경 교체 사용에는 최종 사용자가 런타임에 코드를 다운로드하고 실행하는 것이 포함됩니다.

Amazon Voice Focus, 배경 흐림 및 배경 교체 런타임 코드 사용에는 추가 고지 사항이 적용됩니다. 자세한 내용은 [이 Amazon Voice Focus 고지 사항 파일](https://static.sdkassets.chime.aws/workers/NOTICES.txt), [배경 흐림 및 배경 교체 고지 사항 파일](https://static.sdkassets.chime.aws/bgblur/workers/NOTICES.txt) 및 [배경 흐림 2.0 및 배경 교체 2.0 고지 사항 파일](https://static.sdkassets.chime.aws/ml_media_fx/otherassets/NOTICES.txt)을 참조하세요. 귀하는 이 SDK를 통해 Amazon Voice Focus, 배경 흐림 및 배경 교체, 배경 흐림 2.0 및 배경 교체 2.0 런타임 코드를 사용하는 모든 최종 사용자가 이러한 추가 고지 사항을 사용할 수 있도록 하는 데 동의합니다.

[demos 디렉토리](https://github.com/aws/amazon-chime-sdk-js/tree/main/demos)의 브라우저 데모 애플리케이션은 이미지 세그먼테이션을 위해 [TensorFlow.js](https://github.com/tensorflow/tfjs) 및 사전 훈련된 [TensorFlow.js 모델](https://github.com/tensorflow/tfjs-models)을 사용합니다. 이러한 타사 모델을 사용하면 최종 사용자 브라우저가 [jsDelivr](https://www.jsdelivr.com/)에서 런타임에 코드를 다운로드하고 실행하는 것이 포함됩니다. jsDelivr 허용 사용 정책은 이 [링크](https://www.jsdelivr.com/terms/acceptable-use-policy-jsdelivr-net)를 방문하세요.

위에서 참조한 TensorFlow 런타임 코드 사용에는 추가 라이선스 요구 사항이 적용될 수 있습니다. 자세한 내용은 TensorFlow.js의 라이선스 페이지 [여기](https://github.com/tensorflow/tfjs/blob/master/LICENSE) 및 TensorFlow.js 모델 [여기](https://github.com/tensorflow/tfjs-models/blob/master/LICENSE)를 참조하세요.

귀하와 귀하의 최종 사용자는 배경 교체와 함께 사용하기 위해 업로드된 모든 콘텐츠(이미지 포함)에 대한 책임이 있으며, 해당 콘텐츠가 법률을 위반하거나 제3자의 권리를 침해 또는 도용하거나 Amazon과의 계약의 중요한 조건(문서, AWS 서비스 약관 또는 허용 사용 정책 포함)을 위반하지 않도록 해야 합니다.

Amazon Chime SDK for JavaScript를 사용한 라이브 전사는 Amazon Transcribe에 의해 구동됩니다. Amazon Transcribe 사용에는 AWS 기계 학습 및 인공 지능 서비스에 대한 특정 조건을 포함한 [AWS 서비스 약관](https://aws.amazon.com/service-terms/)이 적용됩니다. Amazon Transcribe 및 Amazon Transcribe Medical에 대한 표준 요금이 적용됩니다.

귀하와 귀하의 최종 사용자는 Amazon Chime SDK 미팅 녹화가 전자 통신 녹화에 관한 법률 또는 규정의 적용을 받을 수 있음을 이해합니다. 녹화된 세션 또는 통신의 모든 참가자에게 세션 또는 통신이 녹화되고 있음을 적절하게 알리고 동의를 얻는 것을 포함하여 녹화와 관련된 모든 적용 가능한 법률을 준수하는 것은 귀하와 귀하의 최종 사용자의 책임입니다.

---

Copyright Amazon.com, Inc. or its affiliates. All Rights Reserved.
