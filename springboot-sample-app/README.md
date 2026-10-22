# Spring Boot Sample App

This is a simple Java Spring Boot sample project created for demonstration purposes.

## Project name
`springboot-sample-app`

## Run locally
```bash
cd springboot-sample-app
./mvnw spring-boot:run
```

If you do not have the Maven wrapper, you can run:
```bash
mvn spring-boot:run
```

## Sample endpoint
- `GET /api/hello?name=World`

Example response:
```json
{ "message": "Hello, World!" }
```
