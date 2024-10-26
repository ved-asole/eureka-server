# CrimsonSky - Eureka Server Microservice

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=ved-asole_api-gateway&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=ved-asole_api-gateway)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=ved-asole_api-gateway&metric=sqale_rating)](https://sonarcloud.io/summary/new_code?id=ved-asole_api-gateway)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=ved-asole_api-gateway&metric=reliability_rating)](https://sonarcloud.io/summary/new_code?id=ved-asole_api-gateway)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=ved-asole_api-gateway&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=ved-asole_api-gateway)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=ved-asole_api-gateway&metric=vulnerabilities)](https://sonarcloud.io/summary/new_code?id=ved-asole_api-gateway)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=ved-asole_api-gateway&metric=bugs)](https://sonarcloud.io/summary/new_code?id=ved-asole_api-gateway)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=ved-asole_api-gateway&metric=code_smells)](https://sonarcloud.io/summary/new_code?id=ved-asole_api-gateway)
[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=ved-asole_api-gateway&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=ved-asole_api-gateway)

## Live Link / Demo Link: 🔗
Access the flight service at **[localhost:8761](http://localhost:8761)**

## Table of Contents: 📑

- [About The Service](#about-the-service-)
- [Technologies](#technologies-%EF%B8%8F)
- [Setup](#setup-)
- [Approach](#approach-)
- [Status](#status-)
- [License](#license-%EF%B8%8F)

## About the Service: 📚
The **Eureka Server Microservice** is the heart of the CrimsonSky flight booking system. It manages naming and discovery of all the microservices across the application. The service is built with **Spring Boot** and uses **Spring Cloud Netflix Eureka** for service registry, naming and discovery, **Spring Cloud Config** for configuration management, ensuring efficient microservice communication.

## Technologies: ☕️

- Java
- Spring Boot
- Spring Cloud Netflix Eureka
- Spring Cloud Config
- Junit and Mockito

## Setup: 💻

- **Install Java 21 :**
    - Download and install **[Java 21](https://www.oracle.com/in/java/technologies/downloads/#java21)**
    - Set up the **JAVA_HOME** environment variable.


- **Install Maven:**
    - Download and install **[Maven](https://maven.apache.org/download.cgi)**
    - Add the **bin** directory to the **PATH** environment variable.

**Available Scripts:**

In the project directory, you can run:

- #### `mvn install`
  Installs all necessary dependencies.

- #### `mvn spring-boot:run`
  Runs the api-gateway service.\
  Open [http://localhost:8761](http://localhost:8761) to access it.

# Approach: 🚶
This service is part of the **CrimsonSky** microservices ecosystem, focusing service registry, naming and discovery using **Netflix Eureka** for optimal performance and efficient service communication.

# Status: 📶
Service under development 🛠️

# License: ©️
MIT License (**[Check Here](LICENSE)**)