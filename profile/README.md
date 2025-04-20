# L22CORD
웹 기반 채팅 서비스를 구현중인 팀입니다.

## 목차
> 1. [구성원](#1-구성원)
> 2. [프로젝트 소개](#2-프로젝트-소개)
> 3. [개발 환경](#3-개발-환경)
>> 1. [인프라](#1-인프라)
>> 2. [APIs / Libs](#2-apis--libs)
> 4. [서버 아키텍처](#4-서버-아키텍처)

<br/>
<br/>

# 1. 구성원
<div align="center">
  
| 최승인 | 은희상 |
| :---: |  :----: |
|<img height="150" src="https://github.com/user-attachments/assets/8c4618e6-0106-49a9-95c5-7c538ae9d74b">|<img height="150" src="https://github.com/user-attachments/assets/b57ff75f-f1c3-4889-80f4-a1c4064420b2">|
|<a href = "https://github.com/Lucas-Choi-17"><img alt="GitHub" src ="https://img.shields.io/badge/GitHub-181717.svg?&style=for-the-badge&logo=GitHub&logoColor=white"/>|<a href = "https://github.com/Silver-Eun"><img alt="GitHub" src ="https://img.shields.io/badge/GitHub-181717.svg?&style=for-the-badge&logo=GitHub&logoColor=white"/>|
  
</div>

<br/>

# 2. 프로젝트 소개
채팅 서비스를 개발하는 프로젝트로 사용자 간 실시간 커뮤니케이션 기능을 제공하고 있습니다. 안정적이고 효율적인 서비스 운영을 위해 마이크로서비스 아키텍처를 설계하였으나 개인 서버 환경의 한계로 인해 현재는 하나의 서버에서 마이크로서비스 구조로 배포하여 운영 중입니다.

- 배포 URL : https://l22cord.site

- 개발 기간 : 2024.12.16 ~ 진행중

<br/>

# 3. 개발 환경
## 1. 인프라
- **Front** : REACT, JavaScript, CSS
- **Back-end** : JAVA, Spring-Boot, Spring Data JPA, MySQL, Redis
- **Security** : Spring Security, JWT(Json Web Token)
- **Service & Database Server** : Private Mac Server
- **Object Storage** : MinIO
- **Docker**
- **GitHub Actions**
- **Nginx**

<br/>

## 2. APIs / Libs
### _ Verification Mail
- Gmail smtp

### _ L22cordTEAM Builds
- JwtLibrary : JWT 토큰 인증을 위한 통일화된 유틸리티(토큰 생성 및 데이터 추출)
- AuthAPI : 사용자 로그인, 회원가입 및 인증을 위한 API
- UserAPI : 전반적인 사용자 정보를 관리하는 API
- ChatroomAPI : 채팅방 정보 및 채팅을 관리 및 socket을 중계하는 API
- NotifyAPI : 사용자에게 전송되는 기본 알림 및 채팅방 알림을 위한 API

<br/>

# 4. 서버 아키텍처
![server](https://github.com/user-attachments/assets/1a097e63-e897-4faf-b18f-4dac77e033e9)


