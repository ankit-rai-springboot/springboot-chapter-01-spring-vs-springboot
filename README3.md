# Actuator: Part of Spring Boot, Not Spring

### What is Spring Actuator?  
**Spring Actuator** is a module in Spring Boot that provides built-in production-ready features to monitor and manage your Spring Boot application. It offers valuable insights such as health checks, metrics, application status, and more.

### Key Features of Spring Actuator:
- **Health Checks**: Automatically checks the health of your application (e.g., database, disk space, etc.).
- **Metrics**: Provides detailed metrics on application performance, such as memory usage, request counts, etc.
- **Environment Information**: Displays environment details like system properties and environment variables.
- **Auditing**: Tracks events such as login attempts and API calls.
- **Application Info**: Exposes application-specific information like build version, uptime, etc.

### Why is Actuator Part of Spring Boot and Not Spring?
- **Spring Framework**: Primarily focuses on building Java applications (e.g., data access, messaging, and more). It doesn’t have built-in production-ready tools like health checks or metrics.
- **Spring Boot**: Extends Spring Framework by providing **Actuator** as part of the framework to make it easier to deploy, monitor, and maintain Spring-based applications in production.

### Example: Adding Actuator to Your Spring Boot Application
To enable Spring Boot Actuator, you can simply add the dependency in your `pom.xml` or `build.gradle`:

#### In `pom.xml`:
```xml
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-actuator</artifactId>
</dependency>
```

In application.properties:

You can configure endpoints for health checks and metrics:

- management.endpoints.web.exposure.include=health,info

### Conclusion:
Spring Actuator is part of Spring Boot and provides essential production-ready features that help you monitor and manage your applications, which Spring Framework does not offer out-of-the-box.

