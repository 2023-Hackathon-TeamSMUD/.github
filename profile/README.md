<p align="center">
  <img width="240" alt="온라인메모장 앱아이콘" src="https://github.com/2023-Hackathon-TeamSMUD/.github/assets/56509933/b806f750-80c3-4ce8-9271-87dde4148eb4">
</p>

<p align="center">
  <strong>
    - SockSense 🧦 -
    <br>
    시각장애인을 위한 양말 판별 및
    <br>
    맞춤형 코디 추천 서비스
  </strong>
</p>
<br>



## 🔍 Introduction

### 주제 선정
양말의 짝을 구분하지못해 불편함을 느끼는 시각장애인들의 니즈를 접했습니다. <br>
이에 그들의 일상생활 속 시각 정보 격차를 해소할 수 있는 양말 판별 및 양말 맞춤형 코디 추천 서비스를 개발하게 되었습니다.

### 특징
- 대비되는 색감과 일관성 있는 디자인으로 시각장애인들의 접근성을 높였습니다.
- 페이지별 서비스 코치 마크와 함께 음성 가이드를 제공하여 시각장애인들의 편의성을 도왔습니다.
- 촬영을 통해 양말 구분(짝이 올바른지) 및 양말과 성별에 어울리는 코디를 제공합니다. <br>
(영상 처리를 통한 양말 이미지 분석과 ChatGPT를 활용한 코디 추천)
- 추천받은 코디를 저장하여 원할 때 저장된 코디를 확인할 수 있습니다.
- 시각장애인을 위한 서비스이기에, 회원가입 없이 모바일웹으로 간편하게 이용 가능하도록 하였습니다.
<br><br>



## 📹 Demo

### PC Page

**Memo list**|**View memo**|**Invite friends**
-----|-----|-----
<img src="https://github.com/OnlineMemo/.github/assets/56509933/d662b9b9-4c55-4fbb-8199-b5e6dd222f0e" width="100%">|<img src="https://github.com/OnlineMemo/.github/assets/56509933/35c09de5-7f59-4e06-ab74-d9bcd6f0647e" width="100%">|<img src="https://github.com/OnlineMemo/.github/assets/56509933/2096b659-80ca-4f77-b6b7-7f4c760357e0" width="100%">
메모들 목록을 나열합니다.|메모 내용을 조회합니다.|메모에 친구들을 초대하거나, 함께 새로운 메모를 작성합니다.

### Mobile Page

**Login**|**SignUp**|**Change pw**
-----|-----|-----
<img src="https://github.com/OnlineMemo/.github/assets/56509933/1f5c053b-13e5-4da2-9a4f-3db57e983611" width="100%">|<img src="https://github.com/OnlineMemo/.github/assets/56509933/af5c6b6f-1f31-49ff-a57d-1b6f5a304032" width="100%">|<img src="https://github.com/OnlineMemo/.github/assets/56509933/b2f2b934-dec5-41f2-ba99-b070f12bf512" width="100%">
로그인 합니다.|회원가입 합니다.|계정의 비밀번호를 변경합니다.

**Memo list**|**New memo**|**View memo**
-----|-----|-----
<img src="https://github.com/OnlineMemo/.github/assets/56509933/6e5a4727-56b1-473f-8451-fed8864ae91a" width="100%">|<img src="https://github.com/OnlineMemo/.github/assets/56509933/9101fd58-c90a-48dd-af24-a3693aec1b7d" width="100%">|<img src="https://github.com/OnlineMemo/.github/assets/56509933/7eb239e1-b338-4141-a6e6-745140167b70" width="100%">
메모들 목록을 나열합니다.|새로운 개인 메모를 작성합니다.|메모 내용을 조회합니다.

**Friend list**|**Received list**|**Invite friends**
-----|-----|-----
<img src="https://github.com/OnlineMemo/.github/assets/56509933/981d4884-5faf-488d-9822-339fd866ce5d" width="100%">|<img src="https://github.com/OnlineMemo/.github/assets/56509933/ae8c9f27-2b47-4a9e-99e3-d1a5c8a0eb92" width="100%">|<img src="https://github.com/OnlineMemo/.github/assets/56509933/707a9527-ec8a-4863-8d12-608693bc3e8e" width="100%">
친구들 목록을 나열합니다.|친구요청 수신 목록을 조회합니다.|메모에 친구들을 초대하거나, 함께 새로운 메모를 작성합니다.

