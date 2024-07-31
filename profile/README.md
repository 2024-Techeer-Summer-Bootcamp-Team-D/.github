<h1 align="center">🎧 MV Studio 🎧</h1>
<div align="center"> 
<h3><b>Let's Create Music videos and Share them Together! </b></h3><br>
<img width="11000" src="https://github.com/user-attachments/assets/5cb8baea-82ee-4aa8-878d-d3202e7f6277">

<h3><b>MV Studio를 통해 창의적인 아이디어를 실현해 보세요!</b></h3>

<br>

</div>
<br><br>


# 📖 Table of contents
* [Introduction](#-introduction)
* [Demo](#-demo)
* [API](#-api)
* [System Architecture](#-system-architecture)
* [ERD](#-erd)
* [Tech Stack](#-tech-stack)
* [Monitoring](#-monitoring)
* [How to start](#-how-to-start)
* [Directory Structure](#-directory-structure)
* [Team Members](#-team-members)

<br>

# 📣 Introduction
### URL
> 🖥️ [MVStudio](https://mvstudio)

### Medium
> 🔎 [MVStudio Medium](https://medium.com) &nbsp;

<br>

- **사용자가 선택한 다양한 옵션에 따라 맞춤형 뮤직비디오를 생성**
- **AI 기술을 활용하여 높은 퀄리티의 뮤직비디오를 신속하게 제작**
- **장르, 악기, 주제, 분위기를 자유롭게 지정 가능**
- **사용자 채널 관리 및 차트 기반 분석 제공**
- **완성된 뮤직비디오를 소셜 미디어에 쉽게 공유**
- **제작한 뮤직비디오를 개인 프로젝트에 활용 가능**

<br>

# 🕺🏻 Demo
### Onboarding Page
> MV Studio의 간략한 설명을 담고 있습니다.
<img align="center" width="1000" alt="Onboarding Page" src="https://github.com/user-attachments/assets/39f6008d-2706-4ea6-a702-c943bdfb37a0">


### Login & Sign up
> 구글 소셜 로그인 및 회원가입을 통해 손쉽게 로그인하실 수 있습니다.
<br>
<img align="center" width="1000" alt="Login & Sign up" src="https://github.com/user-attachments/assets/9bf03788-3394-4b6b-9cb9-c16f484be1e7">

<br>

### Main Page
> 다른 사람들의 뮤직비디오를 시청할 수 있으며, 최신순, 조회수순, 급상승, 자신의 국가와 나이대에서 인기순으로 목록을 조회할 수 있습니다.
<br>
<img align="center" width="1000" alt="" src="https://github.com/user-attachments/assets/b21859ca-1641-4086-b497-2432bf3122f7">

<br>

### Search Music Video
> 검색 기능을 통해 원하는 뮤직비디오를 쉽게 찾을 수 있습니다.
<br>
<img align="center" width="1000" alt="" src="https://github.com/user-attachments/assets/dc648d65-0ea9-4dc5-98e5-14f42ec4b256">

<br>

### Create Music Video
> 사용자는 장르, 악기, 영상 스타일, 제목, 보컬, 언어, 템포를 직접 설정하여 뮤직비디오를 생성할 수 있습니다.<br>
> 선택한 설정을 바탕으로 제공되는 세 개의 가사 중 원하는 가사를 선택하면 해당 가사로 뮤직비디오가 생성됩니다.
<br>
<img align="center" width="1000" alt="" src="https://github.com/user-attachments/assets/6f9b6aeb-3b19-48b4-8dae-acf7af4c07b1">

<br>

### Play Music Video
> 뮤직비디오를 클릭하면 재생 페이지로 이동하여 시청할 수 있습니다.<br>
> 이 페이지에서 총 조회수, 만든 사람, 가사를 확인할 수 있으며 시청 도중 나중에 다시 와도 이전에 보던 부분부터 계속 시청할 수 있습니다.
<br>
<img align="center" width="1000" alt="" src="https://github.com/user-attachments/assets/b3268116-9b7e-42fb-b01f-354d919f03ab">

<br>
  
### My Page
> 사용자는 마이페이지에서 자신이 만든 뮤직비디오와 최근에 시청한 뮤직비디오를 확인할 수 있습니다.
> 인스타그램과 유튜브 버튼을 통해 자신의 인스타그램과 유튜브 계정으로 바로 이동할 수 있습니다.
<br>
<img align="center" width="1000" alt="" src="https://github.com/user-attachments/assets/db9365d8-7e89-4de1-9886-d03406757de0">

<br>

### Analyzing my channel
> 사용자는 자신이 만든 뮤직비디오의 시청 추이를 날짜별 조회수, 성별, 국가별, 연령대별 차트로 분석할 수 있습니다.
<br>
<img align="center" width="1000" alt="" src="https://github.com/user-attachments/assets/5c873ef6-f61a-471d-8155-4aca7de01df9">

<br>

### Upload Music Video
> 사용자는 자신의 뮤직비디오를 유튜브에 업로드할 수 있습니다.
<br>
<img align="center" width="1000" alt="" src="https://github.com/user-attachments/assets/1593e304-c1c6-47fd-a753-c34485299531">

<br>

### Buy Credits
> 뮤직비디오 제작에 필요한 크레딧은 카카오페이를 통해 결제할 수 있습니다.
<br>
<img align="center" width="1000" alt="" src="https://github.com/user-attachments/assets/99b7d465-ff65-4b11-b836-532681a6bd29">


<br>

# 📗 API

 |**charts**|
 |:-------------:|
 |<img align="center" width="1000" alt="charts" src="https://github.com/user-attachments/assets/aef0f280-3a65-40c2-8c32-2f3027465718">|
 |**members**|
 |<img align="center" width="1000" alt="members" src="https://github.com/user-attachments/assets/93f56572-e398-4810-a89b-4869fcae5ccb">|
 |**music-videos**|
 |<img align="center" width="1000" alt="music-videos" src="https://github.com/user-attachments/assets/b4d3b0ca-14c2-4bdb-a63a-50dab395f1fe">|
 |**oauth**|
 |<img align="center" width="1000" alt="oauth" src="https://github.com/user-attachments/assets/f910a641-c8f5-4d54-8222-98d34a49f806">|


<br><br>

# 🛠 ️System Architecture <a name="-system-architecture"></a>
<div align="center">
  <img align="center" width="1000" src="https://github.com/user-attachments/assets/4d787a65-837f-42ff-b922-e470210ea897">
</div>
<br><br>

# 🔑 ERD
<div align="center">
  <img width="1000" src="https://github.com/user-attachments/assets/55a76355-4840-433f-b721-415387c78a24">
</div>
<br><br>

# 💻 Tech Stack

<div align="center">
  <table>
    <tr>
      <th>Field</th>
      <th>Technology of use</th>
    </tr>
    <tr>
      <td><b>Frontend</b></td>
         <td>
           <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">
           <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
           <img src="https://img.shields.io/badge/css3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
           <img src="https://img.shields.io/badge/styledcomponents-DB7093?style=for-the-badge&logo=styledcomponents&logoColor=white">
           <img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white">
           <img src="https://img.shields.io/badge/vite-646CFF?style=for-the-badge&logo=vite&logoColor=white">
           <img src="https://img.shields.io/badge/tanstackquery-FF4154?style=for-the-badge&logo=reactquery&logoColor=black">
           <img src="https://img.shields.io/badge/axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white">
           <img src="https://img.shields.io/badge/mui-007FFF?style=for-the-badge&logo=mui&logoColor=white">
           <img src="https://img.shields.io/badge/chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white">
           <img src="https://img.shields.io/badge/eslint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white">
           <img src="https://img.shields.io/badge/prettier-F7B93E?style=for-the-badge&logo=prettier&logoColor=white">
           <img src="https://img.shields.io/badge/zustand-F3DF49?style=for-the-badge&logo=zustand&logoColor=white">
         </td>
    </tr>
    <tr>
      <td><b>Backend</b></td>
      <td>
        <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=Django&logoColor=white">
        <img src="https://img.shields.io/badge/DJANGO_REST_Framework-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709">
        <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=RabbitMQ&logoColor=white">
        <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=Celery&logoColor=white">
      </td>
    </tr>
    <tr>
      <td><b>DevOps</b></td>
      <td>
        <img src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=black">
        <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
        <img src="https://img.shields.io/badge/Amazon_EC2-FF9900?style=for-the-badge&logo=Amazon-EC2&logoColor=black">
        <img src="https://img.shields.io/badge/gunicorn-499848?style=for-the-badge&logo=gunicorn&logoColor=black">
        <img src="https://img.shields.io/badge/githubactions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white">
      </td>
    </tr>
    <tr>
      <td><b>DB</b></td>
      <td>
        <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
        <img src="https://img.shields.io/badge/amazonrds-527FFF?style=for-the-badge&logo=amazonrds&logoColor=white">
        <img src="https://img.shields.io/badge/Amazon S3-569A31?style=for-the-badge&logo=Amazon S3&logoColor=white">
        <img src="https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white">
      </td>
    </tr>
    <tr>
      <td><b>AI</b></td>
      <td>
        <img src="https://img.shields.io/badge/chatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white">
        <img src="https://img.shields.io/badge/Suno-000000?style=for-the-badge&logo=Suno&logoColor=black&logoColor=white">
        <img src="https://img.shields.io/badge/runway-8947A8?style=for-the-badge&logoColor=black">
      </td>
    </tr>
    <tr>
      <td><b>Monitoring</b></td>
      <td>
        <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=black">
        <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=black">
        <img src="https://img.shields.io/badge/Amazon Cloudwatch-FF4F8B?style=for-the-badge&logo=Amazon Cloudwatch&logoColor=white">
        <img src="https://img.shields.io/badge/cadvisor-1478FF?style=for-the-badge&logoColor=black">
        <img src="https://img.shields.io/badge/node_exporter-37D100?style=for-the-badge&logoColor=black">
        <img src="https://img.shields.io/badge/rds_exporter-285FFA?style=for-the-badge&logoColor=black">
        <img src="https://img.shields.io/badge/filebeats-005571?style=for-the-badge&logo=beats&logoColor=white">
        <img src="https://img.shields.io/badge/elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white">
        <img src="https://img.shields.io/badge/logstash-005571?style=for-the-badge&logo=logstash&logoColor=white">
        <img src="https://img.shields.io/badge/kibana-005571?style=for-the-badge&logo=kibana&logoColor=white">
      </td>
    </tr>
    <tr>
      <td><b>etc</b></td>
      <td>
        <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
        <img src="https://img.shields.io/badge/slack-4A154B?style=for-the-badge&logo=slack&logoColor=white">
        <img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white">
        <img src="https://img.shields.io/badge/zoom-0B5CFF?style=for-the-badge&logo=zoom&logoColor=black">
        <img src="https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white">
      </td>
    </tr>
  </table>
</div>
<br>


# 📊 Monitoring

<div align="center">
  <h3 align="left">Prometheus & Grafana</h3>
  
  |**cAdvisor**|**Node Exporter**|
  |:---------:|:-----------------:|
  |<img width="1000" alt="cAdvisor" src="https://github.com/user-attachments/assets/5a1d21e4-bb17-4579-9577-c06864a79302">|<img width="1000" alt="Node Exporter" src="https://github.com/user-attachments/assets/da1d15d4-b34d-4d72-910c-c768a2a70534">
  
  <br>
  
  |**Cloud Watch**|
  |:---------:|
  |<img width="1000" alt="Cloud Watch" src="https://github.com/user-attachments/assets/8d5293c1-ec6e-4743-b3b9-06c44a94c575">|
  
  <br>
  
  |**ELK**|
  |:---------:|
  |<img width="1000" alt="ELK2" src="https://github.com/user-attachments/assets/3e5d7125-2a92-44d4-bd33-eba6bbd4ac15">|
</div>

<br>

# 🔧Logging

<div align="center">
   
   |**ELK**|
   |:---------:|
   |<img width="1000" alt="ELK" src="https://github.com/user-attachments/assets/5991a158-203e-471f-b755-2c8de1a86050">|
   
</div>

# 🚀 How To Start

### 1. Clone The Repository
```
https://github.com/2024-Techeer-Summer-Bootcamp-Team-D/MVStudio-Docker.git
```
### 2. ENV Setting In The MVStudio-Docker Folder
* .env
```
ELASTIC_VERSION=
ELASTIC_PASSWORD=
LOGSTASH_INTERNAL_PASSWORD=
KIBANA_SYSTEM_PASSWORD=
METRICBEAT_INTERNAL_PASSWORD=
FILEBEAT_INTERNAL_PASSWORD=
HEARTBEAT_INTERNAL_PASSWORD=
MONITORING_INTERNAL_PASSWORD=
BEATS_SYSTEM_PASSWORD=
INIT_INDEX=
```
* MVStudio-Frontend/.env
```
VITE_REACT_APP_BASE_URL =
```
* MVStudio-Backend/.env
```
SECRET_KEY=
DEBUG=

MYSQL_ROOT_PASSWORD=
MYSQL_DATABASE=
MYSQL_USER=
MYSQL_PASSWORD=
DATABASE_HOST=
DB_SQL_MODE=

AWS_ACCESS_KEY_ID=
AWS_SECRET_ACCESS_KEY=
AWS_STORAGE_BUCKET_NAME=
AWS_S3_REGION_NAME=

OPENAI_API_KEY=
SUNO_API_KEY=

SOCIAL_AUTH_GOOGLE_OAUTH2_KEY=
SOCIAL_AUTH_GOOGLE_OAUTH2_SECRET=
RUNWAYML_API_KEY=

BASE_BACKEND_URL=
BASE_FRONTEND_URL=
REFRESH_TOKEN_SECRET=
KAKAO_APP_ADMIN_KEY=
CID=
```
<br>

### 3. Run Docker
```
$ docker-compose -f docker-compose.prod.yml -f docker-compose.monitoring.yml up -d --build
```
<br>

# 📂 Directory Structure

<details>
    <summary>MVStudio-Docker</summary>
<pre>
<code>

📦MVStudio-Docker  

</code>
</pre>
</details>


<details>
    <summary>MVStudio-Frontend</summary>
<pre>
<code>

📦MVStudio-Frontend  

</code>
</pre>
</details>

<details>
    <summary>MVStudio-Backend</summary>
<pre>
<code>

📦MVStudio-Backend  

</code>
</pre>
</details>
<br>

# 👥 Team Members
<h2>👥 Team Members</h2>
<table>
  <tr>
    <th>Name</th>
    <th>조진우</th>
    <th>강기환</th>
    <th>김진희</th>
    <th>박유경</th>
    <th>유성원</th>
    <th>최호원</th>
  </tr>
  <tr>
    <th>Profile</th>
    <td><img src="https://github.com/jinoo0306.png" style="width:120px;height:120px;"></td>
    <td><img src="https://github.com/GiHwan2.png" style="width:120px;height:120px;"></td>
    <td><img src="https://github.com/kimzini.png" style="width:120px;height:120px;"></td>
    <td><img src="https://github.com/ukongee.png" style="width:120px;height:120px;"></td>
    <td><img src="https://github.com/Youth-one.png" style="width:120px;height:120px;"></td>
    <td><img src="https://github.com/BMHowon.png" style="width:120px;height:120px;"></td>
  </tr>
  <tr>
    <th>Role</th>
    <td>Leader, Backend,<br> Frontend, DevOps</td>
    <td>Backend, DevOps</td>
    <td>Backend, DevOps</td>
    <td>Frontend, Design</td>
    <td>Frontend, Design</td>
    <td>Frontend, Design</td>
  </tr>
  <tr>
    <th>GitHub</th>
    <td><a href="https://github.com/jinoo0306">@jinoo0306</a></td>
    <td><a href="https://github.com/Gihwan2">@Gihwan2</a></td>
    <td><a href="https://github.com/kimzini">@kimzini</a></td>
    <td><a href="https://github.com/ukongee">@ukongee</a></td>
    <td><a href="https://github.com/Youth-one">@Youth-one</a></td>
    <td><a href="https://github.com/BMHowon">@BMHowon</a></td>
  </tr>
</table>
<br>
