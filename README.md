# spring-boot-logback-profile-based-config

**1-) Run spring boot application with dev profile to get detailed log**

D:\DEV\spring-boot-logback-profile-based-config> **mvnw.cmd clean package -Dspring.profiles.active=dev**

DEBUG [main] org.springframework.boot.StartupInfoLogger: Running with Spring Boot v2.4.4, Spring v5.3.5<br/>
INFO  [main] org.springframework.boot.SpringApplication: The following profiles are active: dev<br/>
[INFO] ------------------------------------------------------------------------<br/>
[INFO] BUILD SUCCESS<br/>
[INFO] ------------------------------------------------------------------------<br/><br/><br/>


**2-) Run spring boot application with prod profile to get info level, limited log**

D:\DEV\spring-boot-logback-profile-based-config> **mvnw.cmd clean package -Dspring.profiles.active=prod**

INFO  [main] org.springframework.boot.SpringApplication: The following profiles are active: prod<br/>
[INFO] ------------------------------------------------------------------------<br/>
[INFO] BUILD SUCCESS<br/>
[INFO] ------------------------------------------------------------------------<br/>

