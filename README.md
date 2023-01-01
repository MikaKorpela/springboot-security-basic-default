# springboot-security-basic-default

Spring Boot basic authentication with default configuration.

## Add Dependencies

```xml
<dependency>
  <groupId>org.springframework.boot</groupId>
  <artifactId>spring-boot-starter-security</artifactId>
</dependency>
```

## Enable Web Security

```java
@SpringBootApplication
@EnableWebSecurity
public class Application {
  public static void main(String... args) {
    SpringApplication.run(Application.class, args);
  }
}
```

## Add Properties

```properties
spring.security.user.name=user1
spring.security.user.password=password1
```
