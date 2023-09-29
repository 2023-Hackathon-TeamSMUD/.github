<p align="center">
  <img width="240" alt="SockSense 앱아이콘" src="https://github.com/2023-Hackathon-TeamSMUD/.github/assets/56509933/b806f750-80c3-4ce8-9271-87dde4148eb4">
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
- 페이지별 서비스 코치 마크와 함께 음성 가이드를 제공하여 시각장애인들의 편의성을 높였습니다.
- 촬영을 통해 양말 구분(짝이 올바른지) 및 양말과 성별에 어울리는 코디를 제공합니다. <br>
(영상 처리를 통한 양말 이미지 분석과 ChatGPT를 활용한 코디 추천)
- 추천받은 코디를 저장하여 원할 때 저장된 코디를 확인할 수 있습니다.
- 시각장애인을 위한 서비스이기에, 회원가입 없이 모바일웹으로 간편하게 이용 가능하도록 하였습니다.
<br><br>



## 📹 Demo

### Mobile Page

**Separation start**|**Shoot one sock**|**Shoot another sock**|**Separation complete**
-----|-----|-----|-----
<img src="https://github.com/2023-Hackathon-TeamSMUD/.github/assets/56509933/3a5372f7-81f9-466f-9680-e9cc79f455f0" width="100%">|<img src="https://github.com/2023-Hackathon-TeamSMUD/.github/assets/56509933/e126e279-c7b1-45dc-8a83-b32cd8977d90" width="100%">|<img src="https://github.com/2023-Hackathon-TeamSMUD/.github/assets/56509933/45da9402-0feb-4d2e-99fb-a23fb10a3cd5" width="100%">|<img src="https://github.com/2023-Hackathon-TeamSMUD/.github/assets/56509933/0cae28d7-8cbd-4358-8959-1afbb28614b2" width="100%">
양말 짝 구분 메인 페이지 입니다.|단계별로 안내해주며, 한쪽 양말을 먼저 촬영합니다.|다른 쪽 양말을 촬영합니다.|양말의 짝을 구분해줍니다.

**Styling start**|**Shoot sock**|**Choose gender**|**Styling complete**
-----|-----|-----|-----
<img src="https://github.com/2023-Hackathon-TeamSMUD/.github/assets/56509933/addca5b4-5735-483f-ab38-66ea720d0911" width="100%">|<img src="https://github.com/2023-Hackathon-TeamSMUD/.github/assets/56509933/93f78b5f-b4ba-439b-afeb-35ed7b7a5f07" width="100%">|<img src="https://github.com/2023-Hackathon-TeamSMUD/.github/assets/56509933/32a7fbe6-fa0a-4af7-ba92-de40dd5b32fd" width="100%">|<img src="https://github.com/2023-Hackathon-TeamSMUD/.github/assets/56509933/49692eb3-b7c3-4efd-9176-54f8e313b3c9" width="100%">
양말 코디 메인 페이지 입니다.|양말 촬영 완료 페이지 입니다.|본인의 성별을 선택합니다.|양말과 성별에 어울리는 코디를 추천해줍니다.

