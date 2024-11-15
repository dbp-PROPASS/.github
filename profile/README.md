# 자격증 관리 웹 PROPASS
## 프로젝트 소개
- PROPASS는 자격증 일정을 한 눈에 알아보고, 효율적인 일정 관리를 목적으로 진행된 프로젝트입니다.
- 검색을 통해 자격증의 상세 정보를 확인 할 수 있습니다.
- 사용자가 관심에 두는 자격증과 이미 취득한 자격증을 등록하여 해당 자격증의 일정을 관리할 수 있습니다.
- 커뮤니티 기능을 통해 다른 사용자들과 자격증에 대해 토의 할 수 있습니다.
## 1. 팀원 구성
<table>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/pyqvv"><img src="https://github.com/user-attachments/assets/b7b23029-f456-491a-9ad6-9063ee30060e" width="100px;" alt=""/><br /><sub><b>신서영</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/H8bubble"><img src="https://github.com/user-attachments/assets/8d63ca25-340f-47ba-9595-9f5ea5085e87" width="100px;" alt=""/><br /><sub><b>박현빈</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/kyungeune"><img src="https://github.com/user-attachments/assets/33e9cde7-9bdc-4731-a9a2-340a54a3b82f" width="100px;" alt=""/><br /><sub><b>신경은</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/Ss-HhJin"><img src="https://github.com/user-attachments/assets/d3dbfdf9-1cb3-4ac5-8eeb-cbbd34498444" width="100px;" alt=""/><br /><sub><b>신해진</b></sub></a><br /></td>
     <tr/>
  </tbody>
</table>

## 2. 개발환경
- Front-end :
  <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=white">
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white">
  <img src="https://img.shields.io/badge/css3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white">
- Back-end :
  
- 협업 툴 :
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white">
- 디자인 : <img src="https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white">
## 3. 설계
### 메뉴 구조도
<img src="https://github.com/user-attachments/assets/e9afa5a2-1b22-439d-a33c-735e2ae3856a" alt="Menu structure diagram" width="500"/>

### 화면 흐름도
<img src="https://github.com/user-attachments/assets/3b9292b2-9e0d-4133-839c-42a1a1bbb667" alt="screen flow" width="500"/>

## 4. 개발 기간 및 작업 관리
### 개발 기간
- 전체 개발 기간 : 2024-11-11 ~ 2024-12-??
- UI 구현 : 2024-11-11 ~ 2024-12-??
- 기능 구현 : 2024-11-?? ~ 2024-12-??
### 작업 관리
- 주간회의를 진행하며 프로젝트를 논의하고, 회의 내용을 Notion에 기록했습니다.
## 5. 페이지별 기능
### [Start Menu]
- 사용자가 로그인하지 않았을 때 보여지는 메인 화면입니다.
- 한 눈에 사이트에 대해 파악할 수 있도록 구성했습니다.
<img src="https://github.com/user-attachments/assets/8db22b6d-af69-4c0d-adf6-c4a09a750e92" alt="start-menu" width="500"/>

### [Login Form]
- 기존 회원의 경우 : 이메일과 비밀번호를 입력하여 로그인 가능합니다.
- 기존 회원이 아닌 경우 : 하단의 회원가입 페이지로의 이동을 유도합니다.
<img src="https://github.com/user-attachments/assets/4e7afcbe-3743-4518-b7ae-882426800001" alt="login" width="500"/>

### [SignUp Form]
- 사용자의 계정 생성 절차를 위한 화면입니다.
- 회원가입 시, 관심분야를 선택해 자격증 추천에 도움이 될 수 있도록 합니다.
<img src="https://github.com/user-attachments/assets/0ed49cb1-bcf3-4fbc-be09-3c59aee3fccb" alt="sign-up" width="500"/>

### [Certificate Recommend]
- 사용자 정보 기반으로 맞춤 자격증을 추천해주는 화면입니다.
  - 사용자의 나이대에 맞는 인기 자격증을 제공받을 수 있습니다.
  - 사용자의 관심 분야의 인기 자격증에 대해 한 눈에 알아볼 수 있습니다.
<img src="https://github.com/user-attachments/assets/426f34ae-873f-434c-922c-0dbe340e6ab3" alt="cert-recommend" width="500"/>

### [Certificate List]
- 사용자가 원하는 자격증을 검색하여 관련 정보를 찾아볼 수 있는 기능을 제공합니다.

### [Certificate info]
- 사용자가 검색하여 선택한 자격증의 상세 정보를 제공하는 화면입니다.
- 회차, 응시료, 합격률 등의 정보를 제공하며, 사용자의 관심 자격증으로 등록할 수 있는 기능을 제공합니다.

### [Community]
- 사용자 간 소통을 위한 게시판입니다.
- 카테고리를 선택해 원하는 분야에서 자유롭게 게시글을 작성할 수 있습니다.
- 검색 기능을 통해, 원하는 글들을 모아 볼 수 있습니다.
<img src="https://github.com/user-attachments/assets/7697b95d-d62b-4402-aa01-9b1b75eea6cc" alt="Comunity" width="500"/>

### [Community Post]
- 사용자의 게시글과 그에 대한 댓글을 볼 수 있는 화면입니다.
- 익명을 통해 사용자들간의 자유로운 소통이 가능합니다. 
<img src="https://github.com/user-attachments/assets/1cd0081c-2cac-4e77-87c6-ed45589d8cd8" alt="CommunityPost" width="500"/>

### [My Page]
- 사용자의 개인정보 (이름, 연락처 등)를 수정할 수 있는 화면입니다.
<img src="https://github.com/user-attachments/assets/9865fc2e-d34b-4420-b802-a0621563e704" alt="edit-user" width="500"/>

### [My Certificate]
- 사용자가 취득한 자격증을 관리하는 화면입니다.
- 사용자는 취득한 자격증을 조회 및 삭제 할 수 있습니다.
<img src="https://github.com/user-attachments/assets/6f0d9e3f-b279-4cf6-a14e-f2da09ac58fa" alt="own-certificate" width="500"/>

### [Delete User]
- 회원 탈퇴 기능을 제공합니다.
<img src="https://github.com/user-attachments/assets/7cb86ffd-8651-46c9-9083-699218e4a445" alt="delete-user" width="500"/>

### [Schedule Manage]
- 로그인 후 메인 페이지로 전환되며, 일정 관리 기능을 제공합니다.
- 자신이 즐겨찾기한 자격증의 시험 접수 시작일, 시험 접수 마감일, 시험일, 결과 발표일 등을 제공받을 수 있습니다.
<img src="https://github.com/user-attachments/assets/0fdab313-6fa8-4698-a014-141042c30da3" alt="ScheduleManage" width="500"/>

### [CertificateList]
- 사용자가 검색하여 선택한 자격증의 상세 정보를 제공합니다.
- 회차, 응시료, 합격률 등의 정보를 제공하며, 사용자가 관심 자격증으로 등록할 수 있습니다.
<img src="https://github.com/user-attachments/assets/63797f73-36ba-4351-b3b0-8e2e9042581f" alt="certificateList" width="500"/>

### 6. 트러블슈팅
### 7. 프로젝트 후기
