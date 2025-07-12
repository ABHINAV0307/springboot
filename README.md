# Spring Boot Application

A basic Spring Boot application with REST endpoints.

## Prerequisites

- Java 17 or higher
- Maven 3.6 or higher

## Running the Application

### Using Maven
```bash
mvn spring-boot:run
```

### Using Java
```bash
mvn clean package
java -jar target/springboot-0.0.1-SNAPSHOT.jar
```

## Available Endpoints

- `GET /` - Welcome message
- `GET /hello` - Hello message

## Testing

Run the tests using Maven:
```bash
mvn test
```

## Application Properties

The application runs on port 9090 by default. You can modify the configuration in `src/main/resources/application.properties`.

## Project Structure

```
src/
├── main/
│   ├── java/
│   │   └── com/example/springboot/
│   │       ├── SpringbootApplication.java
│   │       └── controller/
│   │           └── HelloController.java
│   └── resources/
│       └── application.properties
└── test/
    └── java/
        └── com/example/springboot/
            ├── SpringbootApplicationTests.java
            └── controller/
                └── HelloControllerTest.java
``` 