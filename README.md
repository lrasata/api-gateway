# api-gateway
Getting started with Microservices : Exploring Routes with Spring Cloud Gateway.

Instead of using the uri of each services, we can call the uri of api-gateway and configure it to redirect to the right service.
Instead of calling localhost:8000/myservices1 and localhost:8001/myservices2 of some services, we can call localhost:8765/myservices1 and locahost:8765/myservices2 where 8765 is the port of Api Gateway.

Project originally generated with https://start.spring.io/ with dependencies :
- Spring Boot Devtools
- Spring Boot Actuator
- Eureka Discovery Client
- Gateway

Application configurations are set up in ```application.properties```


![Load-balancing](https://user-images.githubusercontent.com/63764427/155869388-ce5a5cd6-f926-46e8-8998-92db5fd10901.png)

source : https://courses.in28minutes.com/p/master-microservices-with-spring-boot-and-spring-cloud
