# <img width="30" alt="docker logo" src="https://github.com/user-attachments/assets/72091dc1-2915-4b35-bec9-efe983e4b083"> RestDocker

> 프로젝트 소개: 도커 이미지, 컨테이너, 네트워크 등을 학습할 수 있도록 서비스

<br>

## 📌 목차
1. [프로젝트 소개](#프로젝트-소개)
2. [기술 스택](#기술-스택)
3. [구현 기능](#구현-기능)
4. [아키텍처](#아키텍처)
5. [UI](#UI)

<br>

## 💁‍♂ 프로젝트 소개

프로젝트에 대한 상세 설명을 여기에 적습니다. 예를 들어:
- 프로젝트의 배경과 동기
- 주요 기능과 사용 사례
- 간략한 아키텍처 다이어그램

![Architecture Diagram](path/to/architecture-diagram.png)

<br>

## 🛠 기술 스택

<img width="834" alt="스크린샷 2024-09-10 오후 4 56 05" src="https://github.com/user-attachments/assets/b7f971d1-9fc8-40b9-8e37-ad00e2f90043">

<br>

## 🏗 구현 기능

1. **회원 관리**
   - 카카오 로그인 / 네이버 로그인
   - 인증토큰 갱신
   - 회원가입 시, bridge 네트워크 기본 할당
2. **도커 이미지**
   - 이미지 전체 조회
   - 특정 이미지 자세히 조회
   - DockerHub에서 Image 가져오기
   - 이미지 삭제
3. **도커 네트워크**
   - Host의 네트워크 전체 조회
   - Host의 특정 네트워크 자세히 조회
   - Host의 네트워크 생성
   - Host의 네트워크 삭제
4. **도커 컨테이너**
   - 실행 상태의 컨테이너만 조회 ( 상태에 관련없이 전체 조회, 마지막 수정 컨테이너 조회 )
   - 특정 컨테이너 자세한 조회
   - 컨테이너 생성
   - 컨테이너 삭제
   - 컨테이너 실행
   - 컨테이너 시작
   - 컨테이너 종료

<br>

## ⚙️ 아키텍처
![아키텍처](https://github.com/user-attachments/assets/b783a49f-fc7c-4e61-a3f9-e4ad003f8acd)


<br>

## 🎨 UI

### 주요 화면

| 페이지        | 스크린샷                         |
| ------------- | -------------------------------- |
| 회원가입 페이지 | ![SignUp Page](path/to/signup.png) |
| 대시보드      | ![Dashboard](path/to/dashboard.png) |

<br>

