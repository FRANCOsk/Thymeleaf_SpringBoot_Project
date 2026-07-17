# Thymeleaf Spring Boot Demo

A small server-rendered Java web application demonstrating how Spring MVC controllers, Thymeleaf templates, and static assets work together in Spring Boot.

## Technology stack

- Java 11+
- Spring Boot 2.6
- Spring MVC
- Thymeleaf
- Maven

## Prerequisites

- JDK 11 or newer
- Maven 3.8 or newer, or the included Maven Wrapper when available

## Run locally

```bash
mvn spring-boot:run
```

Then open `http://localhost:8080`.

## Build and test

```bash
mvn clean verify
```

The `verify` phase compiles the application, runs the automated tests, and creates the executable Spring Boot JAR under `target/`.

## Project structure

```text
src/main/java        Application code and MVC controllers
src/main/resources   Thymeleaf templates, static assets, and configuration
src/test/java        Automated tests
```

## Continuous integration

GitHub Actions validates each pull request and every push to `main` by running the Maven verification lifecycle on a supported Java runtime.

## Notes

This repository is intended as a learning and demonstration project. Before production use, review configuration, error handling, dependency versions, observability, and security requirements for the target environment.
