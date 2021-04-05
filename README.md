## spring-boot-logback-profile-based-config

Execute test class in dev or prod profile to get different detail levels of log information for a spring boot application using logback.

### Tech Stack
Java 11 <br/>
H2 Database Engine <br/>
spring boot <br/>
spring data jpa <br/>
hibernate <br/>
logback <br/>
maven <br/>
junit <br/>
<br/>

**´1-) Package spring boot application with dev profile to get detailed log during packaging´**

D:\DEV\spring-boot-logback-profile-based-config> **mvnw.cmd clean package -Dspring.profiles.active=dev**

DEBUG [main] org.springframework.boot.StartupInfoLogger: Running with Spring Boot v2.4.4, Spring v5.3.5<br/>
INFO  [main] org.springframework.boot.SpringApplication: The following profiles are active: dev<br/>
[INFO] ------------------------------------------------------------------------<br/>
[INFO] BUILD SUCCESS<br/>
[INFO] ------------------------------------------------------------------------<br/><br/><br/>


**2-) Package spring boot application with prod profile to get info level, limited log during packaging**

D:\DEV\spring-boot-logback-profile-based-config> **mvnw.cmd clean package -Dspring.profiles.active=prod**

INFO  [main] org.springframework.boot.SpringApplication: The following profiles are active: prod<br/>
[INFO] ------------------------------------------------------------------------<br/>
[INFO] BUILD SUCCESS<br/>
[INFO] ------------------------------------------------------------------------<br/>

