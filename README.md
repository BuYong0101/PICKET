# PICKET
공연 티켓 예매 사이트

- [프로젝트 개요](#프로젝트-개요)
- [기술 스택](#프로젝트-기술-스택)
- [팀원 구성 및 역할](#팀원-구성-및-역할)
- [페이지별 기능](#페이지별-기능)
  - [메인페이지](#메인페이지)
  - [공연페이지](#공연목록페이지)
  - [마이페이지](#마이페이지)
  - [고객센터](#고객센터)
- [시연 영상](#시연-영상)

## 프로젝트 개요
* 이 사이트는 콘서트, 뮤지컬, 연극, 클래식, 전시회와 같은 다양한 공연들의 티켓을 예매할 수 있는 사이트입니다.
* 직관적인 디자인과 편리한 기능들을 통해 문화 예술을 더 많은 사람들에게 쉽게 접할 수 있도 하는 것을 목표로 하고 있습니다.
* 사용자는 각 공연의 상세정보를 통해 원하는 날짜의 어떤 공연 열리는지 손쉽게 확인할 수 있습니다.

## 프로젝트 기술 스택
- **Frontend**: HTML, CSS, JavaScript, Thymeleaf
- **Backend**: Spring Boot, Spring Security, Spring Data JPA
- **Database**: Oracle
- **IDE**: IntelliJ, VS Code, SQL Developer
- **OpenAPI**: 카카오 지도 API
- **버전 관리**: GitHub
  
## 팀원 구성 및 역할
- **오상훈**: 해당 상품의 상세 페이지 구현 및 마이 페이지 지원 
- **윤재민**: 고객센터 구현 및 메인 페이지, 백엔드 지원
- **조미르**: 백엔드 전반적인 구현 및 에러 확인
- **최부용**: 마이페이지 구현 및 상세 페이지 지원
- **황규현**: 메인 페이지 및 로그인 UI 담당, 웹 홈페이지의 전반적인 UI 수정 및 지원,  백엔드 데이터 베이스  Entity 및 DTO 구현 

## 페이지별 기능

### 메인페이지
![메인페이지](https://github.com/Ddonggirim/PICKET/blob/master/README%20%EC%9D%B4%EB%AF%B8%EC%A7%80/%EB%A9%94%EC%9D%B8%ED%8E%98%EC%9D%B4%EC%A7%80.png)

- **회원가입 및 로그인**
<br>
<div style="display: flex;">
    <img src="https://raw.githubusercontent.com/Ddonggirim/PICKET/master/README%20%EC%9D%B4%EB%AF%B8%EC%A7%80/%ED%9A%8C%EC%9B%90%EA%B0%80%EC%9E%85.png" alt="공연일자" width="500" style="margin-right: 10px;" />
    <img src="https://raw.githubusercontent.com/Ddonggirim/PICKET/master/README%20%EC%9D%B4%EB%AF%B8%EC%A7%80/%EB%A1%9C%EA%B7%B8%EC%9D%B8.png" alt="티켓예매" width="500" />
</div>
<br>

---

### 공연목록페이지
![공연 목록](https://github.com/Ddonggirim/PICKET/blob/master/README%20%EC%9D%B4%EB%AF%B8%EC%A7%80/%EA%B3%B5%EC%97%B0%ED%8E%98%EC%9D%B4%EC%A7%80.png)
<br>
- **공연 상세정보**
<br>
![상세정보](https://github.com/Ddonggirim/PICKET/blob/master/README%20%EC%9D%B4%EB%AF%B8%EC%A7%80/%EA%B3%B5%EC%97%B0%EC%83%81%EC%84%B8%EC%A0%95%EB%B3%B4.png)
<br>
- **길찾기**
<br>
![길찾기](https://github.com/Ddonggirim/PICKET/blob/master/README%20%EC%9D%B4%EB%AF%B8%EC%A7%80/%EA%B8%B8%EC%B0%BE%EA%B8%B0.png)
<br>
- **티켓예매**
<div style="display: flex;">
    <img src="https://raw.githubusercontent.com/Ddonggirim/PICKET/master/README%20%EC%9D%B4%EB%AF%B8%EC%A7%80/%EA%B3%B5%EC%97%B0%EC%9D%BC%EC%9E%90.png" alt="공연일자" width="500" style="margin-right: 10px;" />
    <img src="https://raw.githubusercontent.com/Ddonggirim/PICKET/master/README%20%EC%9D%B4%EB%AF%B8%EC%A7%80/%ED%8B%B0%EC%BC%93%EC%98%88%EB%A7%A4.png" alt="티켓예매" width="500" />
</div>
<br>

---

### 마이페이지
- **마이티켓**: 회원이 예매한 티켓 조회
<br>
![마이티켓](https://github.com/user-attachments/assets/0f18921e-221b-43de-8b45-c8b69295fa8b)
<br>
- **관심목록**: 회원이 찜한 공연 조회
<br>
![관심목록](https://github.com/user-attachments/assets/32b78703-4b5d-438a-8865-93252543478c)
<br>
- **포인트**: 회원의 포인트 충전 및 내역 조회
<br>
![포인트](https://github.com/user-attachments/assets/6f9b328f-6b84-43dc-b693-03458e319b73)
<br>
- **회원정보**: 회원정보 수정 및 회원탈퇴
<br>
![회원정보](https://github.com/user-attachments/assets/782229f6-ec4b-4ca7-99c2-4e2aa833bc7f)
<br>
- **문의내역**: 회원의 문의내역 조회
<br>
![문의내역](https://github.com/user-attachments/assets/bff96a79-3a1d-48d1-b031-d976d969a171)

---

### 고객센터
![고객센터](https://github.com/user-attachments/assets/8af23cd6-1963-41eb-895b-b333351459c6)
<br>
- **Q&A**: 회원들이 자주 묻는 질문
<br>
![Q&A](https://github.com/user-attachments/assets/d8e415ca-30dc-41b7-9039-05c9e736be23)
<br>
- **1:1 문의**: Q&A로 미해결 시 문의서를 작성
<br>
![1:1 문의](https://github.com/user-attachments/assets/d4049d8b-8779-43e5-8591-05a666bccd38)

---

## 시연 영상
![GIF 시연](https://github.com/user-attachments/assets/7a7d06e1-450f-49e7-9e7d-397df1789496)

