<div align="center">

# 임강현 | Backend Developer

### 개발할 때가 가장 행복한 개발자

대규모 커머스 데이터를 안정적으로 처리하는 백엔드와 실제 업무에 쓰이는 AI 애플리케이션을 만들고 있습니다.

</div>

## About Me

- **2,000개 이상의 테넌트 DB**로 구성된 멀티테넌트 OMS를 개발·운영하고 있습니다.
- **100만 행 이상의 주요 테이블**과 대량 주문 데이터를 다루며 성능·동시성·데이터 정합성을 함께 고려해 설계합니다.
- 주문·발송 장애가 발생하면 CX팀과 실시간으로 소통하고, DB·로그·Sentry를 분석해 제한된 시간 안에 운영을 복구합니다.
- 멀티 AI 에이전트 오케스트레이션 앱 **AgentParty를 직접 개발**해 6개월 이상 주력 업무 도구로 사용했으며, 사내 발표 후 동료들에게 배포했습니다.

## Highlights

| 영역 | 성과 |
| --- | --- |
| OMS 대량 매칭 | 작업기록 적재를 포함한 1만 건 처리 시간을 **7.5초 → 0.5초**, 약 **93.3% 단축** |
| QA 자동화 | 상품 등록 QA 사례의 소요 시간을 **약 40분 → 7분 이내**로 단축 |
| AgentParty 렌더링 | 스트리밍 중 입력 지연을 **최대 8초 → 0.2초**, **97.5% 단축** |
| AgentParty 저장 | 저장 회차당 전송량을 **22.1MB → 약 1KB**, **99% 감소** |
| AgentParty 메모리 | 5시간 실사용 기준 WSL 평균 RSS를 **5.5GB → 1.4GB**로 감소 |

## Tech Stack

- **Languages** — TypeScript, JavaScript, PHP, C#, Dart
- **Backend** — NestJS, Laravel, Node.js
- **Database** — Microsoft SQL Server, PostgreSQL, Redis
- **Framework** — Unity, Flutter

## Featured Projects

### AgentParty

Claude Code·Codex·Grok·API 모델을 한 앱에서 운용하는 **멀티 AI 에이전트 오케스트레이션 데스크톱·모바일 애플리케이션**입니다.

- 세션 간 메시지 전송과 역할별 에이전트 생성·수명 관리
- 메시지 규칙과 멤버별 송수신 제어
- 시그널링 서버와 WebRTC P2P 기반 모바일 연결
- 6개월 이상 실사용하며 개선하고 동료들에게 배포

[Product](https://agentparty-landing.vercel.app) · [Desktop](https://github.com/JioBani/AgentPartyApp) · [Mobile](https://github.com/JioBani/AgentPartyMobile) · [Server](https://github.com/JioBani/AgentPartyServer)

### Tatica Defence

Unity·C# 기반의 오토배틀러 덱 빌딩 디펜스입니다. 계층형 상태 관리와 컴포지션 기반 상태효과 시스템을 적용해 새로운 행동과 효과를 기존 제어 로직의 변경 없이 확장할 수 있도록 설계했습니다.

[Repository](https://github.com/JioBani/Tatica-Defence)

---

![GitHub activity graph](https://github-readme-activity-graph.vercel.app/graph?username=JioBani&bg_color=ffffff&color=1f2937&line=2563eb&point=2563eb&area=true&area_color=93c5fd&hide_border=true)
