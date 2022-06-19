#### jooq
* [springboot jooq](https://github.com/ingduk2/springboot-jooq-practice)
  * 실무에서 jooq 적용을 위해 정리  

#### java concurrentHashmap Test
* [concurrentHashmap dto update Test](https://github.com/ingduk2/java-concurrenthashmap-test)
  * 업무 중 트래픽이 늘어남에 따라 kafka consumer 랙이 많이 쌓여서 concurrency 옵션(멀티쓰레드로) 변경하면서 기존 구조에서 많은 데드락과 데이터가 틀어지는 문제 발생.
  * 키가 중복인 데이터가 많아서 메모리에서 잠깐 쌓았다가 주기적으로 DB에 저장하는 방식으로 변경하려고 생각.
  * concurrentHashmap 쓰면서 synchronized 도 같이 쓰길래 궁금해서 뒤져보고, [concurrentHashmap, Atomic](http://blog.breakingthat.com/2019/04/04/java-collection-map-concurrenthashmap/) 을 사용하는 예제를 보면서 여러가지 테스트를 해봐야겠다고 생각해서 이것 저것 잡다하게 테스트해보게 됨.

#### Spring MDC Logging (작업중)
* [Spring MDC Logging](https://github.com/ingduk2/springboot-aop-mdc-logging)
  * context, transaction 단위로 로그를 추가하는 부분을 찾다가 slf4j MDC 를 알게 됨.
  * AOP, InterCeptor, Filtor 에서 나누어서 진행해보려는 중. 

#### ShortUrl (작업중)

#### practice
* [springboot docker](https://github.com/ingduk2/springboot-docker-jenkins)
  * docker 실습
* [springboot webservice](https://github.com/ingduk2/springboot-webservice)
  * 스프링 부트와 AWS로 혼자 구현하는 웹 서비스(이동욱님) 실습
* [springboot kafka](https://github.com/ingduk2/springboot-kafka)
  * springboot kafka 실습
* [springboot redis](https://github.com/ingduk2/springboot-redis)
  * springboot redis 실습

### 강의 수강
* 인프런
  * 김영한님 강의
    * 자바 ORM 표준 JPA 프로그래밍 - 기본편
    * 실전! 스프링 부트와 JPA 활용1 - 웹 애플리케이션 개발
    * 실전! 스프링 부트와 JPA 활용2 - API 개발과 성능 최적화
    * 실전! 스프링 데이터 JPA
    * 실전! Querydsl
    * 스프링 MVC 1편 - 백엔드 웹 개발 핵심 기술
    * 스프링 MVC 2편 - 백엔드 웹 개발 활용 기술 (수강중)
    * 스프링 핵심 원리 - 고급편
    * 스프링 DB 1편 - 데이터 접근 핵심 원리
    * 스프링 DB 2편 - 데이터 접근 활용 기술 (수강중)
  * 정수원님 강의
    * 스프링 배치 - Spring Boot 기반으로 개발하는 Spring Batch (수강중)
  * Dowon Lee 님 강의
    * Spring Cloud로 개발하는 마이크로서비스 애플리케이션(MSA) (수강중)
  * 최태현님 강의
    * 자바 개발자를 위한 코틀리 입문(Java to Kotlin Starter Guide) (수강중)  
* 패스트캠퍼스
  * 스프링러너의 스프링 아카데미
    * Spring을 활용한 유연한 백엔드 개발 트레이닝
    * 원리를 이해하는 Spring MVC/SpringBoot 실전 활용 가이드 (수강중)
  * TheRed
    * 4천만 MAU를 지탱하는 서비스 설계와 데이터 처리 기술 By 카카오페이지 기술전략이사 윤진석
    * 이규원의 현실 세상의 TDD : 안정감을 주는 코드 작성 방법  
    * 백발의 개발자를 꿈꾸며 : 코드리뷰, 레거시와 TDD by 백명석, 최범균
    * 25개 백엔드 개발 필수 현업 예제를 통해 마스터하는 JAVA STREAM
