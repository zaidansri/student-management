# Student Management System

A basic single-application Spring Boot REST API for managing students.

## Technology

- Java 17
- Spring Boot 3.5.5
- Maven
- PostgreSQL

## Dependencies

- `spring-boot-starter-web`: Provides Spring MVC and an embedded server for building REST endpoints.
- `spring-boot-starter-data-jpa`: Provides Spring Data JPA and Hibernate for mapping Java objects to database tables and accessing data.
- `postgresql`: Provides the PostgreSQL JDBC driver so the application can connect to PostgreSQL at runtime.
- `spring-boot-starter-test`: Provides common testing tools for future unit and integration tests.

No security, JWT, Kafka, Docker, microservices, or Lombok dependencies are included.

## Package structure

```text
src
└── main
    └── java
        └── com.example.studentmanagement
            └── StudentManagementApplication.java
```

The application will later be organized into these simple packages:

```text
com.example.studentmanagement
├── controller    # REST endpoints
├── service       # Application logic
├── repository    # Database access
└── entity        # JPA entity classes
```

Only the application entry point has been created for now. The CRUD classes will be added in the following steps.

## Run the empty application

```bash
mvn spring-boot:run
```
