# Spring Cloud : Netflix-Eureka-Naming-Server
 
** Demonstrates Eureka Naming Server **
* TBD *

** Eureka Naming Server port : 8761**

 

**  http://localhost:8761/ **

```

//For Fiegn client
Step 1

@EnableEurekaServer
public class NetflixEurekaNamingServerApplication {

Step 2:
Application.properties
spring.application.name=netflix-eureka-naming-server
server.port=8761
eureka.client.register-with-eureka=false
eureka.client.fetch-registry=false


```


** References **

* [Spring properties reference](https://docs.spring.io/spring-boot/docs/current/reference/html/common-application-properties.html)
* [Spring Configurations](https://www.baeldung.com/properties-with-spring)
* [MD File Syntax](https://confluence.atlassian.com/bitbucketserver/markdown-syntax-guide-776639995.html)
* [In28mins Github Resource Config](https://github.com/in28minutes/spring-microservices/tree/master/03.microservices)
* [Install Github on local](https://git-scm.com/)
