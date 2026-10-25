# 안녕하세요, 이재민입니다 👋

### 팀이 같은 기준으로 판단하고 일할 수 있는 구조를 만드는 풀스택 개발자

에이전트가 코드를 대신 쓰는 환경에서도 개발자에게 남는 것은 **판단**이라고 생각합니다.
흩어진 기획을 하나의 기준으로 정리하고, 제 작업 방식을 팀과 AI가 함께 쓸 수 있는 절차로 옮기는 일에 관심이 많습니다.

<p align="left">
  <a href="mailto:dlwoals0850@gmail.com"><img src="https://img.shields.io/badge/Email-dlwoals0850@gmail.com-D14836?style=flat-square&logo=Gmail&logoColor=white"/></a>
</p>

---

## 🧭 대표 프로젝트: CatchU (2026, 팀장)

> 개발자의 GitHub 기록과 본인의 설명을 연결해, 면접에서 개발 경험과 판단을 전달하도록 돕는 서비스
> 저장소는 2026년 11월 공개 예정입니다.

에이전트가 코드를 작성하는 시대에 "개발자가 코드를 썼다"는 사실보다 **어떤 판단을 했는지**가 중요하다고 보고 기획했습니다.
구직자인 저는 제 경험을 GitHub 근거와 함께 보여주고 싶었고, 기술 면접관 인터뷰에서는 "GitHub를 봐야 하지만 시간이 없어 거의 못 본다"는 이야기를 들었습니다. CatchU는 이 두 입장을 잇는 데서 출발했습니다.

**제가 한 일**

- **기획의 공통 기준 정리**: 기획이 크게 바뀐 뒤 이전 문서 때문에 사람과 AI의 판단이 어긋나는 문제를 보고, 문서를 현행 기획으로 통합했습니다. AI-DLC로 intent와 요구사항을 구체화하고, 자료의 역할별로 기준이 되는 위치를 정했습니다.
- **에이전트 작업 체계 설계와 개선**: "내가 이 프로젝트를 한다면 어떻게 할까"를 돌아보고, 이슈와 하위 이슈로 나눠 단위별로 AI와 작업하는 방식을 `AGENTS.md` 지침으로 옮겼습니다. 직접 사용하고 팀원의 사용을 관찰하며, 병목이 보이면 불편한 점을 물어 지침을 고쳤습니다. (PR #141, #190)
- **GitHub 기록 수집과 경험 후보 판별**: 허용한 범위만 읽고 출처와 누락 범위를 남기며, 사용자의 기여를 작업 단위로 묶는 기능을 구현했습니다. (PR #192, #268)
- **REST 개별 조회 → GraphQL 묶음 조회**: 작업 단위로 묶이지 않은 커밋을 하나씩 조회하면 호출 수가 크게 늘 것으로 예상해, 연결 PR 조회를 최대 100개씩 묶는 방식으로 바꿨습니다. 합성 데이터 비교에서 요청 수가 710회에서 217회로 줄었습니다. (PR #273)
- **MVP 범위 판단**: 큐 검증 결과를 검토하며 장애 복구 기능이 MVP의 목표에 비해 과하다고 판단해, 복구 범위를 줄이고 실패 표시·권한·중복 클릭 방지 같은 보호는 남겼습니다.

---

## 📁 이전 프로젝트

| Project | 시기 · 역할 | 제가 한 일 |
| :--- | :--- | :--- |
| [**TheMe**](https://github.com/ljm0850/TheMe) | 2022 · 5인 팀장, 프론트엔드 | 개인·공용 테마 개념을 팀원마다 다르게 이해하던 문제를 Figma 화면·버튼 동작 비교로 합의, 테마 등록 흐름과 이미지 리사이징 구현 |
| [**BEASTA ZOO**](https://github.com/ljm0850/BEASTA-ZOO) | 2022 · 6인, 블록체인 담당 | NFT 발행·조합·거래 계약 구현, 온체인 난수 처리 문제의 한계를 팀과 공유하고 대안 적용 · SSAFY 특화 프로젝트 우수상 |
| [**GOOSE**](https://github.com/ljm0850/Goose) | 2022 · 6인, 프론트엔드 | 스터디 홈페이지·게시판 구현, 동료의 담당 기능을 기준으로 구현 순서와 개념을 설명하며 프론트엔드 작업 지원 |
| [**All Review You**](https://github.com/ljm0850/All-Review-you) | 2022 · 2인 | Django REST API를 함께 보며 공동 작성, Vue 구조 담당 |

당시 프로젝트 회고: [TheMe](https://ljm0850.tistory.com/126) · [BEASTA ZOO](https://ljm0850.tistory.com/123) · [GOOSE](https://ljm0850.tistory.com/122) · [All Review You](https://ljm0850.tistory.com/75)

---

## 🛠 Skills

- **Languages:** Python, TypeScript, JavaScript
- **Frontend:** Vue, React, Next.js
- **Backend:** Django
- **Infra · DevOps:** Docker, AWS (EC2, ECS), Nginx, GitHub Actions
- **AI 협업:** Claude Code, 에이전트 지침 설계(`AGENTS.md`), AI-DLC
- **프로젝트에서 다뤄보는 중:** Valkey/Redis (작업 큐), Solidity (2022)

---

## 📚 학습

- **광주인공지능사관학교 AI 보안 과정** (2026.05~) · [학습 기록](https://github.com/ljm0850/TIL-AI-Security)
  - ECS 배포 중 헬스체크 타임아웃: 컨테이너 내부 응답으로 범위를 좁혀 잘못 연결된 보안그룹을 찾음
  - GitHub Actions CI 구성 후 의도적인 실패로 PR 검사 차단까지 확인
- **SSAFY 7기** (삼성 청년 SW 아카데미)
  - 1학기 성적우수상 (반 3등), 코딩 역량 Certificate 우수 (상위 30% 이내)
  - 알고리즘·CS 스터디 참여

## 🏆 자격 · 알고리즘

- 정보처리기사 · AWS Certified Cloud Practitioner · SQLD
- PCCP Level 4 (Python)

[![Solved.ac Profile](http://mazassumnida.wtf/api/generate_badge?boj=dlwoals0850)](https://solved.ac/dlwoals0850)
