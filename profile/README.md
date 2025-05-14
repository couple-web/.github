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

- `2025. 03. 28.` ~ `2025. 05. 09.`

---


## 🔍 코드

1. [Frontend](https://github.com/couple-web/weare-front)
2. [Backend](https://github.com/couple-web/weare-back)

---

## 🖼️ 배경

현대 커플들은 서로의 일상을 기록하고 공유하는 다양한 플랫폼을 사용하고 있지만,  
실제 연인 관계에 최적화된 기록과 추천, 소통 기능은 부족한 실정입니다.  

기존 커플 앱들은 단순한 다이어리 기능에 그치는 경우가 많아  
더 감성적이고, 더 실시간적인 기능을 원하던 사용자의 니즈를 발견했습니다.

이에 저희는 **연인만을 위한 감성적 공간**을 제공하고자  
기록, 추천, 소통을 한데 모은 "AI 기반 커플 플랫폼" WE ARE를 기획하게 되었습니다.

---

## 📊 개요

WE ARE는 단순한 커플 다이어리나 메신저를 넘어서,  
**연인의 기억을 감성적으로 기록하고**,  
**AI 기반으로 데이트 장소를 추천하며**,  
**기념일 및 일정 알림을 실시간으로 받을 수 있는**  
커플을 위한 통합 플랫폼입니다.

또한, 기존 커플 앱의 단조로움을 벗어나  
**사용자의 라이프스타일과 감성에 맞춘 맞춤형 추천과 실시간 알림 서비스**를 통해  
더욱 자연스럽고 실용적인 관계 중심 플랫폼을 지향합니다.

---

## 🧩 핵심 기능

### 📸 커플 기록 앨범
- 연인과의 사진, 메모, 동영상을 감성적으로 기록할 수 있는 앨범형 UI 제공
- 날짜 기반 자동 정렬, 추억 회고에 최적화된 타임라인 구성
- 앨범 콘텐츠에 '좋아요', 댓글, 대댓글 기능 제공
- 댓글/좋아요 발생 시 WebSocket을 통한 실시간 알림 전송
- 일정에 등록된 날짜의 날씨 정보를 자동으로 표시하여 추억을 감각적으로 기록

### 🗓️ 커플 캘린더 & 기념일 관리
- 기념일, 투두 일정 등록 및 수정 가능
- D-Day, 반복 일정 기능 포함
- 일정 3일 전 / 7일 전 기준으로 OpenWeather API 연동, 지역 기반 날씨 알림 자동 발송
- 스케줄러 기반 알림 + WebSocket 실시간 전달로 유저 몰입도 향상
- 월간/주간 캘린더 뷰 제공

### 📍 데이트 장소 추천 시스템 (AI + 위치 기반)
- Hugging Face 모델 기반 사용자 맞춤 데이트 장소 추천
- 카테고리(카페, 전시, 맛집 등) + 지역 필터로 커스터마이징된 장소 탐색 가능
- Kakao Map 연동으로 지도 기반 UI 제공
- 추천 장소 클릭 시, 상세 정보(사진, 설명, 리뷰) 카드로 표시

### 💬 실시간 소통 & 알림
- 피드, 댓글, 기념일 등 주요 사용자 이벤트에 대해 실시간 알림 제공
- WebSocket 기반으로 알림 뱃지 및 모달 UI 출력
- 알림은 개별 사용자에게 비동기 처리되어 개인화된 UX 제공
- 알림 목록에서 읽음 여부 확인 및 알림 삭제 가능

### 🙋‍♂️ 사용자 프로필 & 커플 인증
- 닉네임, 프로필 사진, 자기소개 수정 기능
- 커플 연결 요청 및 수락을 통해 관계 형성
- 마이페이지에서 내가 작성한 콘텐츠, 댓글, 일정, 장소 기록 모아보기 제공

### 🧑‍💻 관리자 기능
- 관리자 전용 대시보드 제공 (통계, 신고 콘텐츠 관리)
- 차트.js 기반 유저 수, 콘텐츠 활동량, 인기 장소 등의 시각화
- 신고된 콘텐츠는 관리자 페이지에서 직접 확인 및 삭제 처리 가능

---

## 🛠️ 주요 기술

### 1. Frontend
- React
- JavaScript (ES6+)
- Zustand (전역 상태 관리)
- Styled-components
- React Router
- Axios
- WebSocket (실시간 알림)
- Visual Studio Code

### 2. Backend
- Java
- Spring Boot
- Spring Security (JWT 인증)
- JPA (Hibernate)
- MySQL
- WebSocket (STOMP 기반 실시간 처리)
- Scheduler (@Scheduled 기반 예약 작업)
- Gradle
- IntelliJ IDEA

### 3. Storage & Infra
- MySQL (관계형 데이터베이스)
- AWS EC2 (서버 인프라)
- Nginx (정적 자원 라우팅)
- Jenkins (CI/CD 파이프라인 자동화)
- GitHub Actions (자동화 빌드/테스트)

### 4. External API & AI
- Google Map API (지도 기반 장소 표시)
- OpenWeather API (지역 기반 날씨 정보)
- Hugging Face (감성 기반 장소 추천 AI 모델)
- Naver 검색 API (장소 키워드 보강)

### 5. 협업 & 개발 도구
- GitHub (형상 관리 / 협업)
- Notion (회의록, 기획 정리)
- Figma (UI 디자인 협업)
- ERDCloud (DB 설계 시각화)


---

## 📄 산출물

1. [기능 명세서 (엑셀)](https://github.com/Dwsok472/NAMANSOLOJAVA/blob/main/%EA%B8%B0%EB%8A%A5%EB%AA%85%EC%84%B8%EC%84%9C.xlsx)
2. [API 명세서 (PDF)](https://github.com/Dwsok472/NamanSOLO/blob/main/api%EB%AA%85%EC%84%B8%EC%84%9C.pdf)
3. [와이어프레임 (Figma)](https://www.figma.com/design/KNSEuzmYAAMkwDF5MlgTV8/Untitled?node-id=0-1&t=ZF9OZGYEJrHVd5QG-1)
4. [ER 다이어그램 (이미지)](https://raw.githubusercontent.com/couple-web/.github/main/ERD.png)
5. [컴포넌트 명세서 (Figma)](https://www.figma.com/design/iNDzBBagw3jkQKrJD69gVv/%EB%82%98%EB%A7%8C%EC%86%94%EB%A1%9C%ED%8C%8)

---

## 📁 프로젝트 구조

### 1. Frontend

```
NAMANSOLO
├── public
│   └── vite.svg
├── src
│   ├── assets
│   ├── components
│   │   ├── Admin
│   │   ├── Album
│   │   ├── api
│   │   ├── Button
│   │   ├── ChatBot
│   │   ├── FindIdAndPwd
│   │   ├── img
│   │   ├── Login
│   │   ├── MainPage
│   │   ├── Map
│   │   ├── MapPicker
│   │   ├── MyPage
│   │   ├── Register
│   │   └── WebSocket
│   ├── api.js
│   ├── api1.js
│   ├── api2.js
│   ├── api3.js
│   ├── Event.jsx
│   ├── Footer.jsx
│   ├── Header.jsx
│   ├── Icons.jsx
│   ├── PopUp.jsx
│   ├── SlideMenu.jsx
│   ├── Test.jsx
│   ├── UserAlbumDummy.jsx
│   ├── Websocket.js
│   ├── img
│   ├── App.css
│   ├── App.jsx
│   ├── index.css
│   └── main.js
├── .env
```

### 2. Backend

```
NAMANSOLOJAVA
├── src
│   └── main
│       ├── java
│       │   └── com.dw.NAMANSOLOJAVA
│       │       ├── chat
│       │       ├── Config
│       │       ├── Controller
│       │       ├── DTO
│       │       ├── enums
│       │       ├── Exception
│       │       ├── jwt
│       │       ├── model
│       │       ├── Repository
│       │       ├── Service
│       │       └── NAMANSOLOJAVAApplication
│       └── resources
│           ├── application.properties
│           └── data.sql
├── uploads
├── var
│   ├── upload
│   └── uploads
├── rest api 명세서.xlsx
├── pom.xml
├── .env
├── .gitignore

```

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

## 🖥 화면

### 1. 인트로 애니메이션

인트로 페이지 진입 시, 텍스트가 등장하며  
로고로 자연스럽게 전환되는 감성 연출이 포함되어 있습니다.

![인트로 애니메이션](https://private-user-images.githubusercontent.com/185031810/443730621-0360c959-e978-403b-b9b4-543613db8dc3.gif?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDcyMzY1MDUsIm5iZiI6MTc0NzIzNjIwNSwicGF0aCI6Ii8xODUwMzE4MTAvNDQzNzMwNjIxLTAzNjBjOTU5LWU5NzgtNDAzYi1iOWI0LTU0MzYxM2RiOGRjMy5naWY_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNTE0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDUxNFQxNTIzMjVaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0xMDFmNGQxNjZlOTI1MGZhMDI4YmE0MzE2Y2QzNzdmNzdmNjMyNWFiNmRkMWEzYjFlYTM2NmU0MmI3MGFhMzJjJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.ruyd1cVJyyBQp5RvsWZCHkI7TU7Fmru85ZB_SpXGLnE)


> 인트로 페이지 진입 시, 텍스트가 등장하며 로고로 자연스럽게 전환되는 감성 연출이 포함되어 있습니다.


### 2. 메인 페이지

<img src="https://private-user-images.githubusercontent.com/185031810/443735881-e2ce8965-7ea4-403d-bb2d-d7e7168e6bd0.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDcyMzcyODEsIm5iZiI6MTc0NzIzNjk4MSwicGF0aCI6Ii8xODUwMzE4MTAvNDQzNzM1ODgxLWUyY2U4OTY1LTdlYTQtNDAzZC1iYjJkLWQ3ZTcxNjhlNmJkMC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNTE0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDUxNFQxNTM2MjFaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT02ZDJjMGU2OTkzYWFiMTQxNjJiODIzMDYzM2RjZDIzNmNiMWRkYzAxZWQwYjQ3OGQ1OWVlODM2MmJlMjA0MTg0JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.c4rfpyyxcgvPKukKB6_MINy3ZD3DVBQnXiBB5D24MXk" width="600" height="700"><br/>

인트로가 종료되면 감성적인 무드의 메인 페이지가 자연스럽게 등장합니다.  
페이지 구성은 사용자 경험 중심으로 설계되어, 시각적 연출과 동선 흐름이 연결되도록 설계되어 있습니다.

#### 감성 문구 + CTA 버튼

- 메인 상단에는 사이트의 감성을 담은 문구와 함께  
  주요 기능으로 향하는 CTA 버튼이 배치되어 있습니다.
- 각 버튼은 문구의 의미와 기능에 맞춰 **정확한 페이지로 연결**됩니다.

#### 앨범 섹션 (책장 넘기기 UX)

- 다음 섹션에서는 **좌우 넘김 UI**를 활용해  
  마치 책장을 넘기듯 앨범을 탐색할 수 있습니다.
- 로그인 여부에 따라 '내 앨범' 또는 '전체 앨범'으로 라우팅이 분기되어  
  사용자 맞춤형 동선을 제공합니다.

#### 로티 애니메이션 + 슬라이드 구성

- 이어지는 섹션에서는 **로티 애니메이션**과 함께  
  슬라이드마다 텍스트와 모션이 동기화되어 등장합니다.
- 사이트의 핵심 기능들을 시각적 몰입과 함께 **자연스럽게 전달**합니다.

#### 기능 카드 (버블 애니메이션)

- 마지막 섹션은 **버블 카드 형식**으로 구성되어 있으며,  
  각 카드에는 시간차 애니메이션이 적용되어 **입체감 있는 연출**을 제공합니다.
- 모든 카드는 주요 기능 페이지와 연결되어  
  **사용자 접근성과 탐색 효율을 극대화**합니다.

  
### 3. 전체 앨범 페이지

<table>
  <tr>
    <td align="center" width="50%">
      <img src="https://private-user-images.githubusercontent.com/185031810/443741373-4e1a76ea-34dc-4ca6-8e71-c4f960f6eb3d.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDcyMzgwMjksIm5iZiI6MTc0NzIzNzcyOSwicGF0aCI6Ii8xODUwMzE4MTAvNDQzNzQxMzczLTRlMWE3NmVhLTM0ZGMtNGNhNi04ZTcxLWM0Zjk2MGY2ZWIzZC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNTE0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDUxNFQxNTQ4NDlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1kYTZkNDczYzQwNGU1YzE2OWEwODM5MWU2MzRiZTI4MDdiZDQwMzIxOThjZmY4MTVlMDdlM2Q1NWVhMGI4ZDE4JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.SfEF3ZS97ZUlGoPTdVgBcMkMFwGFvnlYDk5Iv-ldZOk" width="100%"><br/>
      <b>📂 전체 앨범 목록</b><br/>
    </td>
    <td align="center" width="50%">
      <img src="https://private-user-images.githubusercontent.com/185031810/443757369-ba521b41-f132-4a8f-9e33-3b6c6e231c12.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDcyNDA2NjksIm5iZiI6MTc0NzI0MDM2OSwicGF0aCI6Ii8xODUwMzE4MTAvNDQzNzU3MzY5LWJhNTIxYjQxLWYxMzItNGE4Zi05ZTMzLTNiNmM2ZTIzMWMxMi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNTE0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDUxNFQxNjMyNDlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1hYjU0YzIxYzUzYTRjM2UyNDUwNzljNTg5NGFjN2Y0MmQwZWE3ZGRhODE5Njc0MTZjYmQ5YWRmZjhkOTZjMzNhJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.FFRpXTAgji1dugMU5k_iHy9jPiCdQZ369gxKovKei7E" width="100%"><br/>
      <b>📸 앨범 상세 미리보기</b><br/>
    </td>
  </tr>
</table>

> 전체 앨범은 방문자가 쉽게 다양한 추억을 탐색할 수 있도록 구성되며,  
> 감성적인 인터페이스와 반응형 레이아웃을 통해 몰입감을 제공합니다.


---

### 4. 추천 여행 페이지

사용자는 지도에서 원하는 지역을 클릭하여 탐색을 시작할 수 있으며,  
초기 상태에서는 기본 지도와 안내 메시지만 표시됩니다.

<table>
  <tr>
    <td align="center" width="50%">
      <img src="https://private-user-images.githubusercontent.com/185031810/443745576-8b3a48e9-ea2d-4e03-a622-dcd650c39250.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDcyMzg2NzAsIm5iZiI6MTc0NzIzODM3MCwicGF0aCI6Ii8xODUwMzE4MTAvNDQzNzQ1NTc2LThiM2E0OGU5LWVhMmQtNGUwMy1hNjIyLWRjZDY1MGMzOTI1MC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNTE0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDUxNFQxNTU5MzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0zOGQ3ZjE3ODBhMDBmOTk1MTQ1ZjBiYjg1MTM2MjdjYmYzNDA0ZTQ2ZjM4ZDdjNDdjZDVmODAzYzNmOTk4ZjllJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.uYZkWRZcuNCa2cAhS8AXyH-VVb8sCuHmwdTGwil2qMc" width="100%"><br/>
      <b>🗺️ 지역 선택 후 장소 리스트</b><br/>
    </td>
    <td align="center" width="50%">
      <img src="https://private-user-images.githubusercontent.com/185031810/443745575-233bee92-70c7-4512-8f0a-f215cbe0b9b2.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDcyMzg2NzAsIm5iZiI6MTc0NzIzODM3MCwicGF0aCI6Ii8xODUwMzE4MTAvNDQzNzQ1NTc1LTIzM2JlZTkyLTcwYzctNDUxMi04ZjBhLWYyMTVjYmUwYjliMi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNTE0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDUxNFQxNTU5MzBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT03NWMwNjYyM2JjNzg4YmY0NzhkYjM0YzU0MmYzYTM1YTVhZTcxYzdkMzM5ZDI0MGY2ZWQyZGQ1ZjM4NDllMzdmJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.ENOQEujbGLY6uRDyapbRTVukeqO5DY-PPXVZpQBWjQM" width="100%"><br/>
      <b>📌 장소 선택후 상세 모달</b><br/>
    </td>
  </tr>
</table>


#### 장소 리스트 + 카테고리 필터

- 좌측 리스트는 카드 기반 UI로 구성되며,  
  각 카드에는 장소명 / 썸네일 이미지 / 주소가 표시됩니다.
- 상단에는 ‘맛집’, ‘호텔’, ‘포토존’ 등의 필터 버튼이 있어  
  클릭 시 선택한 카테고리 기준으로 리스트가 필터링됩니다.
- 장소 수가 많을 경우를 대비해 **6개 단위 페이징** 처리되며,  
  '이전', '다음' 버튼을 통해 간편하게 탐색 가능합니다.


#### 장소 상세 모달 + 관리자 권한 제어

- 각 카드를 클릭하면 모달이 열리며,  
  상세 설명 / 주소 / 이미지 슬라이더 등을 확인할 수 있습니다.
- **관리자 권한**이 있을 경우,  
  해당 모달 내에서 **수정/삭제 버튼**이 함께 노출됩니다.
- 권한은 `Spring Security`를 활용한 **Role 기반 접근 제어**로 처리했습니다.


#### 지도 보기 기능 (Google Maps API)

- 모달 하단의 ‘지도 보기’ 버튼 클릭 시  
  **구글 맵이 연동된 실제 위치 뷰**로 이동합니다.
- UX 측면에서 **지도 중심 포커싱** 애니메이션을 적용하여  
  부드럽게 사용자의 시선을 유도합니다.


> 본 페이지는  
> `지역 선택 → 장소 탐색 → 상세 보기 → 지도 확인`까지  
> **한 흐름으로 자연스럽게 연결되는 사용자 경험**을 제공하며,  
> 서버 안정성과 조건부 렌더링을 통해 **동적인 구성과 응답성**을 최적화하였습니다.

### 5. 마이페이지 & 캘린더 기능

사용자 프로필을 클릭하면 마이페이지로 이동되며,  
여기서는 커플의 기념일, 데이트 일정, 앨범, 팔로우 기능을 한 곳에서 확인하고 관리할 수 있습니다.

<!-- 첫 줄: 팔로우 / 앨범 -->
<table>
  <tr>
    <td align="center" width="50%">
      <img src="https://private-user-images.githubusercontent.com/185031810/443749946-7ad82eda-a486-45c2-86af-b761ce598bfd.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDcyMzk4MzAsIm5iZiI6MTc0NzIzOTUzMCwicGF0aCI6Ii8xODUwMzE4MTAvNDQzNzQ5OTQ2LTdhZDgyZWRhLWE0ODYtNDVjMi04NmFmLWI3NjFjZTU5OGJmZC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNTE0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDUxNFQxNjE4NTBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1mNzE5YmQyMjQzOWFhMjcxZWJhZGU5OWY5ZmFhYTk0Zjc3NzE4ZmE4NTUyZjljYWM3YjkyN2I5NDUwZTU3NDRmJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.PX_6UGcAqPGdzkR-Nyd6jTsYJw5-YjfNcdn0I8edUng" width="100%"><br/>
      <b>👥 팔로우 / 팔로잉</b><br/>
      유저 간 팔로우/앨범 구독 기능<br/>
      팔로우 요청 수락 및 취소 가능
    </td>
    <td align="center" width="50%">
      <img src="https://private-user-images.githubusercontent.com/185031810/443749948-20ceaf62-194b-4991-a334-c93f35890e5b.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDcyMzk4MzAsIm5iZiI6MTc0NzIzOTUzMCwicGF0aCI6Ii8xODUwMzE4MTAvNDQzNzQ5OTQ4LTIwY2VhZjYyLTE5NGItNDk5MS1hMzM0LWM5M2YzNTg5MGU1Yi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNTE0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDUxNFQxNjE4NTBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1hMjRjMWIzMzllZWYyMWUyZjVlYjFkMzhkZTM3OGZkN2ZmY2QyZjgwNWRkNjJjYzVmOTkzZDUyNWY4NGE2MWE1JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.QgRqyq0hHLNncUiOruv2_JO-RZYs3KZcxKpOWFeV8BU" width="100%"><br/>
      <b>📸 마 앨범 뷰</b><br/>
      카드형 레이아웃, 최신순 / 좋아요순 / 댓글순 필터
    </td>
  </tr>
</table>

<!-- 두 번째 줄: 데이트 추가 / 기념일 보기 -->
<table>
  <tr>
    <td align="center" width="50%">
      <img src="https://private-user-images.githubusercontent.com/185031810/443749945-1237fbe3-937b-41f7-9176-eb17e3306300.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDcyMzk4MzAsIm5iZiI6MTc0NzIzOTUzMCwicGF0aCI6Ii8xODUwMzE4MTAvNDQzNzQ5OTQ1LTEyMzdmYmUzLTkzN2ItNDFmNy05MTc2LWViMTdlMzMwNjMwMC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNTE0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDUxNFQxNjE4NTBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0wNmFjOGQyMGQ2NmY2NTFkNjFjM2NiMDc5MmNiMjE0MTc1MDAxZGEzY2QyMzNlNzkzMWQxNTYwNDEyYjg1ODRmJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.w5VYlglAjs9BXu2NlZ9uBOuXf-B4Z2wfeDJVI1lZ5VA" width="100%"><br/>
      <b>🗓️ 데이트 일정 추가</b><br/>
      기간형 일정 + 설명, 날짜, 색상 라벨, 사진 첨부
    </td>
    <td align="center" width="50%">
      <img src="https://private-user-images.githubusercontent.com/185031810/443749947-7af6e69b-30d5-4e71-adfb-f0318ae9dbff.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDcyMzk4MzAsIm5iZiI6MTc0NzIzOTUzMCwicGF0aCI6Ii8xODUwMzE4MTAvNDQzNzQ5OTQ3LTdhZjZlNjliLTMwZDUtNGU3MS1hZGZiLWYwMzE4YWU5ZGJmZi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNTE0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDUxNFQxNjE4NTBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT03NjllODYzMTc0M2MzNDA4NTViNjMxNjhhMjg5ZjFiMDY0NjhlYWFhNjFlMmZmMjQwMDBhN2ZmMjU2OGY5ZDlmJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.AyETv5GROvkvVzWAGHOJUUBq0OYkyvPz3dZ7kk0Qzq0" width="100%"><br/>
      <b>🎉 기념일 달력 보기</b><br/>
      개인 / 공식 기념일 구분<br/>
      D-Day 자동 계산 및 색상 분류
    </td>
  </tr>
</table>

#### 캘린더 기능 상세 설명

- 기념일은 직접 등록할 수 있으며 날짜/내용/색상을 지정 가능  
- 등록된 일정은 달력과 우측 '기념일란'에 함께 표시  
- 기념일 중 일부는 '공식 기념일'로 읽기 전용으로만 표시됨

#### 일정 추가/수정/삭제

- 데이트 일정은 기간형 일정으로, 시작일~종료일 범위를 선택  
- 설명 입력 및 사진 첨부 가능 (삭제도 가능)  
- 종료일이 시작일보다 앞서면 경고창 발생
- 등록된 일정은 수정, 삭제 모두 가능하며 `전체보기`에서 한 번에 관리 가능

#### 동선과 UX 고려

- 헤더의 유저 프로필 클릭 → 마이페이지 접근  
- 일정 → 상세 → 전체 보기 → 다시 기념일/데이트로 돌아가기까지  
  흐름이 자연스럽게 이어지도록 설계됨

### 6. 선물 추천 & 실시간 알림 & AI 챗봇

실시간 사용자 반응과 맞춤형 편의를 제공하기 위해  
선물 추천 페이지에 다음과 같은 기능들을 통합 구현하였습니다.

<table>
  <tr>
    <td align="center" width="33%">
      <img src="https://private-user-images.githubusercontent.com/185031810/443754185-98e6bb87-15c5-45f3-b99d-99ddd0473b3a.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDcyNDAxMDgsIm5iZiI6MTc0NzIzOTgwOCwicGF0aCI6Ii8xODUwMzE4MTAvNDQzNzU0MTg1LTk4ZTZiYjg3LTE1YzUtNDVmMy1iOTlkLTk5ZGRkMDQ3M2IzYS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNTE0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDUxNFQxNjIzMjhaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1mMmU3OWRiOTNkM2NlMjMzMTA1NTYwYmIwMjVmYTMyYjY0MGNhZTExMTA1OTQxOTZiOWRiNWFhOTliMWYzODA3JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.28lWAQD-f98IIuy6-Ep826geYDs5Pdntj_SkmG0NO_w" width="100%"><br/>
      <b>🎁 선물 랭킹 TOP10</b><br/>
      - 네이버 쇼핑 OpenAPI를 사용하여<br/>
      - 최신 인기 선물을 실시간으로 보여줍니다<br/>
      - 성별별 추천 기능 (여성/남성 필터)
    </td>
    <td align="center" width="33%">
      <img src="https://private-user-images.githubusercontent.com/185031810/443754181-c3354f3f-e189-4f83-84b6-ee143451cd9c.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDcyNDAxMDgsIm5iZiI6MTc0NzIzOTgwOCwicGF0aCI6Ii8xODUwMzE4MTAvNDQzNzU0MTgxLWMzMzU0ZjNmLWUxODktNGY4My04NGI2LWVlMTQzNDUxY2Q5Yy5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNTE0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDUxNFQxNjIzMjhaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT03YjgzZmIzZjFkZjQyMmUyNDE5MmQ3OGNmNmFhN2VlMDI3ZWU3Y2I5YjQzNzBlYTRhMDMyODAwNWU1Njk4NDE4JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.uKLTMcNY-dSkbPqvcFyWgLD4-Js5ujQpl6Hr-vpUfPY" width="100%"><br/>
      <b>🔔 실시간 알림</b><br/>
      - WebSocket 기반 실시간 알림 구현<br/>
      - 댓글/좋아요/팔로우/날씨까지 하나로 통합<br/>
      - OpenWeather API로 날씨 정보도 함께 표시
    </td>
    <td align="center" width="33%">
      <img src="https://private-user-images.githubusercontent.com/185031810/443754179-7b3fb23f-5e4e-4bbc-b44b-b4af6931d413.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDcyNDAxMDgsIm5iZiI6MTc0NzIzOTgwOCwicGF0aCI6Ii8xODUwMzE4MTAvNDQzNzU0MTc5LTdiM2ZiMjNmLTVlNGUtNGJiYy1iNDRiLWI0YWY2OTMxZDQxMy5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNTE0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDUxNFQxNjIzMjhaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT03YjRkZDkwZDVkNjVjNzc0ODgwM2Y1YTYxNjdlMzYwNzJiYjQ1MGI3ZDk5ZTZhNzQ0NDVjYmNmMDhmMDRjMmI5JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.ESDThYVgo1cCSlXilMrY7RxeK8e3nsyzHyJ2q6fMp2U" width="100%"><br/>
      <b>🤖 AI 챗봇</b><br/>
      - HuggingFace AI API 기반 챗봇 연동<br/>
      - "데이트 장소 추천" 등 실시간 대화 가능<br/>
      - 직관적이고 친근한 대화 UX 제공
    </td>
  </tr>
</table>


---

## 👥 팀원 소개

<table>
  <tr>
    <td align="center" width="180px">
      <img src="https://private-user-images.githubusercontent.com/185031810/443603814-54f6794b-d7c7-4cac-ab86-020606a99152.jpg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDcyMTczNDUsIm5iZiI6MTc0NzIxNzA0NSwicGF0aCI6Ii8xODUwMzE4MTAvNDQzNjAzODE0LTU0ZjY3OTRiLWQ3YzctNGNhYy1hYjg2LTAyMDYwNmE5OTE1Mi5qcGc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNTE0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDUxNFQxMDA0MDVaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0xMTRmZDI4Yzg0OWJiZDNlNjVmMTRlZTM4NzM5NTk3NTViNTAyZjE4NzY0Y2E4MmVjZTFmY2RiMmMxNmYzYmQ2JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.GU54A7iSFqLsSl-Ygf3D738BEsPUE2EIDs-tgtOmZyI" width="120" height="120"><br/>
      <b><a href="https://github.com/Dwsok472" target="_blank">남재우</a></b><br/>
      팀장 / 프론트엔드<br/>
      지도 추천<br/>
      관리자 UI / 인트로 UX
    </td>
    <td align="center" width="180px">
      <img src="이미지_URL_2" width="100" height="120"><br/>
      <b><a href="https://github.com/yooseoyoung" target="_blank">유서영</a></b><br/>
      프론트엔드<br/>
      앨범 UI / DTO 설계<br/>
      기념일 UX
    </td>
    <td align="center" width="180px">
      <img src="이미지_URL_3" width="100" height="120"><br/>
      <b>오정재</b><br/>
      백엔드<br/>
      콘솔 디버깅<br/>
      TO-DO / 기념일 기능
    </td>
    <td align="center" width="180px">
      <img src="이미지_URL_4" width="100" height="120"><br/>
      <b>강준우</b><br/>
      백엔드 / UI 디자인<br/>
      웹소켓 알림 / 프로필<br/>
      SQL 구성
    </td>
  </tr>
</table>

---

## 💌 마무리 한 줄

> 우리는 단순한 서비스 개발이 아닌,  
> **"사랑을 감성적으로 기억하게 해주는 플랫폼"**을 만들고자 했습니다.

WE ARE는  
✨ **기억 → 추천 → 계획 → 소통** 이라는 흐름 안에서  
커플의 관계가 더 특별해지길 바라는 마음으로 설계되었습니다.

---

<p align="center"><b>기록하고, 추천받고, 추억하는 모든 순간</b><br />우리는 <strong>WE ARE</strong>와 함께합니다.</p>

