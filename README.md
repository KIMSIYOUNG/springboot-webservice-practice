# Spring boot + AWS 를 사용한 웹 어플리케이션

## 사용 기술

- IDE : Intellij
- Build tool : Gradle
- Test : Junit
- Java, Spring boot, Spring Data Jpa, AWS(EC2, RDS, S3)
- Spring security , Oauth2

## 구현 기능 및 학습 내용

- 간단한 게시판 기능 (Api + 화면)

    - 등록
        - [x] Api & Test Code
        - Mustache 를 사용한 화면 구성
    - 수정
        - [x] Api & Test Code
        - Mustache 를 사용한 화면 구성
    - 조회
        - [x] Api & Test Code
        - Mustache 를 사용한 화면 구성
    - 삭제
        - [x] Api & Test Code
        - Mustache 를 사용한 화면 구성
    - [x] Jpa Auditing을 통한 날짜 관리

- 소셜 로그인 
    
    - Spring security + Oauth2
    - 구글 로그인 연동
    - 네이버 로그인 연동

- 배포
    
    - AWS EC2 서버 배포
    - Travis CI 배포 자동화
    - 무중단 배포    