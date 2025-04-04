# Spring Boot Banner

This repository contains a custom ASCII banner for use with Spring Boot applications.

## Usage

Place the `banner.txt` file in the `src/main/resources` directory of your Spring Boot project. It will automatically be displayed in the console on application startup.

## Configuration

To display application-specific values like name and version, you need to define the following properties in your configuration files:

### `application.yml`

```yaml
spring:
  app:
    name: your-app-name
    version: 1.0.0
```

### `application.properties`

```properties
spring.app.name=your-app-name
spring.app.version=1.0.0
```
