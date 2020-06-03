# springboot with querydsl, swagger
Spring Boot에 Swagger, JPA, QueryDSL을 적용한 기본 프로젝트   

### 목적
- 실무 프로젝트의 경험을 바탕으로, 간단한 WAS를 만들수 있는 Architecture를 만들어본다.
- 기본적인 Spring Boot의 설정을 통해 간단한 WAS를 만든다.
- Swagger-ui 를 활용하여 req/res를 쉽게 테스트 할 수 있다.
- JPA를 통해 기본적인 DB Transaction을 할 수 있다.
- QueryDSL을 사용하여 복잡한 Join 등을 처리할 수 있다.
<hr/>

### 요약
- 시작은 start.spring.io 에서, 아래 패키지를 포함하여 프로젝트를 생성한다.
  + Spring Web
  + Spring Data JPA
  + Spring Data JDBC
  + Lombok
- Boot에서는 @Controller 대신 @RestController를 활용하여 RESTful API를 만들 수 있다.
- JPA는 간단한 것 위주로 사용하자.
  + 자신이 있으면, 연관 관계 매핑을 적극 활용하자.
- QueryDSL는 java로 쿼리를 짤 수 있게 도와주는 도구이다.
