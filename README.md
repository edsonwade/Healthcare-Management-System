# 🏥 Healthcare Management System

[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://www.linux.org/)
[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.java.com/)
[![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellij-idea&logoColor=white)](https://www.jetbrains.com/idea/)
[![SonarLint](https://img.shields.io/badge/SonarLint-CB2029?style=for-the-badge&logo=sonarlint&logoColor=white)](https://www.sonarlint.org/)
[![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)](https://www.notion.so/)
[![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=Hibernate&logoColor=white)](https://hibernate.org/)
[![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=Spring-Security&logoColor=white)](https://spring.io/projects/spring-security)
[![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=Jenkins&logoColor=white)](https://www.jenkins.io/)
[![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=Jira&logoColor=white)](https://www.atlassian.com/software/jira)

## Introduction
The Healthcare Management System is a microservices-based application designed to streamline various healthcare-related tasks such as patient management, appointment scheduling, medical records management, billing, and reporting. This README provides an overview of the project structure, services, and setup instructions.

## 🎯 Objectives
The main objectives of this project are:
- Implement a scalable and maintainable healthcare system using microservices architecture.
- Utilize various technologies and concepts such as Spring Boot, Spring Cloud, Docker, Docker Compose, Kafka, Prometheus, and more.
- Ensure security using Spring Security for authentication and authorization.
- Facilitate CI/CD pipelines with Jenkins Pipeline for automated build, test, and deployment.
- Provide thorough documentation and instructions for setting up and running the project.

## 📦 Microservices
The system consists of the following microservices:

1. **Patient Service**: Manages patient registration, profile management, and medical history tracking.
2. **Doctor Service**: Handles doctor registration, profile management, and schedule management.
3. **Appointment Service**: Manages appointment scheduling with conflict resolution and notification functionalities.
4. **Medical Records Service**: Deals with medical record creation, retrieval, and update functionalities.
5. **Billing Service**: Handles billing generation, invoicing, and payment tracking functionalities.
6. **Reporting Service**: Provides reporting functionalities for generating insights into patient demographics, appointment trends, and revenue analysis.

## 📚 Shared Libraries
The project includes the following shared libraries:

1. **Common Library**: Contains shared code, models, and utilities used across multiple services.
2. **Security Library**: Contains security-related functionality such as authentication and authorization.

## 💻 Technologies and Concepts Used
- ⚙️ Spring Boot
- ☁️ Spring Cloud (Gateway API, Load Balancing, Cache, Health, Metrics)
- 🔒 Spring Security
- 🛠️ Docker, Dockerfile, Docker Compose
- 🛤️ Flyway Migration, JPA, PostgreSQL, MongoDB
- 📘 OpenAPI (Swagger), HATEOAS Rest
- 📨 Apache Kafka, Email, Prometheus, Grafana, Testcontainers (Unit Test, Functional Test, Integration Test with Mockito)
- 🚀 CI/CD with Jenkins Pipeline
- 🛠️ Dev Configuration and Production Environment Setup

## 📊 Entity Model
The entity model includes entities such as:
- Patient
- Doctor
- Appointment
- MedicalRecord
- Billing
- Report

Each microservice manages its related entities and exposes APIs for CRUD operations and business-specific functionality.

## 🔧 Setup and Configuration
1. Clone the repository.
2. Install Docker and Docker Compose.
3. Navigate to the project directory.
4. Run `docker-compose up` to build and start the microservices and their dependencies.
5. Access the individual microservices' endpoints as per their documentation for further configuration and usage.

## 🤝 Contributing
If you'd like to contribute to this project, please follow these guidelines:
- Fork the repository.
- Create a new branch for your feature or fix.
- Make your changes and commit them.
- Push to your fork and submit a pull request.

## 📝 License
This project is licensed under the MIT License.
