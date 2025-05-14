### 기능하나씩-완성하기 🛠️

자주 사용되는 기능들을 단계적으로 구현하며 학습하고 기록하는 프로젝트! AI를 사용하지 않고,, 구현 목표


### 단계별 구현 로드맵

| 단계 | 주제 | 주요 기능 | 상태관리 | 핵심 기술/라이브러리 |
|------|------|-----------|----------|-----------------------|
| ✅ 1단계 | 로그인 & 인증 | 회원가입/로그인 | useState | Tailwind, SessionStorage |
| ⬜ 2단계 | 게시판 | CRUD / 필터링 | Zustand | Zustand, localStorage |
| ⬜ 3단계 | 메모/태그 기능 | 태그 필터, 즐겨찾기 | Zustand + Immer | debounce, 배열 조작 |
| ⬜ 4단계 | 일정 & 달력 | 날짜 선택/일정 추가 | Redux Toolkit | date-fns, Recoil 비교 |
| ⬜ 5단계 | 알림/타이머 | 시간 기반 알림 | Zustand or RxJS | setTimeout, toastify |
| ⬜ 6단계 | 마이페이지 | 유저 기반 뷰 | Context API | 조건부 렌더링, 파일 업로드 |
| ⬜ 7단계 | 무한스크롤/검색 | 리스트 최적화 | React Query | IntersectionObserver |
| ⬜ 8단계 | 소셜 로그인 | 구글/깃허브 | NextAuth.js | OAuth 이해, 보안 흐름 |
| ⬜ 9단계 | 미디어 기능 | 이미지 업로드 | Zustand | FileReader, drag-n-drop |
| ⬜ 10단계 | 배포 & SEO | Vercel 배포, 메타태그 | 없음 | next-seo, Vercel |

---

### 각 단계별 상세 설명

### 🟢 1단계: 로그인 & 인증
- 기능: 회원가입, 로그인, 로그아웃  
- 저장소: SessionStorage  
- 상태관리: `useState`  
- 기술 포인트: Tailwind UI, 라우터 페이지 전환  
- 👉 검색 키워드: `sessionStorage 로그인`, `Tailwind 버튼 스타일`

---

### 🔵 2단계: 게시판 CRUD
- 기능: 게시글 작성 / 수정 / 삭제, 리스트 보기  
- 상태관리: `Zustand`  
- 저장소: `localStorage`  
- 기술 포인트: Zustand 구조화, 동적 라우팅  
- 👉 검색 키워드: `zustand 배열 관리`, `localStorage로 게시글 저장`

---

### 🟠 3단계: 태그 기반 메모장
- 기능: 메모 생성 + 태그 + 즐겨찾기  
- 상태관리: Zustand + Immer  
- 기술 포인트: 디바운스, 배열 `.some()` 검색  
- 👉 검색 키워드: `debounce 구현`, `zustand immer 연동`

---

### 🟣 4단계: 일정 관리 달력
- 기능: 날짜 선택 + 일정 추가  
- 상태관리: Redux Toolkit  
- 기술 포인트: `date-fns`, `useMemo`  
- 👉 검색 키워드: `date-fns 달력`, `redux toolkit 기본`

---

### 🔴 5단계: 알림 기능
- 기능: 알림 예약, 읽음 표시  
- 상태관리: Zustand 또는 RxJS  
- 기술 포인트: `react-toastify`, `setTimeout`  
- 👉 검색 키워드: `toastify`, `zustand 알림`

---

### 🟡 6단계: 마이페이지 / 프로필
- 기능: 유저 정보, 프로필 편집, 파일 업로드  
- 상태관리: Context API + Zustand  
- 기술 포인트: 조건부 렌더링, `file input`  
- 👉 검색 키워드: `react file input`, `context api vs zustand`

---

### 🟤 7단계: 무한스크롤 / 검색
- 기능: 데이터 최적화 리스트  
- 상태관리: React Query  
- 기술 포인트: IntersectionObserver, query cache  
- 👉 검색 키워드: `react-query infinite scroll`, `IntersectionObserver 구현`

---

### ⚫ 8단계: 소셜 로그인
- 기능: Google / GitHub 로그인  
- 상태관리: NextAuth.js  
- 기술 포인트: OAuth 인증, provider 설정  
- 👉 검색 키워드: `next-auth 구글 로그인`, `깃허브 OAuth`

---

### ⚪ 9단계: 이미지 & 미디어 기능
- 기능: 이미지 업로드, 미리보기  
- 상태관리: Zustand + preview 상태  
- 기술 포인트: `FileReader`, drag-n-drop  
- 👉 검색 키워드: `react drag and drop image`, `FileReader 사용법`

---

### 🌐 10단계: 배포 & SEO
- 기능: Vercel 배포, 메타 태그 설정  
- 상태관리: 없음  
- 기술 포인트: `next-seo`, `robots.txt`, `og:image`  
- 👉 검색 키워드: `vercel 배포`, `next-seo 사용법`

---
