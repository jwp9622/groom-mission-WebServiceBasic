# 미션 설명
## 주요 미션 기능
1) 그래들 프로젝트를 생성하고 스프링 컨텍스트에 새로운 빈 추가하기
2) CSS를 사용하여 웹 페이지 스타일링하기
3) HTML 기본 태그를 사용하여 웹 페이지 구조 만들기

## 기술 스택
Java 17
Spring boot 3.4.5
Mustache Template

## 디렉토리 구조
```
groom-mission-WebServiceBasic/
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com
│   │   │       └── example
│   │   │           └── SpringPremier
│   │   │               ├── SpringPremierApplication.java
│   │   │               ├── controller                      #웹 요청 처리용 컨트롤러 클래스
│   │   │               │   └── WebController.java
│   │   │               └── service                         #비즈니스 로직 처리용 서비스 클래스
│   │   │                   └── SampleService.java
│   │   └── resources
│   │       ├── application.properties
│   │       ├── static                                  #CSS, JS, 이미지 등 정적 리소스
│   │       │   ├── css
│   │       │   │   └── style.css
│   │       │   └── js
│   │       │       └── script.js
│   │       └── templates                               #Mustache 템플릿 파일
│   │           ├── index.mustache
│   │           ├── layout.mustache
│   │           └── fragments                           #재사용 가능한 머스테치 부분 템플릿
│   │               └── header.mustache
│   └── test                                            #JUnit 기반 테스트 코드
├── build.gradle
├── gradlew
├── gradlew.bat
├── settings.gradle
├── .gitignore
├── .gitattributes
├── README.md
├── 미션-웹기초.txt
```