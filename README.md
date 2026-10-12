<div align="center">
<img width="800px" src="./Seokho%20Logo.gif"/>

<h2>유석호 · 검증 도구를 만드는 개발자</h2>

<b>버그를 찾는 데서 멈추지 않고, 같은 버그가 다시 못 지나가게 도구로 막습니다.</b><br/>
게임 클라이언트(Unity · C#)를 만들어 본 개발 경험과, 현업에서 직접 만든 검증 · 자동화 도구로<br/>
게임 QA · 테스트 자동화 엔지니어를 지향합니다.

</div>

---

### 🔎 지금 하는 일

- 에듀테크 회사에서 **콘텐츠 개발**을 맡아 학습 콘텐츠(인터랙티브 액티비티)를 TypeScript · PixiJS 로 만들고 있습니다.
- 반복 제작을 자동화하는 **데스크톱 앱을 혼자 설계 · 구현 · 배포**해 실제 제작에 쓰고 있습니다.
  AI(Claude Code)가 코드를 쓰면 **타입 검사가 막고**, 개발 완료 액티비티 857개를 스펙 검사에 다시 넣는 점검으로 **결함 9개**를 찾았습니다.

### 🔍 검증하는 방식

| | |
|---|---|
| **테스트 설계** | 기능 리스크 · 사용 빈도 · 조건 분기로 범위를 정하고, 정상 흐름과 네거티브 케이스를 함께 설계 |
| **재현 가능한 리포트** | 재현 절차와 환경을 남기고, 「플레이 흐름을 깨는가」로 심각도를 판단 |
| **E2E 자동화** | Playwright 로 납품 빌드를 띄워 기기 크기 셋에서 끝까지 플레이, 연타 · 깨진 저장값 · 예전 저장값 같은 경계와 회귀를 테스트로 고정 |
| **회귀를 도구로** | 개발 완료 액티비티 **857개**를 스펙 검사에 다시 넣는 점검(2026-10 기준 통과 802, 결함 9), 완성본을 다시 만들어 글자까지 비교하는 재현 검사 |
| **흔들리는 대상 고정** | AI 응답을 녹음 · 재생해 「AI 가 다르게 답한 것」과 「도구가 망가진 것」을 분리해 측정 |
| **함정 기록** | 개발하며 밟은 함정 99개를 기록해 다음 작업 전에 먼저 읽게 함 |

### 📌 대표 프로젝트

| 프로젝트 | 무엇 | 기술 |
|---|---|---|
| [**activity-forge**](https://github.com/dbtjrgh/activity-forge) | 학습 액티비티 양산 자동화 데스크톱 앱 — AI 가 쓴 코드를 타입 검사가 막고 3회까지 재시도, 완성본 857개 점검으로 결함 9개 발견, figma 화면 해석, 자체 업데이트 배포 | Electron · TypeScript · React · Claude Code |
| [**hospital-social-story**](https://github.com/dbtjrgh/hospital-social-story) | 발달장애인 병원 검사 연습 콘텐츠와 편집기 — Playwright E2E 테스트 115개를 폰 · 태블릿 크기로, 원고 검사기로 금지 표현 차단 | React · Electron · Playwright |
| [**Limbus Company 로비 테스트**](https://broadleaf-cone-10f.notion.site/46ad3026dd6f41819442a1331edf6bee) | v1.102.0 업데이트 로비를 PC 라이브 서버에서 7개 영역 206케이스로 테스트, Pass 193 · Fail 2 · Not Test 11 (2026.04) | QA · TC |
| [**샷건킹 모작 TC**](https://broadleaf-cone-10f.notion.site/46ad3026dd6f41819442a1331edf6bee) | 직접 만든 샷건킹 모작의 로비 · 튜토리얼 · 전투 테스트 케이스 설계와 버그 리포트 (튜토리얼 중 입력 제한 누락 등) | QA · TC |
| [**Shotgun-King**](https://github.com/dbtjrgh/Shotgun-King) | 샷건킹 3D 모작 — 1인 개발 | Unity · C# |
| [**HAUNTED-HOUSE**](https://github.com/dbtjrgh/HAUNTED-HOUSE) | 파스모포비아 모작, 4인 협동 호러 — 팀 프로젝트 | Unity · C# |
| [**The_Light_Brigade**](https://github.com/dbtjrgh/The_Light_Brigade) | VR FPS 로그라이크 모작 — 팀 프로젝트 | Unity VR · C# |
| [**Console-Miniature**](https://github.com/dbtjrgh/Console-Miniature) | C++ 콘솔 미니게임 모음 | C++ |

<h3 align="center">🛠 Tech Stack</h3>
<div align="center">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />&nbsp
  <img src="https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white" />&nbsp
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />&nbsp
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />&nbsp
  <img src="https://img.shields.io/badge/PixiJS-E72264?style=for-the-badge&logoColor=white" />&nbsp
  <br/>
  <img src="https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white" />&nbsp
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white" />&nbsp
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />&nbsp
  <br/>
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white" />&nbsp
  <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white" />&nbsp
  <img src="https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white" />&nbsp
  <img src="https://img.shields.io/badge/Notion-F3F3F3?style=for-the-badge&logo=notion&logoColor=black" />&nbsp
</div>

<div align="center">
<br/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dbtjrgh&layout=compact" />
</div>

<h3 align="center">📫 Contact</h3>
<div align="center">
  <a href="mailto:dbtjrgh0522@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>&nbsp
  <a href="https://broadleaf-cone-10f.notion.site/46ad3026dd6f41819442a1331edf6bee"><img src="https://img.shields.io/badge/Portfolio-Notion-000000?style=for-the-badge&logo=notion&logoColor=white"/></a>&nbsp
  <a href="https://www.instagram.com/dbtjrgh"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/></a>
</div>
