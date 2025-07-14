# microservices springboot springcloud docker kubernetes rest api
microservices project using Spring Boot, Spring Cloud, Docker, and Kubernetes  built alongside a 5 in 1 course.

# Spring Boot Microservices 5-in-1 Course

This repository contains all the code, examples, and configurations from the **Spring Boot Microservices 5-in-1** course covering:

- Spring Boot
- REST APIs
- Spring Cloud (Eureka, Config Server, API Gateway)
- Docker
- Kubernetes

## Project Structure

| Service           | Description                        |
|-------------------|------------------------------------|
| user-service       | User management microservice       |
| product-service    | Product catalog microservice       |
| order-service      | Order management microservice      |
| discovery-server   | Eureka for service registration    |
| config-server      | Externalized configuration server  |
| api-gateway        | API Gateway with routing/filtering |

##  Run
1. `docker-compose up` – Starts all services
2. `kubectl apply -f k8s/` – Deploy to Kubernetes

## Tech Stack
- Java 17 / 24
- Spring Boot 3.x
- Spring Cloud 2023.x
- Docker, Kubernetes
- MySQL/PostgreSQL
- Kafka, Redis (later modules)

