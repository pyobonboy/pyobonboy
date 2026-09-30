<div align="center">

# 한원채

**Full-stack Developer**

Payments · POS Integration · Back-office Systems

결제·POS 연동과 사내 운영 시스템을 만드는 풀스택 개발자입니다.<br>
매장의 결제 단말과 POS 안에서 동작하는 서비스를 설계부터 배포·운영까지 맡아 왔고,<br>
돈과 재고가 걸린 흐름에서는 중복 반영·동시성·외부 API 실패를 먼저 설계합니다.

[![Email](https://img.shields.io/badge/Email-pyobon07%40naver.com-03C75A?style=flat-square&logo=naver&logoColor=white)](mailto:pyobon07@naver.com) [![GitHub](https://img.shields.io/badge/GitHub-pyobonboy-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/pyobonboy)

</div>

## Tech Stack

| 분야 | 기술 |
|---|---|
| Language | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| Frontend | ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![three.js](https://img.shields.io/badge/three.js-000000?style=flat-square&logo=threedotjs&logoColor=white) |
| Backend | ![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) ![Knex.js](https://img.shields.io/badge/Knex.js-D26B38?style=flat-square) |
| Database | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) |
| Testing | ![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white) ![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white) ![Node Test Runner](https://img.shields.io/badge/Node_Test_Runner-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white) |
| Infra · DevOps | ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) ![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black) ![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) |
| Integration | ![Toss Payments](https://img.shields.io/badge/Toss_Payments-0064FF?style=flat-square) ![Toss Place SDK](https://img.shields.io/badge/Toss_Place_SDK-0064FF?style=flat-square) ![Kakao Alimtalk](https://img.shields.io/badge/Kakao_Alimtalk-FFCD00?style=flat-square&logo=kakaotalk&logoColor=black) ![Claude API](https://img.shields.io/badge/Claude_API-191919?style=flat-square&logo=anthropic&logoColor=white) |

## Featured Projects

각 레포의 README에 **문제 → 해결 → 근거 코드 → 검증** 순서로 핵심 기술 과제를 정리했습니다.

<table>
<tr>
<td width="50%" valign="top">

**[merchant-ops-system](https://github.com/pyobonboy/merchant-ops-system)**<br>
가맹점 운영 관리 시스템<br>
`Next.js` `Supabase` · 2인 팀 주 개발

가맹 접수 → 심사 → 설치 → 인터넷 개통 → CS를 한곳에서 처리하는 사내 운영 시스템입니다. 실제 업무에 쓰였습니다.

> 결재 권한 판정 단일화, 재고 중복 차감 방지, PostgREST 1000행 절단 대응

→ [기술 과제 보기](https://github.com/pyobonboy/merchant-ops-system#핵심-기술-과제와-해결)

</td>
<td width="50%" valign="top">

**[franchise-inventory-system](https://github.com/pyobonboy/franchise-inventory-system)**<br>
프랜차이즈 재고·발주 관리<br>
`Express` `Knex` `React` · 1인 개발

POS 매출을 자동 수집해 레시피대로 재고를 차감하고, 본사–가맹점 발주·결제·정산을 관리합니다.

> 폴링·웹훅 중복 반영 방지, 환불 동시성, SQLite·Postgres 이중 방언 CI(테스트 94케이스)

→ [기술 과제 보기](https://github.com/pyobonboy/franchise-inventory-system#핵심-기술-과제와-해결)

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[tire-b2b-commerce](https://github.com/pyobonboy/tire-b2b-commerce)**<br>
타이어 B2B 마켓플레이스<br>
`Next.js` `Prisma` · 1인 개발

주문, 토스페이먼츠 결제, 부분환불, 반품·교환, 판매자 정산까지 다루는 승인제 B2B 오픈마켓입니다.

> 외부 결제 API의 트랜잭션 분리, 부분환불 자동화와 과다환불 방지, 서명 없는 웹훅 검증

→ [기술 과제 보기](https://github.com/pyobonboy/tire-b2b-commerce#핵심-기술-과제와-해결)

</td>
<td width="50%" valign="top">

**[d2c-product-store](https://github.com/pyobonboy/d2c-product-store)**<br>
주방 설비 자사몰(D2C)<br>
`Next.js` `Prisma` `three.js` · 1인 개발

업소용 세제 자동 희석 장치와 소모품을 파는 자사몰로, 토스페이먼츠 결제·부분취소·재고 원장·관리자 화면까지 다룹니다.

> 결제 승인 선점과 토스 재조회, 부분취소 환불액 계산, 취소 잠금과 대사(테스트 299케이스)

→ [기술 과제 보기](https://github.com/pyobonboy/d2c-product-store#핵심-기술-과제와-해결)

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[car-service-queue](https://github.com/pyobonboy/car-service-queue)**<br>
정비 예약·대기열 플러그인<br>
`Express` `Prisma` `Cloud Run` · 1인 개발

매장 결제 단말과 POS 안에서 동작하는 정비 예약·대기 호출·알림톡 시스템으로, GCP Cloud Run에서 운영했습니다.

> 원자적 대기번호와 멱등 접수, 다중 인스턴스 레이트리밋, 전산–POS 연동 경로 전환(테스트 약 200케이스)

→ [기술 과제 보기](https://github.com/pyobonboy/car-service-queue#핵심-기술-과제와-해결)

</td>
<td width="50%" valign="top">

**[academy-billing-lite](https://github.com/pyobonboy/academy-billing-lite)**<br>
학원 수납 관리<br>
`NestJS` `React` `pnpm` · 1인 개발

토스 POS 탭앱 안에서 청구서를 관리하고 대면(POS)·비대면(결제 링크) 결제를 처리합니다.

> 서명 없는 웹훅의 IP 검증과 폴링 대사, 대면결제 실패 복구 큐(테스트 49케이스)

→ [기술 과제 보기](https://github.com/pyobonboy/academy-billing-lite#핵심-기술-과제와-해결)

</td>
</tr>
<tr>
<td colspan="2" valign="top">

**[restaurant-ai-ops](https://github.com/pyobonboy/restaurant-ai-ops)**<br>
외식업 AI 운영 플랫폼(데모)<br>
`Next.js` `Claude API` · 1인 개발

점주는 AI 비서에게 묻고, 본사는 전 매장을 한 화면에서 보는 운영 플랫폼입니다.

> 도구 호출 루프와 규칙 기반 폴백, 근로기준법 가드가 들어간 급여 계산, 민감 필드 암호화

→ [기술 과제 보기](https://github.com/pyobonboy/restaurant-ai-ops#핵심-기술-과제와-해결)

</td>
</tr>
</table>

## 중요하게 보는 것

- **중복 반영은 구조로 막는다.** 조건부 UPDATE의 영향 행 수로 소유권을 먼저 가져가서, 폴링·웹훅·재시도가 겹쳐도 한 번만 반영되게 합니다.

- **외부 결제 API는 트랜잭션 밖에서 부른다.** 먼저 커밋하고 호출하며, 실패하면 사람이 이어받을 수 있는 복구 상태를 남깁니다.

- **웹훅은 받되 그대로 믿지 않는다.** 서명·IP·비밀값으로 확인하고, 원천 API 재조회와 주기적 대사로 교차 검증합니다.

- **결정은 문서로 남긴다.** 기능마다 왜 그렇게 만들었는지, 무엇을 포기했는지를 기록합니다.

## Contact

- Email: [pyobon07@naver.com](mailto:pyobon07@naver.com)
