<p align="center">
  <img src="https://user-images.githubusercontent.com/your-logo-image.png" width="180" />
</p>

<h1 align="center">💑 WE ARE</h1>
<div align="center">
  
  <!-- 🧑‍💻 Front-End -->
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black" />
  
  <br/>

  <!-- ⚙️ Back-End -->
  <img src="https://img.shields.io/badge/Java-007396?style=flat&logo=java&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat&logo=spring&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Swagger-85EA2D?style=flat&logo=swagger&logoColor=black" />
  
  <br/>

  <!-- 🔧 CI/CD & Tools -->
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white" />
  <img src="https://img.shields.io/badge/IntelliJ IDEA-000000?style=flat&logo=intellij-idea&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/VS Code-007ACC?style=flat&logo=visual-studio-code&logoColor=white" />

</div>

## 📌 목차

- 📅 [기간](#-기간)
- 🔍 [코드](#-코드)
- 🖼️ [배경](#-배경)
- 📊 [개요](#-개요)
- 🏗️ [아키텍처](#-아키텍처)
- 💡 [주요 기능](#-주요-기능)
- 🛠️ [주요 기술](#-주요-기술)
- 🤝 [협업 도구](#-협업-도구)
- 📄 [산출물](#-산출물)
- 🧾 [결과물](#-결과물)
- 📁 [프로젝트 구조](#-프로젝트-구조)
- 🖥️ [화면](#-화면)
- 📽️ [영상](#-영상)
- 👥 [팀원](#-팀원)

---

## 📅 기간  
-- 2025. 03. 28. ~ 2025. 05. 09.

---

<p align="center">
  감성을 기억하는 커플 플랫폼<br />
  기록, 추천, 소통이 어우러진 <strong>AI + 실시간 알림 기반</strong> 커플 웹 서비스
</p>

---

## 🎯 프로젝트 개요

**WE ARE**는 단순한 커플 다이어리나 메신저를 넘어,  
**연인의 기억을 감성적으로 기록하고**,  
**AI 기반으로 데이트 장소를 추천하며**,  
**기념일 및 일정 알림을 실시간으로 받을 수 있는**,  
커플을 위한 종합 플랫폼입니다.

우리는 기존 커플 앱의 단조로운 기능을 넘어서,  
**실제 사용자의 라이프스타일과 감성에 맞는 서비스를 제공**하고자 했습니다.

---

## 🧩 핵심 기능

### 📌 1. 감성 기록 앨범
- 사진 + 문구로 구성된 추억 카드 기반의 앨범 UI
- 책장을 넘기듯 넘기며 추억을 돌아볼 수 있는 UX 설계
- 일정에 따라 자동 정렬 및 필터링 제공

### 📌 2. 커플 일정 관리 캘린더
- 기념일 및 개인 일정 등록 가능
- 3일 전 / 7일 전 자동 날씨 예보 알림
- 지역 기반 날씨를 실시간으로 조회하여 이벤트 최적화

### 📌 3. AI 데이트 장소 추천
- 지역 + 카테고리(맛집, 포토존 등) 기반 추천
- KakaoMap API와 연동된 지도 기반 UI
- Hugging Face AI 모델을 통한 사용자 맞춤형 장소 추천 (감성 필터링 포함)

### 📌 4. 실시간 채팅 및 알림
- WebSocket 기반 실시간 알림 (일정, 날씨, 댓글)
- 메시지, 알림 배지, 알림 리스트 연동
- 사용자별 수신 대상 필터링 처리

### 📌 5. 관리자 기능
- 총 회원 수, 인기 장소, 최근 게시글 수 시각화
- 월별 방문자 수 및 장소 등록 수 차트 시각화 (Chart.js)

---

## 🛠 기술 스택

| 영역 | 사용 기술 |
|------|-----------|
| **Frontend** | React, Zustand, Styled-components, React Router, Axios |
| **Backend** | Spring Boot, Spring Security, JPA, MySQL, JWT, WebSocket, Scheduler |
| **Infra / DevOps** | GitHub Actions, AWS EC2, Nginx, Jenkins |
| **외부 API** | OpenWeather, Kakao Map, Hugging Face, Naver 검색 API |

---

## 📂 프로젝트 저장소 구조

| 저장소 | 설명 | 링크 |
|--------|------|------|
| 🗂️ `project-weare` | 전체 소개 및 문서화용 리포지토리 | [🔗 바로가기](https://github.com/couple-web/project-weare) |
| 💻 `weare-front` | React 기반 프론트엔드 코드 | [🔗 바로가기](https://github.com/couple-web/weare-front) |
| 🔧 `weare-back` | Spring Boot 기반 백엔드 코드 | [🔗 바로가기](https://github.com/couple-web/weare-back) |

---

## 👨‍👩‍👧‍👦 팀원 및 역할

| 이름 | 역할 | 담당 내용 |
|------|------|------------|
| **남재우** | 팀장 / 프론트 | 조직 아키텍처 설계, 지도 기반 장소 추천 구현, 관리자 통계 UI, 인트로 UX |
| **유서영** | 프론트 | 앨범형 UI 설계, 감성 카드 뷰 구현, 일정 캘린더 UX |
| **오정재** | 백엔드 | // |
| **강준우** | 백엔드 | // |

---

## 💬 개발 목표 및 방향성

- 사용자에게 **감성적인 경험**을 제공하면서도,  
  **실용적인 기능** (추천, 일정, 알림)을 통합한 **몰입형 커플 플랫폼** 개발
- 각 컴포넌트의 UX 완성도와 **실제 사용자 입장에서의 흐름 설계**에 집중
- 추억을 ‘기록’하는 데서 그치지 않고,  
  **추천 → 일정화 → 기록화**까지 자연스럽게 이어지는 전체 흐름을 고려함

---

## 🧠 백엔드 기능 처리 흐름 (주요 예시)

### 📅 일정 & 날씨 알림
1. 사용자가 일정(기념일, 투두 등) 등록
2. 스케줄러(@Scheduled)가 3일 전 / 7일 전 기준으로 감지
3. 사용자 지역 기반으로 OpenWeather API 호출
4. 조건 만족 시 → 알림 데이터 생성
5. WebSocket을 통해 실시간 알림 전송 + 알림 리스트 DB 저장

### 📍 장소 추천 기능
1. 사용자 지역 + 카테고리 선택
2. KakaoMap API로 지도 및 마커 표시
3. 선택된 장소를 Hugging Face 기반 추천 알고리즘에 전달
4. 유사 감성의 장소를 필터링하여 결과 반환
5. 프론트에서 카드형 UI로 장소 정보 시각화

### 📊 관리자 대시보드
- 차트.js를 활용해 유저 수, 월별 방문자 수, 장소 등록 수 등을 실시간 그래프로 표현
- 백엔드에서 통계 집계 쿼리 수행 후 JSON 형태로 반환

---

## 🖥 프론트엔드 컴포넌트 구조 요약

| 기능 영역 | 주요 컴포넌트 |
|-----------|----------------|
| 인트로 | `Intro`, `LogoTransition` |
| 장소 추천 | `MapPicker`, `PlaceCard`, `CategoryFilter` |
| 앨범 | `AlbumPage`, `CardItem`, `ImageViewer` |
| 일정 관리 | `Calendar`, `ToDoList`, `WeatherAlarm` |
| 알림 | `AlarmList`, `AlarmItem`, `WebSocketHandler` |
| 관리자 페이지 | `AdminDashboard`, `ChartSection`, `StatBox` |

- Zustand를 활용한 전역 상태 관리
- Styled-components로 페이지별 독립 디자인
- `sessionStorage`를 통한 인증 정보 유지 및 로그인 처리

---

## 💌 마무리 한 줄

> 우리는 단순한 서비스 개발이 아닌,  
> **"사랑을 감성적으로 기억하게 해주는 플랫폼"**을 만들고자 했습니다.

WE ARE는  
✨ **기억 → 추천 → 계획 → 소통** 이라는 흐름 안에서  
커플의 관계가 더 특별해지길 바라는 마음으로 설계되었습니다.

---

<p align="center"><b>기록하고, 추천받고, 추억하는 모든 순간</b><br />우리는 <strong>WE ARE</strong>와 함께합니다.</p>

