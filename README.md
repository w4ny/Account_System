# [Spring Boot] Account_System
## 💵 Spring boot와 Java를 활용하여 Account(계좌 관리) 시스템을 만드는 1차 실습 프로젝트
>계좌 관련 API(계좌 생성, 해지, 확인) 및 거래 관련 API(잔액 사용, 사용 취소, 잔액 사용 취소) 서비스

## 💡공통 요구 사항(01_프로젝트 생성 및 요구사항 분석 내용)
- `Spring boot`와 `Java`를 활용합니다.
- DB는 `H2 DB(memory DB 모드)`를 활용합니다.
- DB를 접근하는 방법은 `Spring data jpa`를 활용합니다.
- `Embedded redis`를 활용합니다.
- API Request body와 Response Body는 `json 타입`으로 표현합니다.
- 각각의 API들은 각자의 요청과 응답 객체 구조를 갖습니다. (다만, 요청을 처리하다가 실패하는 경우의 응답은 공통된 구조를 갖도록 합니다.)
