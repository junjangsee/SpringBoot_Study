# 스프링 부트 프로젝트 구조

## 권장하는 SpringBootApplication 위치 및 구조
> SpringBootApplication 설정 파일이 있는 위치 부터 `@ComponentScan` 을 해서 Bean으로 등록함
https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/#using-boot-structuring-your-code

<br/>

![structer](/images/structer1.png)
![structer](/images/structer2.png) 위에 나와있는 최상위 패키지인 com부터 myapplication 패키지까지 포함된 파일들만 Bean으로 등록한다.

## 메이븐 기본 프로젝트 구조와 동일
- 소스 코드 (src\main\java)
- 소스 리소스 (src\main\resource)
- 테스트 코드 (src\test\java)
- 테스트 리소스 (src\test\resource)

## 메인 애플리케이션 위치
- 기본패키지