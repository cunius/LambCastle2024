# LambCastle2024

### I'm Selling Lamb 🐑

### application.properties
```shell
spring.application.name=****
server.port=****
spring.jpa.open-in-view=true

#DB
spring.jpa.hibernate.ddl-auto=create
spring.jpa.defer-datasource-initialization=true
spring.datasource.url=jdbc:mysql://localhost:3306/mydatabase
spring.datasource.username=****
spring.datasource.password=****
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.jpa.show-sql:true

#Cache
spring.thymeleaf.cache=false

#CSS
spring.mvc.static-path-pattern=/resources/**
spring.resources.static-locations=classpath:/static/

#Activate Debug log
```
### compose.yaml
```shell
services:
  mysql:
    image: 'mysql:latest'
    environment:
      - 'MYSQL_DATABASE=mydatabase'
      - 'MYSQL_PASSWORD=****'
      - 'MYSQL_ROOT_PASSWORD=****'
      - 'MYSQL_USER=myuser'
    ports:
      - '3306:3306'
```
### Dependencies
```shell
Spring Boot DevTools
Lombok
Docker Compose Support
Spring Web
Thymeleaf
Spring Security
OAuth2 Client
JDBC API
Spring Data JPA
MySQL Driver
Validation
CycolneDX SBOM support
```