**Coordination guide**|**Coordination list**|**Delete Coordination**|**None Coordination**
-----|-----|-----|-----
<img src="https://github.com/2023-Hackathon-TeamSMUD/.github/assets/56509933/8520bde4-b840-4e86-bbbb-a1458a7a6e45" width="100%">|<img src="https://github.com/2023-Hackathon-TeamSMUD/.github/assets/56509933/1e9bd995-5d5a-4dd5-95f3-444447c2b496" width="100%">|<img src="https://github.com/2023-Hackathon-TeamSMUD/.github/assets/56509933/eaaafabb-3539-46c7-871a-cefab7e63df1" width="100%">|<img src="https://github.com/2023-Hackathon-TeamSMUD/.github/assets/56509933/459ca5d3-d6f7-4488-8171-02a943f81f7a" width="100%">
저장된 코디를 안내합니다.|저장된 코디 목록 페이지 입니다.|저장된 코디를 삭제합니다.|저장된 코디가 없음을 알립니다.

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
├── package-lock.json
├── package.json
├── public
│   ├── favicon.ico
│   ├── index.html
│   └── manifest.json
├── src
│   ├── App.js
│   ├── api
│   │   ├── postFashion.jsx
│   │   └── postPair.jsx
│   ├── assets
│   │   ├── CameraPage
│   │   │   ├── Aim.svg
│   │   │   ├── Progress1.svg
│   │   │   ├── Progress2.svg
│   │   │   ├── Progress3.svg
│   │   │   ├── Shot.svg
│   │   │   ├── Storage.svg
│   │   │   ├── heart.svg
│   │   │   ├── oicon.jpeg
│   │   │   └── xicon.jpeg
│   │   ├── MainPage
│   │   │   ├── ActiveMan.png
│   │   │   ├── ActiveWoman.png
│   │   │   ├── Back.svg
│   │   │   ├── Black.png
│   │   │   ├── Blue.png
│   │   │   ├── Gray.png
│   │   │   ├── Green.png
│   │   │   ├── Man.png
│   │   │   ├── Orange.png
│   │   │   ├── Pants.png
│   │   │   ├── Progress1.png
│   │   │   ├── Progress2.png
│   │   │   ├── Progress3.png
│   │   │   ├── Purple.png
│   │   │   ├── Red.png
│   │   │   ├── Shoe.png
│   │   │   ├── Top.png
│   │   │   ├── White.png
│   │   │   ├── Woman.png
│   │   │   └── Yellow.png
│   │   ├── StartPage
│   │   │   ├── Logo.png
│   │   │   └── Logo.svg
│   │   ├── StoragePage
│   │   │   ├── Delete.png
│   │   │   └── null.svg
│   │   └── common
│   │       ├── Logo.png
│   │       └── Logo.svg
│   ├── component
│   │   ├── container
│   │   │   ├── CameraPage
│   │   │   │   ├── CameraContainer.jsx
│   │   │   │   ├── CameraPageContainer.jsx
│   │   │   │   └── ResultModalContainer.jsx
│   │   │   ├── MainPage
│   │   │   │   ├── MainCameraContainer.jsx
│   │   │   │   ├── MainPageContainer.jsx
│   │   │   │   ├── ResultSockColorContainer.jsx
│   │   │   │   └── SelectGenderContainer.jsx
│   │   │   ├── StartPage
│   │   │   │   └── LogoContainer.jsx
│   │   │   └── common
│   │   │       ├── StartRenderingContainer.jsx
│   │   │       └── data.jsx
│   │   └── presentation
│   │       ├── CameraPage
│   │       │   ├── Camera.jsx
│   │       │   ├── CameraInformation1.jsx
│   │       │   ├── CameraInformation2.jsx
│   │       │   ├── ResultModal.jsx
│   │       │   └── ServerModal.jsx
│   │       ├── MainPage
│   │       │   ├── Cody.jsx
│   │       │   ├── MainCamera.jsx
│   │       │   ├── ResultSockColor.jsx
│   │       │   ├── SelectGender.jsx
│   │       │   ├── ServerModal.jsx
│   │       │   └── Skelethone.jsx
│   │       ├── StartPage
│   │       │   └── Logo.jsx
│   │       └── common
│   │           └── StartRendering.jsx
│   ├── hooks
│   │   └── useTextToSpeech.jsx
│   ├── index.js
│   ├── pages
│   │   ├── CameraPage.jsx
│   │   ├── MainPage.jsx
│   │   ├── StartPage.jsx
│   │   └── StoragePage.jsx
│   └── styles
│       └── components
│           ├── CameraPage
│           │   ├── Camera.scss
│           │   ├── CameraInformation1.scss
│           │   ├── CameraInformation2.scss
│           │   ├── resultModal.scss
│           │   └── serverModal.scss
│           ├── MainPage
│           │   ├── Cody.scss
│           │   ├── MainserverModal.scss
│           │   ├── ResultSockColor.scss
│           │   ├── SelectGender.scss
│           │   └── Skelethone.scss
│           ├── StartPage
│           │   └── Logo.scss
│           ├── StoragePage
│           │   └── StoragePage.scss
│           └── common
│               └── StartRendering.scss
└── yarn.lock
```

### Backend_Spring
```bash
└── src
    ├── main
    │   ├── generated
    │   ├── java
    │   │   └── com
    │   │       └── smud
    │   │           └── socksensespringproject
    │   │               ├── SocksenseSpringProjectApplication.java
    │   │               ├── config
    │   │               │   └── SwaggerConfig.java
    │   │               ├── controller
    │   │               │   ├── PairController.java
    │   │               │   ├── StylingController.java
    │   │               │   └── TestController.java
    │   │               ├── dto
    │   │               │   ├── chatgpt
    │   │               │   │   ├── ChatgptRequestDto.java
    │   │               │   │   ├── ChatgptResponseDto.java
    │   │               │   │   ├── Choice.java
    │   │               │   │   ├── Message.java
    │   │               │   │   └── Usage.java
    │   │               │   ├── computervision
    │   │               │   │   ├── OneImageRequestDto.java
    │   │               │   │   ├── SimilarityResponseDto.java
    │   │               │   │   ├── SockColorResponseDto.java
    │   │               │   │   └── TwoImagesRequestDto.java
    │   │               │   ├── pair
    │   │               │   │   └── PairResponseDto.java
    │   │               │   └── styling
    │   │               │       ├── Styling.java
    │   │               │       ├── StylingRequestDto.java
    │   │               │       └── StylingResponseDto.java
    │   │               ├── externalapi
    │   │               │   ├── ChatCompletionClient.java
    │   │               │   └── ComputerVisionClient.java
    │   │               ├── response
    │   │               │   ├── GlobalExceptionHandler.java
    │   │               │   ├── ResponseCode.java
    │   │               │   ├── ResponseData.java
    │   │               │   ├── exeption
    │   │               │   │   ├── GenderBadRequestException.java
    │   │               │   │   ├── ImageCantReadException.java
    │   │               │   │   └── ImagesBadRequestException.java
    │   │               │   └── responseitem
    │   │               │       ├── MessageItem.java
    │   │               │       └── StatusItem.java
    │   │               ├── service
    │   │               │   ├── PairService.java
    │   │               │   ├── StylingService.java
    │   │               │   └── logic
    │   │               │       ├── ChatCompletionServiceLogic.java
    │   │               │       ├── ComputerVisionServiceLogic.java
    │   │               │       ├── PairServiceLogic.java
    │   │               │       └── StylingServiceLogic.java
    │   │               └── util
    │   │                   └── MultipartJackson2HttpMessageConverter.java
    │   └── resources
    │       ├── application-chatgpt.properties
    │       ├── application.properties
    │       ├── static
    │       └── templates
    └── test
        └── java
            └── com
                └── smud
                    └── socksensespringproject
                        └── SocksenseSpringProjectApplicationTests.java
