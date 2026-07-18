# Spring Boot Thymeleaf Demo

A server-rendered Java web application demonstrating the integration of Spring MVC and Thymeleaf templates.

## Technology stack

- Java 17
- Spring Boot 3.5
- Spring MVC
- Thymeleaf
- JUnit 5
- Maven

## Purpose

The project demonstrates the core building blocks of a traditional Spring web application:

- MVC controllers and request routing
- server-side HTML rendering
- model data passed from Java to Thymeleaf templates
- static resources and reusable page templates
- automated application-context testing

## Run locally

Requirements:

- JDK 17 or newer
- Maven 3.6.3 or newer

Linux or macOS:

```bash
./mvnw spring-boot:run
```

Windows:

```powershell
mvnw.cmd spring-boot:run
```

Open `http://localhost:8080` after the application starts.

## Build and test

```bash
./mvnw clean verify
```

## Project structure

```text
src/main/java                 Spring Boot application and controllers
src/main/resources/templates Thymeleaf HTML templates
src/main/resources/static    CSS, JavaScript, and other static assets
src/test/java                 automated tests
```

## Dependency maintenance

Dependabot checks Maven and GitHub Actions dependencies every week. GitHub Actions validates pull requests with a clean Java 17 build and test run.

## Development status

This repository is intended as a focused demonstration project. A production application would additionally require validation, security controls, structured error handling, accessibility checks, and broader integration testing.
