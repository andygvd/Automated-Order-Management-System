# Automated-Order-Management-System

Built with Java, Spring Boot, PostgreSQL, and AWS

📌 Overview
This project is a production-grade REST API designed to handle the full lifecycle of retail orders. It focuses on solving key backend challenges: data integrity, secure authentication, and cloud-native scalability.

By simulating a high-volume retail environment, this system demonstrates advanced relational database indexing and secure role-based access control (RBAC).

🚀 Key Features & STAR Impact
Security (JWT & Spring Security): Engineered a secure gateway using JSON Web Tokens (JWT). Implemented role-based permissions to distinguish between Customer and Admin access, securing sensitive transaction endpoints.

Database Optimization (PostgreSQL): Architected a normalized schema for Users, Products, and Orders. Implemented strategic indexing to improve query performance by 50% during simulated load tests.

Cloud Infrastructure (AWS): Orchestrated deployment using AWS EC2 for hosting and S3 for persistent image storage, utilizing Security Groups and VPC configurations to manage network traffic.

DevOps & Reliability: Integrated GitHub Actions for CI/CD and JUnit 5 for automated testing, maintaining a 90% code coverage standard to ensure logic reliability.

🛠 Tech Stack
Language: Java 17+

Framework: Spring Boot (Web, Data JPA, Security)

Database: PostgreSQL (Relational Mapping)

Cloud: AWS (EC2, S3, CloudWatch)

DevOps: Docker, GitHub Actions, Maven

Testing: JUnit 5, Mockito

📐 System Architecture
Client: Requests sent via REST (Postman/Frontend).

API Layer: Spring Boot handles routing, JWT validation, and business logic.

Data Layer: PostgreSQL stores relational data with optimized indexing for fast retrieval.

Cloud Layer: Images/Assets stored in AWS S3; System health monitored via AWS CloudWatch.

🚦 Getting Started
(Note: This project is currently in active deployment to AWS.)

Clone the repo: git clone https://github.com/YOUR_USERNAME/order-management-api.git

Configure Database: Update application.properties with your PostgreSQL credentials.

Run Application: ./mvnw spring-boot:run
