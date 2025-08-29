📊 Expense Tracker – Microservices Architecture
🚀 Overview

Expense Tracker is a backend-focused application designed with a microservices architecture. It allows users to securely manage expenses, with separate services for user management, authentication, expense tracking, and data sync.

The project demonstrates:

Spring Boot microservices with REST APIs

JWT-based authentication & authorization

Asynchronous communication with Kafka

Kong API Gateway for routing & rate limiting

Docker & Docker Compose for containerized deployment

🛠️ Tech Stack

Backend: Spring Boot, Hibernate, MySQL

Messaging: Apache Kafka

API Gateway: Kong (DB-less mode, with rate limiting)

Containerization: Docker, Docker Compose

Database: MySQL

📂 Microservices

User Service → handles user registration & profile

Auth Service → JWT login & token management

Expense Service → CRUD operations for expenses

DS Service → data sync / analytics layer

Kafka → enables async communication between services
 

🔐 Security

JWT-based authentication & role-based authorization

API Gateway enforces routing & rate limiting

📌 Future Work

Frontend with React / React Native

Deployment to AWS (ECS / EC2 / Elastic Beanstalk)

CI/CD pipeline with GitHub Actions

👤 Author

Jeevan Kurian

[Email](jeevan2000kurian@gmail.com)
[Linkedin](https://www.linkedin.com/in/jeevan-kurian-71b806224/)
