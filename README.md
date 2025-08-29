<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=200&color=ffffff&text=High%20Qualiteam%20%20&fontSize=100&textBg=false&descSize=20&animation=twinkling&fontAlign=50&fontColor=000000&desc=스키%20예약%20웹사이트%20&descAlignY=85&descAlign=50">
<p/>

# 😀 프로젝트 소개
High Qualiteam 사용자가 스키 강습 정보를 손쉽게 찾아보고 예약할 수 있도록 설계된 웹사이트입니다. <br>
이 프로젝트는 1인 개발로, 기획부터 디자인, 프론트엔드, 백엔드, 배포까지 전 과정을 직접 진행하며 완성한 풀스택 프로젝트입니다.

- 프로젝트 기간: 2025.08.11 ~ 2025.08.29
- 배포된 사이트 주소 : [High Qualiteam 웹사이트 바로가기](https://qualiteam.co.kr/)

# 💻 주요 기능
해당 웹사이트는 일반 사용자 페이지와 관리자 페이지로 나뉘어 각 사용자에게 필요한 기능을 제공합니다.<br>

### 👩‍💼 사용자 기능
**강사 및 강습 정보 조회** <br>
스키 강사들의 프로필과 강습 패키지 상품 정보를 실시간으로 조회할 수 있습니다.<br>
<br>**강습 예약 및 확인** <br>
원하는 날짜와 강습 패키지를 선택하여 예약하고, 예약 완료 페이지에서 즉시 정보를 확인할 수 있습니다.<br>
예약이 완료되면, 강사와 예약자에게 예약 완료 메일이 전송됩니다.<br>
<br>**FAQ 조회** <br>
사용자들의 자주 묻는 질문을 모아 제공하여 서비스 이용 편의성을 높였습니다.<br>

### 👨‍💻 관리자 기능
**관리자 로그인** <br>
JWT(JSON Web Token) 인증 방식을 도입하여 관리자 전용 API의 보안을 강화했습니다.<br>
<br>**데이터 효율적 관리** <br>
대시보드를 통해 예약 현황을 한눈에 파악하고, FAQ, 강사, 패키지 등 핵심 데이터를 CRUD (생성, 조회, 수정, 삭제) 형태로 관리할 수 있습니다.<br>
<br>**이미지 파일 업로드** <br>
클라우드 기반의 Cloudinary와 연동하여 강사 프로필 및 패키지 이미지를 효율적이고 안정적으로 저장하고 관리합니다.<br>

### 주요 기능

- **스타일 공유**: 자신의 데일리룩이나 특별한 날의 스타일을 사진과 함께 공유할 수 있습니다.
- **큐레이션**: 다른 사용자의 스타일에 큐레이션을 달고 소통할 수 있습니다.
- **랭킹 시스템**: 인기 있는 스타일을 확인할 수 있습니다.
- **인기 태그 목록 기반 탐색**: 다양한 태그를 통해 원하는 스타일을 쉽게 찾아볼 수 있습니다.
- **마이페이지**: 내가 올린 스타일, 좋아요한 스타일 등 활동 내역과 내 정보를 관리할 수 있습니다.

# ⚙️ 기술 스택

### backend

- **Runtime / Framework**: Node.js / Express.js
- **Database**: Prisma (ORM)
- **Authentication**: JSON Web Token (JWT), Bcrypt
- **Image Handling**: Cloudinary (Storage), Multer (Middleware)
- **API Request Logging**: Morgan
- **Email**: Nodemailer
- **Code Formatting**: Prettier

### Frontend

- **Framework**: React
- **Language**: TypeScript
- **Styling**: CSS Modules
- **State Management**: React Context API
- **Build Tool**: **Vite**
- **HTTP Client**: Axios (API 연동)

### 배포 및 CI/CD 파이프라인

- **CI/CD**: GitHub Actions
- **Hosting**: Oracle Cloud 무료 인스턴스

### 시스템 아키텍처
해당 프로젝트는 클라이언트-서버 아키텍처를 따릅니다. 프론트엔드(React)는 백엔드 API 서버(Node.js)에 요청을 보내고, 백엔드 서버는 MySQL 데이터베이스와 Cloudinary 클라우드 스토리지에 접근하여 필요한 데이터를 처리하고 응답합니다. 관리자 기능은 JWT를 통해 보호된 별도의 API 엔드포인트로 제공됩니다.

