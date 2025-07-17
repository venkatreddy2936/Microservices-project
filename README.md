# Quiz Microservices Project

This is a Spring Boot-based microservices application for managing quizzes and questions.

## 🔧 Microservices Included
- **question-service** – Manages quiz questions.
- **quiz-service** – Manages quizzes using question-service.
- **api-gateway** – Single entry point using Spring Cloud Gateway.
- **service-registry** – Eureka Server for service discovery.

## 🛠 Technologies Used
- Spring Boot
- Eureka
- Spring Cloud Gateway
- Maven
- Java 17+

## 🚀 Running the App
Start in this order:
1. service-registry
2. question-service
3. quiz-service
4. api-gateway

## 💡 How to Use
- Access via API Gateway:
  - `http://localhost:8765/question-service/...`
  - `http://localhost:8765/quiz-service/...`
