# 헬스케어 통합 관리 시스템 "시니야 (Seniya)"

**[국비지원] 립테크 디지털 치료제 개발자 양성 과정 (2025.02 - 2025.07)**

<br>

> 고령자를 대상으로 한 맞춤형 건강 관리 및 수업 제공 LMS(학습 관리 시스템)입니다. <br> 사용자의 건강 기록을 체계적으로 관리하고, 전문 트레이너의 수업을 통해 건강한 시니어 라이프를 지원합니다.

<br>

### 🛠️ 기술 스택 (Tech Stack)

| 구분 | 기술 |
| :--- | :--- |
| **Backend** | <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white"> <img src="https://img.shields.io/badge/Apache%20Tomcat-F7DF1E?style=for-the-badge&logo=Apache-Tomcat&logoColor=white"/> |
| **Frontend** | <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"> <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white"> <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> |
| **Database** | <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> |
| **Dependencies**| `Spring Security`, `JWT`, `JPA`, `MyBatis`, `H2 Database`, `Lombok`, `Validation` |
| **Tools** | <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"> <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"> <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white"> <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"> |
| **IDE** | <img src="https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellij-idea&logoColor=white"> <img src="https://img.shields.io/badge/Visual_Studio_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white"> <img src="https://img.shields.io/badge/gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white"/> |

<br>

---

## ✨ 주요 기능 (Features)

### 🔑 공통
- **JWT 기반의 안전한 로그인 및 회원가입**
- **Spring Security를 활용한 사용자 권한별 접근 제어 (관리자, 트레이너, 회원)**
- **RESTful API를 통한 백엔드-프론트엔드 데이터 통신**
- **수업 참여권 결제 시스템**

### 🧑‍💼 관리자 (Admin)
- **수업 개설 및 관리:** 새로운 건강 관리 클래스를 생성, 수정, 삭제합니다.
- **회원 통합 관리:** 모든 회원(트레이너, 일반 회원)의 정보를 조회하고 관리합니다.
- **트레이너 권한 승인:** 트레이너로 활동하고자 하는 회원의 신청을 승인/거절합니다.

### ‍🏋️ 트레이너 (Trainer)
- **프로필 관리:** 자신의 경력, 전문 분야 등 프로필 정보를 생성하고 관리(CRUD)합니다.
- **수업 및 회원 관리:** 자신에게 배정된 수업과 수강생 정보를 조회합니다.
- **문의 및 게시글 관리:** 자신의 수업과 관련된 문의나 게시글에 답변하고 관리합니다.

### 🧓 회원 (Member)
- **수업 조회 및 신청:** 개설된 다양한 건강 관리 수업을 조회하고 원하는 수업을 신청합니다.
- **게시판 활동:** 자유롭게 질문하거나 후기를 남길 수 있는 게시판 및 문의 기능을 사용합니다.
- **인기 트레이너 조회:** 다른 회원들에게 인기 있는 트레이너 프로필을 조회하고 수업을 선택할 수 있습니다.

<br>

---

## ⚙️ 담당 역할 (Tasks & Responsibilities)

| 담당자 | 주요 역할 |
| :---: | :--- |
| <img src="https://avatars.githubusercontent.com/u/198717282?v=4" width="150"> <br> **전창현** <br> <a href="https://github.com/chang0506"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"></a> | <ul><li>RESTful API 설계 및 구현</li><li>데이터베이스 설계 및 구현</li><li>Spring Security 기능 구현</li><li>JWT 인증 구현</li><li>트레이너 관련 기능<ul><li>트레이너 권한 신청 및 조회</li><li>트레이너 권한 승인</li><li>트레이너 프로필 CRUD 기능 구현</li><li>인기 트레이너 조회 기능</li></ul></li><li>문의 관련 CRUD 기능 구현</li></ul> |
| <img src="https://avatars.githubusercontent.com/u/109320988?v=4" width="150"> <br> **문창배** <br> <a href="https://github.com/buzz9248"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"></a>| <ul><li>RESTful API 설계 및 구현</li><li>데이터베이스 설계 및 구현</li><li>Spring Security 기능 구현</li><li>JWT 인증 구현</li><li>메인 페이지<ul><li>오늘의 수업 조회</li><li>트레이너 별 수업 목록 조회</li><li>빠른 검색 기능</li></ul></li><li>관리자 기능<ul><li>사용자 목록 및 수업 관리</li><li>결제 내역 조회</li></ul></li><li>수강권 결제 기능</li></ul> |

<br>

---

## 🚀 시작하기 (Getting Started)

> 💡 이 프로젝트를 로컬 환경에서 실행하는 방법입니다.
>
> ```bash
> # 1. 프로젝트 클론
> git clone [https://github.com/your-username/seniya-lms.git](https://github.com/your-username/seniya-lms.git)
>
> # 2. 백엔드 서버 실행
> # IntelliJ IDEA 또는 다른 IDE에서 Spring Boot 애플리케이션을 실행합니다.
> # application.yml 또는 application.properties에서 DB 및 JWT 설정을 확인해주세요.
>
> # 3. 프론트엔드 서버 실행
> cd frontend
> npm install
> npm run dev
> ```

<br>

This project is licensed under the MIT License.

[![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
