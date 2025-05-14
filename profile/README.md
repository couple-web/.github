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

## 👥 팀원 소개

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/Dwsok472/NamanSOLO/issues/1#issue-3062550334" width="120"><br/>
      <b>남재우</b><br/>
      팀장 / 프론트엔드<br/>
      지도 추천 / 관리자 UI / 인트로 UX<br/>
      <i>✨ 코드 즉석 요리사</i>
    </td>
    <td align="center">
      <img src="이미지_URL_2" width="120"><br/>
      <b>유서영</b><br/>
      프론트엔드<br/>
      앨범 UI / DTO 구조 설계 / 기념일 UX<br/>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="이미지_URL_3" width="120"><br/>
      <b>오정재</b><br/>
      백엔드<br/>
      콘솔 디버깅 / TO-DO 기능 / 공식 기념일<br/>
    </td>
    <td align="center">
      <img src="이미지_URL_4" width="120"><br/>
      <b>강준우</b><br/>
      백엔드 / UI디자인<br/>
      웹소켓 알림 / 프로필 / SQL 구성<br/>
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

