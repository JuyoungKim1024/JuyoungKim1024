<a id="readme-top"></a>

<img width="100%" alt="Kim Juyoung header" src="https://capsule-render.vercel.app/api?type=waving&color=0:27384F,100:F26B7A&height=220&section=header&text=Kim%20Juyoung&fontSize=46&fontColor=ffffff&fontAlignY=40&animation=fadeIn&desc=사용자의%20흐름과%20운영의%20안정성을%20함께%20설계하는%20개발자&descSize=17&descAlignY=62&descAlign=50&descFontColor=ffffff" />

<div align="center">

  <p>
    <img
      alt="Full-stack developer introduction"
      src="https://readme-typing-svg.demolab.com?font=Pretendard&weight=600&size=22&pause=1200&color=C8596A&center=true&vCenter=true&width=760&lines=Build+the+flow.+Secure+the+experience.;Frontend+to+Backend%2C+Real-time+to+Performance."
    />
  </p>

  <p>
    안녕하세요, <b>프론트엔드의 사용자 경험부터 백엔드의 안정성과 성능까지</b><br/>
    서비스 전체 흐름을 연결해 문제를 해결하는 개발자 <b>김주영</b>입니다.
  </p>

  <p>
    <a href="https://github.com/JuyoungKim1024"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-JuyoungKim1024-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  </p>

</div>

---

## 👋 About Me

기능을 만드는 데서 끝내지 않고, 실제 사용자가 여러 화면과 브라우저에서 같은 상태를 보게 되는지까지 확인합니다. 문제를 발견하면 프론트엔드 상태 관리, API 계약, 인증·인가, 트랜잭션, 데이터베이스 쿼리와 배포 설정을 함께 추적하며 원인을 좁힙니다.

- Next.js와 Spring Boot를 함께 다루는 **풀스택 개발**을 지향합니다.
- 여행방 협업 기능의 **실시간 동기화와 권한 경계**를 안정적으로 설계했습니다.
- 보안, 동시성, 성능처럼 기능 이후에 드러나는 문제를 측정하고 개선하는 데 관심이 많습니다.
- 테스트와 모니터링 결과를 근거로 수정하고, 회귀 오류가 없도록 검증합니다.

```text
사용자 흐름 파악 → 재현 가능한 문제 정의 → 계층별 원인 추적
→ 최소 범위 수정 → 자동화 테스트와 관제 지표로 교차 검증
```

## 🧰 Tech Stack

### Frontend

<p>
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
  <img alt="React" src="https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS_4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
  <img alt="Zustand" src="https://img.shields.io/badge/Zustand-443E38?style=flat-square" />
</p>

### Backend & Data

<p>
  <img alt="Java" src="https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
  <img alt="Spring Boot" src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
  <img alt="Spring Security" src="https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white" />
  <img alt="JPA" src="https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=flat-square" />
  <img alt="WebSocket" src="https://img.shields.io/badge/STOMP_WebSocket-010101?style=flat-square" />
  <img alt="MySQL" src="https://img.shields.io/badge/MySQL_8.4-4479A1?style=flat-square&logo=mysql&logoColor=white" />
  <img alt="Redis" src="https://img.shields.io/badge/Redis_7.4-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img alt="Flyway" src="https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white" />
</p>

### Infra, Test & Monitoring

<p>
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img alt="AWS" src="https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white" />
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
  <img alt="k6" src="https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white" />
  <img alt="Prometheus" src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" />
  <img alt="Grafana" src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" />
</p>

## 🚀 What I Built

### Plamingo — AI 기반 공동 여행 계획 서비스

> 장소 탐색, 투표, 날짜 조율, Day별 동선, 지출 정산과 여행 기록을 하나의 협업 흐름으로 연결한 3인 팀 프로젝트

| 영역 | 주요 기여 |
| --- | --- |
| 실시간 협업 | STOMP WebSocket 기반 장소, 댓글, 투표, 일정, 접속 상태와 지출 정산 동기화 안정화 |
| 인증·인가 | JWT 세션 복구, WebSocket 인증, Origin 검증, 여행방 상태·역할별 권한과 서비스 계층 인가 일원화 |
| 여행 의사결정 | 장소 찬반·A/B 투표, 탈락 이력, 지도 포커스, 날짜 제안과 완료 여행방 상태 처리 |
| 일정·AI | Day 일정 편집, Routes 이동시간, 동선 양끝 장소 추천, OpenAI 재정렬과 폴백 흐름 개선 |
| 관리자·운영 | 관리자 OTP 로그인, 회원 정지, 문의, 외부 API 사용량, 커버 이미지와 감사 로그 구현 |
| 품질·성능 | 보안 헤더와 예외 노출 보완, DB 페이지네이션·쿼리 최적화, k6 1,000 VU 부하 테스트와 Grafana 관제 구성 |

## 🔍 Problem Solving Highlights

### 1. 새로고침 없이 일관된 협업 상태 만들기

장소 등록, 댓글, 투표와 정산 결과가 브라우저마다 다르게 보이던 문제를 프론트엔드 구독 수명주기와 백엔드 STOMP 권한 검증 양쪽에서 추적했습니다. 이벤트 누락과 중복 반영을 분리해 처리하고, 여행방 단위 메시지 권한을 서버에서 검증하도록 보완했습니다.

### 2. 인증과 권한을 기능 흐름 안에서 안정화하기

세션 복구 과정의 불필요한 `401` 응답, 게스트에서 회원으로 전환할 때의 권한 불일치, 완료된 여행방의 기능별 접근 규칙을 정리했습니다. 화면 차단에 의존하지 않고 백엔드 서비스 계층에서 권한을 일관되게 검증했습니다.

### 3. 측정값으로 DB 병목 개선하기

k6 실제 사용자 흐름 시나리오와 Prometheus/Grafana 대시보드를 구성해 HikariCP 커넥션 대기와 API 지연을 함께 관찰했습니다. 반복 조회와 페이지네이션을 개선하고 인덱스와 풀 설정을 환경별로 반영한 뒤 동일한 시나리오로 회귀 검증했습니다.

## 📊 GitHub

<div align="center">
  <img height="165" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=JuyoungKim1024&show_icons=true&hide_border=true&title_color=C8596A&icon_color=F26B7A&text_color=27384F&bg_color=ffffff" />
  <img height="165" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=JuyoungKim1024&layout=compact&hide_border=true&title_color=C8596A&text_color=27384F&bg_color=ffffff" />
</div>

---

<div align="center">
  <b>사용자가 자연스럽게 쓰고, 운영자가 안심할 수 있는 서비스를 만들겠습니다.</b><br/><br/>
  <a href="#readme-top">맨 위로</a>
</div>

