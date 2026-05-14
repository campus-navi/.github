# Campus Navi

대학생이 흩어진 교내 정보를 더 빠르게 찾고, 개인에게 필요한 공지를 놓치지 않도록 돕는 캠퍼스 정보 탐색 서비스입니다.

Campus Navi는 대학 공지, 학사 정보, 관심사 기반 추천 흐름을 하나의 서비스 안에서 제공하여  
사용자가 필요한 정보를 더 빠르게 발견하고 놓치지 않도록 돕는 것을 목표로 합니다.

---

## Quick Links

- 서비스 배포 URL: https://campus-navi.com
- 데모 영상: 링크 추가
- 발표 자료: 링크 추가
- API 문서: 링크 추가
- Figma: 링크 추가

---

## MVP 핵심 시나리오

1. 사용자는 대학 인증 기반으로 회원가입합니다.
2. 홈 화면에서 사용자 정보와 주요 교내 정보 진입점을 확인합니다.
3. 관심사를 설정하여 맞춤 공지 추천 기반을 만듭니다.
4. 교내 정보 목록에서 공지, 학사, 장학, 활동 정보를 탐색합니다.
5. 상세 페이지에서 신청 기간, 마감일, 첨부 자료, 요약 정보를 확인합니다.

---

## 주요 기능

### 회원가입 및 대학 인증

- 대학 선택
- 학교 이메일 인증
- 학과 / 입학년도 / 학년 선택
- 아이디, 비밀번호, 닉네임 검증
- 약관 동의 후 가입 완료

### 홈

- 사용자 정보 조회
- 관심사 설정 유도
- 신규 공지 / 추천 공지 카드 노출
- 교내 정보 진입 흐름 제공

### 교내 정보

- 공식 공지 목록 조회
- 카테고리 필터
- 정렬 및 검색
- 공지 상세 정보 확인
- 신청 기간, 마감일, 첨부 자료 표시

### 관심사 설정

- 관심 키워드 선택
- 관심사 저장 API 연동
- 맞춤 공지 추천 기반 마련

---

## Repositories

| Repository | Description |
|---|---|
| frontend | Campus Navi Web Frontend |
| backend | Campus Navi Backend API |
| ai | AI / RAG service |
| infra | Cloud infrastructure and deployment |
| docs | PRD, API, architecture, sprint records |

---

## Tech Stack

### Frontend

- React
- TypeScript
- Vite
- Tailwind CSS
- TanStack Query
- Zustand

### Backend

- Java 21
- Spring Boot
- PostgreSQL
- Redis
- Flyway
- Swagger / OpenAPI

### Cloud

- AWS
- HTTPS
- CI/CD
- GitHub Actions

### AI

- RAG
- Prompt engineering
- Structured output

---

## Team Roles

| Role | Responsibility |
|---|---|
| PM | 문제 정의, MVP 범위 설정, 발표 자료 구성 |
| Designer | 사용자 흐름 설계, Figma, UI/UX 디자인 |
| Frontend | 화면 구현, 상태 관리, API 연동, 사용자 흐름 구현 |
| Backend | API 구현, DB 설계, 인증 및 비즈니스 로직 |
| Cloud | 배포, HTTPS, CI/CD, 인프라 보안 |
| AI | RAG 구조 설계, 프롬프트 설계, AI 응답 구조화 |

---

## Development Process

- Issue 기반 작업 관리
- Git Flow 기반 브랜치 전략
- Pull Request 기반 코드 리뷰
- 기능 단위 PR 작성
- CI 기반 typecheck / lint / build 검증
- 주차별 스프린트 및 베타 테스트 기록 관리

---

## Deployment & Security

- Production URL: https://campus-navi.com
- HTTPS 적용
- 민감 정보 GitHub 미노출
- DB public direct access 차단
- SSH 접근 제한
- S3 파일 목록 비노출 확인

---

## Roadmap

- RAG 기반 AI 에이전트 고도화
- 교내 정보 추천 정확도 개선
- 커뮤니티 기능 확장
- 지식 스튜디오 기능 도입
- 멘토링 / 과외 매칭 기능 검토
