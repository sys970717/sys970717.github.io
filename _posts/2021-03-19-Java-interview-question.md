1. 스프링
    - 스프링 어노테이션
```java
   		 @Controller
   		 @Service
   		 @Repository : DB Exception을 DataAcessException으로 변환한다.
   		 
   		 @AutoWired(required=false) , default true
		 @Qualifier
   		 @Required

   		 @Value
   		 @Bean
   		 @Configuration

   		 @PostConstruct : 의존하는 객체를 설정한 이후에 초기화 작업을 수행하기 위해 사용
   		 @PreDestory : 컨테이너에서 객체를 제거하기 전에 해야할 작업을 수행하기 위해 사용

   		 @Inject
```


    - 스프링 5 버전에 새로 추가된 기능

    Spring 5 Major Changes

		Java 9 Compatible
		JaveEE 8 Support
		HTTP/2 Support
		Reactive: WebFlux, Router Functions
		Functional Bean Configuration
		JUnit 5
		Portlet Deprecated

	Baseline Changes - versions

		JDK 8+
		Servlet 3.1+
		JMS 2.0
		JPA 2.1
		JavaEE 7+


    - aop에 대해서 설명 하시오

   
    - DI, IoC에 대해서 설명 하시오.

    	http://wiki.sys4u.co.kr/pages/viewpage.action?pageId=7767258


    - 스프링 구동 원리

    - 디자인 패턴(스프링)


2. IO vs NIO의 차이점

3. 함수형 프로그래밍이란?

4. Netty 프레임워크 설계?

5. Push Server 설계?
  1000만건의 push 메시지를 보낼때?

6. Java Collection , stream
  - http://www.libqa.com/wiki/99
  - http://wiki.sys4u.co.kr/pages/viewpage.action?pageId=7766426

7. React 장점

8. Redis 장점 -> 설계는?

9. 객체 지향 언어?

10. Java 8 Optional, 요점이 뭐야?	
		- NullPointerException 을 방지하기 위해 Java8에 Optional 클래스가 추가되었습니다.

11. RESTful API
		- http://bcho.tistory.com/953
		- https://spoqa.github.io/2013/06/11/more-restful-interface.html