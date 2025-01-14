# Build Microservices with Spring Boot, Docker, Kubernetes

Create enterprise and production ready Microservices with Spring, Spring Cloud, Docker and Kubernetes.

# Important Links
- Spring Boot - https://spring.io/projects/spring-boot
- Create SpringBoot project - https://start.spring.io
- DTO pattern blog - https://martinfowler.com/eaaCatalog/dataTransferObject.html
- Model Mapper - http://modelmapper.org/
- Map Struct - https://mapstruct.org/
- Spring Doc - https://springdoc.org/
- Open API - https://www.openapis.org/
- Lucidchart Blog - https://www.lucidchart.com/blog/ddd-event-storming
- Docker website - https://www.docker.com
- Docker hub website - https://hub.docker.com
- Buildpacks website - https://buildpacks.io
- Google Jib website - https://github.com/GoogleContainerTools/jib
- Docker compose website - https://docs.docker.com/compose/
- Twelve-Factor methodology - https://12factor.net
- Beyond the Twelve-Factor App book - https://www.oreilly.com/library/view/beyond-the-twelve-factor/9781492042631/
- Spring Cloud website - https://spring.io/projects/spring-cloud
- Spring Cloud Config website - https://spring.io/projects/spring-cloud-config
- Spring Cloud Bus website - https://spring.io/projects/spring-cloud-bus
- RabbitMQ website - https://www.rabbitmq.com
- Hookdeck website- https://hookdeck.com


## Maven Commands used

|     Maven Command       |     Description          |
| ------------- | ------------- |
| "mvn clean install -Dmaven.test.skip=true" | To generate a jar inside target folder |
| "mvn spring-boot:run" | To start a springboot maven project |
| "mvn spring-boot:build-image" | To generate a docker image using Buildpacks. No need of Dockerfile |
| "mvn compile jib:dockerBuild" | To generate a docker image using Google Jib. No need of Dockerfile |
