# PROJECT_STAYWITHME | 스테이위드미

스테이위드미 UI/UX 메인 서비스

1. 각 숙소에 대한 정보를 접근하기 위한, Feed list 형식을 제공합니다.
2. 정보의 접근성을위해, pagination을 통해 list로 분할하여 보여줍니다.
3. 각 숙소에 대한 DetailPage 내에서 숙소에 대한 정보 및 이미지를 확인할 수 있으며 Info-Extension을 Carousel-Slider를 통해 보여줍니다.

- 사이트 링크 : 

#TEAM_STAYWITHME | 스테이위드미

## 팀원

- Front-end: 최병현, 지연비 , 신유진
- Back-end: 권은경, 이찬규

## 개발 기간

- 기간: 2021년 11월 15일 ~ 2021년 11월 26일(12일간)

## 적용 기술

- Front-end: React(Funiction-Component)\_reactr-router-dom(V6), 
Styled-Components, JavaScript(ES6)
- Back-end: Django, Python, MySQL, jwt, bcrypt, AWS(EC2, RDS)
- 협업툴: Trello, Slack, Notion, Github, dbdiagram, postman

## 구현 기능 및 개인 역할

> Login/Register, PaymentPage 

[Login/Register]
- 카카오 Open API를 이용한 소셜로그인 기능 구현
- 로그인시 백엔드에서 발행한 Token을 Local storage에 저장

[PaymentPage]
- useSearchParams(), fetch()를 사용하여 이전 페이지에서 선택한 정보들을 불러오는 기능 구현
- 체크박스 전체선택/전체해제 구현

## 소감 및 후기

시간의 한계로 인해 마지막에 결제페이지의 data를 백엔드로 post하는 로직을 완성하지 못한 부분이 아쉽다.
다음 프로젝트에서는 결제페이지와 마이페이지를 맡아서 페이지 간의 데이터 전송과 프론트, 백엔드 사이의 데이터 송수신에 대해 좀 더 알아보고 싶다.

## 레퍼런스

- 이 프로젝트는 <u>[스테이폴리오](https://www.stayfolio.com/)으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
