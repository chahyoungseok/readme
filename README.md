# <img width="30" alt="docker logo" src="https://github.com/user-attachments/assets/72091dc1-2915-4b35-bec9-efe983e4b083"> RestDocker

### RestDocker 란
RestApi를 통해 Docker 의 기본 개념(도커 이미지, 컨테이너, 네트워크 등)을 학습할 수 있도록 서비스이다.

<br>


## 💁‍♂ 프로젝트 소개

### **서비스 Identiity** 
Docker 를 자유롭게 공부할 수 있는 환경을 제공하는 서비스. Docker 서비스를 시스템 단이 아닌 RestApi 와의 통신으로 구현합니다.

### **프로젝트 우선순위** 

> 프로젝트 우선순위는 기술적 Trade-Off 인 상황에서 근거있는 선택을 할수있게 해줍니다. <br>
> 1. 확장성
> 2. 가독성
> 3. 성능
> 4. 보안성 <br>
> * Docker 에 대해 공부를 하면서 구현하는 프로젝트입니다. 따라서 언제 어떻게 요구사항이 변경될지 모르기에 확장성이 가장 중요시되는 가치입니다.

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

## 🛠 기술 스택

<img width="834" alt="기술 스택" src="https://github.com/user-attachments/assets/b7f971d1-9fc8-40b9-8e37-ad00e2f90043">

<br><br>

## ⚙️ 아키텍처
<img width="500" alt="아키텍처" src="https://github.com/user-attachments/assets/b783a49f-fc7c-4e61-a3f9-e4ad003f8acd">


<br><br>

## 🎨 UI

### 주요 화면

| 페이지        | 스크린샷                         |
| ------------- | -------------------------------- |
| 회원가입 페이지 | ![SignUp Page](path/to/signup.png) |
| 대시보드      | ![Dashboard](path/to/dashboard.png) |

<br>