```

### Backend_Django (Image Processing)
```bash
├── computervision
│   ├── __init__.py
│   ├── __pycache__
│   │   ├── __init__.cpython-311.pyc
│   │   ├── admin.cpython-311.pyc
│   │   ├── apps.cpython-311.pyc
│   │   ├── models.cpython-311.pyc
│   │   ├── urls.cpython-311.pyc
│   │   └── views.cpython-311.pyc
│   ├── admin.py
│   ├── apps.py
│   ├── migrations
│   │   ├── __init__.py
│   │   └── __pycache__
│   │       └── __init__.cpython-311.pyc
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
├── db.sqlite3
├── manage.py
└── socksense
    ├── __init__.py
    ├── __pycache__
    │   ├── __init__.cpython-311.pyc
    │   ├── settings.cpython-311.pyc
    │   ├── urls.cpython-311.pyc
    │   └── wsgi.cpython-311.pyc
    ├── asgi.py
    ├── settings.py
    ├── urls.py
    └── wsgi.py
```
<br>



## 👨‍👩‍👧‍👧 Team

| [사현진](https://github.com/tkguswls1106) | [정연재](https://github.com/zzangjyj0818) | [유성민](https://github.com/ysmuei) | [김형섭](https://github.com/khs-alt) | [이정향](https://github.com/Hyanggggg) |
| :----------------------------------------: | :----------------------------------------: | :----------------------------------------: | :----------------------------------------: | :----------------------------------------: |
| <img width = "300" src ="https://github.com/2023-Hackathon-TeamSMUD/.github/assets/56509933/95202f4c-ea64-49fa-a288-85eb1bce2da9"> | <img width = "300" src ="https://github.com/2023-Hackathon-TeamSMUD/.github/assets/56509933/513a094c-a28f-413b-84e1-a689b7e3b06b"> | <img width = "300" src ="https://github.com/2023-Hackathon-TeamSMUD/.github/assets/56509933/361da55a-604e-4bd0-a5ad-1af81e06ba71"> | <img width = "300" src ="https://github.com/2023-Hackathon-TeamSMUD/.github/assets/56509933/5d89af01-29c4-441b-b7be-02338dba9b28"> | <img width = "300" src ="https://github.com/2023-Hackathon-TeamSMUD/.github/assets/56509933/a563b39b-6d80-40b1-930f-311455b21e82"> |
| Team Leader, Backend Developer | Frontend Developer | Frontend Developer | Image Processing Engineer | Designer |
