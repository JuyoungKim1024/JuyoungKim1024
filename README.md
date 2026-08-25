<a id="readme-top"></a>

<img width="100%" alt="Kim Juyoung" src="https://capsule-render.vercel.app/api?type=waving&color=0:B8BEC7,48:E8E5DA,100:C9A84C&height=190&section=header&text=Kim%20Juyoung&fontSize=42&fontColor=2F3440&fontAlignY=38&desc=Backend%20Developer&descSize=17&descAlignY=60&descFontColor=4B4F57" />

<div align="center">
  <h3>비즈니스 흐름을 안정적인 서버 구조로 구현하는 백엔드 개발자 김주영입니다.</h3>
  <p>
    API 요청부터 인증과 인가, 트랜잭션과 데이터베이스까지 흐름 전체를 추적합니다.<br/>
    백엔드를 중심으로 설계하되, 프론트엔드까지 직접 연결해 <b>사용자 흐름 전체를 검증</b>할 수 있습니다.
  </p>
  <a href="https://github.com/JuyoungKim1024"><img alt="GitHub JuyoungKim1024" src="https://img.shields.io/badge/GitHub-JuyoungKim1024-181717?style=flat-square&logo=github&logoColor=white" /></a>
</div>

---

## Core Skills

### 1. 백엔드를 중심으로 기능의 끝까지 책임집니다

요구사항을 도메인 규칙으로 구체화하고 계층별 책임을 분리합니다. 필요한 경우 화면까지 수정해 API 동작을 끝까지 검증합니다.

**검증된 경험**

- 역할과 리소스 상태를 반영한 접근 권한 설계
- 비회원에서 회원으로 전환되는 인증 수명주기와 데이터 정합성 처리
- API 설계부터 화면 상태 반영까지 기능 연결

### 2. 실시간 기능을 데이터 일관성 관점에서 다룹니다

연결뿐 아니라 인증, 구독 시점, 중복 이벤트와 권한까지 설계합니다. 여러 클라이언트가 같은 상태를 보도록 보장합니다.

**검증된 경험**

- STOMP 연결 인증과 메시지 권한 검증
- 이벤트 누락, 중복 반영과 재연결 상태 안정화
- 댓글, 투표, 작업 상태, 접속 현황과 집계 데이터 실시간 동기화

### 3. 보안을 설정이 아닌 서비스 흐름으로 검증합니다

Spring Security와 서비스 계층에서 역할과 소유권을 검증합니다. REST API, 쿠키, WebSocket의 보안 경계를 함께 점검합니다.

**검증된 경험**

- 여러 계층에 분산된 인가 로직을 서비스 계층으로 일원화
- 쿠키 인증 Origin 검증과 WebSocket 메시지 권한 강화
- 내부 예외 노출, 보안 헤더, 운영 엔드포인트 공개 범위 보완

### 4. 측정 결과를 근거로 성능을 개선합니다

k6로 부하를 재현하고 Grafana에서 API, DB, CPU와 GC 지표를 함께 분석합니다. 측정 결과로 병목 원인을 찾습니다.

**검증된 경험**

- 최대 1,000 VU의 실제 사용자 흐름 기반 부하 테스트 구성
- HikariCP 포화 구간 식별 및 환경별 풀 설정 개선
- N+1과 반복 조회 제거
- DTO Projection, 페이지네이션과 복합 인덱스 적용

## Evidence

| 역량 | 구현 및 검증 경험 |
| --- | --- |
| 실시간 시스템 | [다중 클라이언트 상태 동기화와 연결 인증 안정화](https://github.com/prgrms-aibe-devcourse/AIBE6_FinalProject_Team01/commit/9f0eb87) |
| 인증과 인가 | [분산된 리소스 접근 검사를 서비스 계층으로 일원화](https://github.com/prgrms-aibe-devcourse/AIBE6_FinalProject_Team01/commit/217d804) |
| WebSocket 보안 | [메시지 발행 시 사용자와 리소스 권한 검증 강화](https://github.com/prgrms-aibe-devcourse/AIBE6_FinalProject_Team01/commit/a8a6a16) |
| 데이터베이스 성능 | [쿼리 구조와 DB 커넥션 풀 병목 개선](https://github.com/prgrms-aibe-devcourse/AIBE6_FinalProject_Team01/commit/441949d) |
| 성능 검증 | [실제 사용자 흐름 기반 부하 테스트 시나리오 구축](https://github.com/prgrms-aibe-devcourse/AIBE6_FinalProject_Team01/commit/3820769) |
| 클라이언트 연동 | [API 데이터와 화면 상태를 연결한 기능 구현](https://github.com/prgrms-aibe-devcourse/AIBE6_FinalProject_Team01/commit/364cff1) |

## Tech Stack

### Backend — Main

<p>
  <img alt="Java" src="https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
  <img alt="Spring Boot" src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
  <img alt="Spring Security" src="https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white" />
  <img alt="JPA" src="https://img.shields.io/badge/JPA-59666C?style=flat-square" />
  <img alt="WebSocket" src="https://img.shields.io/badge/STOMP_WebSocket-010101?style=flat-square" />
  <img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
  <img alt="Redis" src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
</p>

### Frontend — Can Build & Integrate

<p>
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
  <img alt="Zustand" src="https://img.shields.io/badge/Zustand-443E38?style=flat-square" />
</p>

### Infra, Performance & Monitoring

<p>
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img alt="AWS" src="https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white" />
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
  <img alt="k6" src="https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white" />
  <img alt="Prometheus" src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" />
  <img alt="Grafana" src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" />
</p>

---

<div align="center">
  <b>문제를 끝까지 추적하고, 수정 결과를 검증하는 개발자가 되겠습니다.</b>
</div>
