## 프로젝트 개요
생성형 AI를 활용한 숏폼 자동 생성 서비스

## 프로젝트 설명
숏폼이 유행하는 요즘, 누구나 쉽게 숏폼을 제작할 수 있도록 하기 위해서 이 서비스를 제작했습니다.  
영상을 제작하는데 필요한 소스인 자막과 이미지를 직접 첨부할 수도 있고,  
제작하고 싶은 영상의 주제를 입력하는 것만으로도 자동으로 자막과 이미지를 생성할 수도 있습니다.  
앱 내에서 자체적으로 자막에 알맞은 TTS를 생성해주고, 사용자가 선택한 배경 음악까지 합쳐 결과 영상을 제공해줍니다.  
해당 결과 영상은 앱 자체의 게시물에 업로드 해 다른 앱 사용자와 공유할 수도 있고, 타 플랫폼에 공유하여 외부인과도 공유할 수 있습니다.  


## 팀원 소개

| 이름 | 프로필 | 역할 |
|------|--------|------|
| [신동현](https://github.com/whikih34) | <img src="https://github.com/whikih34.png" width="80"/> | - 앱 UI 디자인 및 구현<br>- API 연동 |
| [석종수](https://github.com/Seok-Soo) | <img src="https://github.com/Seok-Soo.png" width="80"/> | - AWS 인프라 구축<br>- DB 설계 및 구현<br>- 자막 생성 기능 구현 |
| [전지훈](https://github.com/xinun) | <img src="https://github.com/xinun.png" width="80"/> | - 앱 UI 디자인 및 구현<br>- 영상 공유 기능 구현<br>- 유튜브 업로드 기능 구현 |
| [조석원](https://github.com/swcho25) | <img src="https://github.com/swcho25.png" width="80"/> | - REST API 개발<br>- DB 설계 및 구현<br>- 영상 생성 기능 구현 |


## 주요 기능

### 1. 로그인
앱 자체 로그인 또는 소셜 로그인  
<img src="https://github.com/user-attachments/assets/43d06230-61b0-4d85-a7f6-3e8a004b14c2" width="300"/>

### 2. 게시판
다른 사용자와 앱을 통해 생성한 숏폼 공유  
<img src="https://github.com/user-attachments/assets/6c439cc6-d165-4584-8ffd-bdcaab9a5b0f" width="300"/>

### 3. 해시태그 검색
게시물에 저장된 해시태그 값에 따라 검색

### 4. 간단한 숏폼 제작 소스 생성
숏폼 생성에 사용될 자막 및 이미지를 사용자가 직접 첨부하는 것만이 아닌, 앱 자체의 서비스를 통해 간단하게 생성

### 5. 간단한 숏폼 생성
자막과 이미지를 통해 TTS와 배경 음악이 적용된 숏폼 생성

### 6. 유튜브 업로드
소셜 로그인을 한 사용자를 대상으로 생성한 숏폼을 유튜브로 업로드  
<img src="https://github.com/user-attachments/assets/ba2a4ec9-b03a-4ed4-8e61-365256e5682c" width="300"/>
<img src="https://github.com/user-attachments/assets/4e7d5bc7-4b23-4e28-bd40-e00414c6f42c" width="300"/>




## 주요 적용 기술

| 분류           | 내용 |
|----------------|------|
| **개발 언어**   | <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/> <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/> |
| **개발 환경**   | <img src="https://img.shields.io/badge/macOS-000000?style=for-the-badge&logo=apple&logoColor=white"/> <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/> |
| **프레임워크** | <img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/React%20Native-61DAFB?style=for-the-badge&logo=react&logoColor=white"/> |
| **개발 도구**   | <img src="https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge"/> <img src="https://img.shields.io/badge/Android%20Studio-3DDC84?style=for-the-badge&logo=androidstudio&logoColor=white"/> <img src="https://img.shields.io/badge/IntelliJ%20IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white"/> <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge"/> |
| **Open API**   | <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white"/> <img src="https://img.shields.io/badge/Stable%20Diffusion-FF1493?style=for-the-badge&logoColor=white"/> <img src="https://img.shields.io/badge/Runway-00D9FF?style=for-the-badge&logoColor=black"/> <img src="https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white"/> |


## 프로젝트 구조
<img width="926" alt="스크린샷 2025-05-21 오후 3 54 18" src="https://github.com/user-attachments/assets/d1546daf-34d6-4cb1-9a8c-1ae546444eeb" />


## 프로젝트 결과물
| 항목 | 링크 |
|------|------|
| 시연 영상 |  |