**User profile**|**Notice**|**App guide**
-----|-----|-----
<img src="https://github.com/OnlineMemo/.github/assets/56509933/d28b8bb5-55fe-4fcf-8225-5ad557a945e3" width="100%">|<img src="https://github.com/OnlineMemo/.github/assets/56509933/5fc7b037-2e48-4e0c-b0ce-29d89787cd50" width="100%">|<img src="https://github.com/OnlineMemo/.github/assets/56509933/419c769b-71bc-46c1-af13-f4ea16d2f93a" width="100%">
회원정보를 조회합니다.|공지사항 페이지 입니다.|모바일앱 다운로드 안내 페이지 입니다.

<br>



## 💻 Architecture
![socksense_architecture drawio](https://github.com/2023-Hackathon-TeamSMUD/.github/assets/56509933/d23ff707-5c84-4985-8da8-61fbac3b5d2e)
<br><br>



## 💡 Tech Stack
|Frontend|Backend|Deployment|Other|
|:------:|:------:|:------:|:------:|
|<img src="https://img.shields.io/badge/React-61DBFB?style=flat-square&logo=React&logoColor=white"/></a><br><img src="https://img.shields.io/badge/React Query-FF475A?style=flat-square&logo=React Query&logoColor=white"/></a><br><img src="https://img.shields.io/badge/JavaScript-F7DF1F?style=flat-square&logo=JavaScript&logoColor=white"/></a>|<img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat-square&logo=Spring Boot&logoColor=white"/></a><br><img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=Java&logoColor=white"/></a><br><img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=Django&logoColor=white"/></a><br><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/></a><br><img src="https://img.shields.io/badge/ChatGPT-74AA9C?style=flat-square&logo=OpenAI&logoColor=white"/></a><br><img src="https://img.shields.io/badge/OpenCV-FF0202?style=flat-square&logo=OpenCV&logoColor=white"/></a>|<img src="https://img.shields.io/badge/Amazon AWS-232F3E?style=flat-square&logo=Amazon AWS&logoColor=white"/></a><br><img src="https://img.shields.io/badge/Heroku-48099B?style=flat-square&logo=Heroku&logoColor=white"/>|<img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=Postman&logoColor=white"/></a><br><img src="https://img.shields.io/badge/Swagger-85EA2E?style=flat-square&logo=Swagger&logoColor=white"/></a><br><img src="https://img.shields.io/badge/Github-111011?style=flat-square&logo=Github&logoColor=white"/></a><br><img src="https://img.shields.io/badge/Visual Studio Code-007ACC?style=flat-square&logo=Visual Studio Code&logoColor=white"/></a><br><img src="https://img.shields.io/badge/IntelliJ IDEA-000000?style=flat-square&logo=IntelliJ IDEA&logoColor=white"/></a>

```
- Frontend : React, React Query, JavaScript
- Backend : Spring Boot, Java, Django, Python, ChatGPT, OpenCV
- Frontend Deployment: AWS Amplify
- Backend Deployment: AWS Elastic Beanstalk, Heroku
- API Test : Postman
- API Documentation : Swagger
- Version control: Github
- Development Environment : Visual studio code, IntelliJ IDEA
```
<br>



## 📗 API

### Spring - API called by the frontend
<img width="1470" alt="swagger spring api" src="https://github.com/2023-Hackathon-TeamSMUD/.github/assets/56509933/b95dc511-e09a-4713-9908-adb3f4ce7a68">

### Django - Image processing API called by Spring backend
<img width="1470" alt="swagger django api" src="https://github.com/2023-Hackathon-TeamSMUD/.github/assets/56509933/4d2af893-0854-4c2a-8ab2-5dacca37f49a">
<br><br>



## 📂 Directory Structure

### Frontend
```bash

```

### Backend_Spring
```bash

```

### Backend_Django (Image Processing)
```bash

```
<br>



## 👨‍👩‍👧‍👧 Team

|                                              [사현진](https://github.com/tkguswls1106)                                              |
| :------------------------------------------------------------------------------------------------------------------------------: |
| <img width = "300" src ="https://github.com/OnlineMemo/.github/assets/56509933/a13439f7-934d-41e1-be52-190e40753707"> |
|                                                   Team Leader, Backend Developer                                                    |
