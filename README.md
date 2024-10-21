# Kaouther-project-collection
This repository is a collection of 5 different repositories for a simple bank application

Welcome! Below is a collection of my projects showcasing my skills in web development, including React, and Spring Boot.

## 1. [Project One](https://github.com/kaouther24/accounts-management-ui)
**Description**: A React-based application to manage bank accounts.

**Tech Stack**: React

## 2. [Project Two](https://github.com/kaouther24/customersService)
**Description**: Microservice to manage customers.

**Tech Stack**: Spring Boot

## 3. [Project Three](https://github.com/kaouther24/accountsService)
**Description**: Microservice to manage customers' bank accounts.

**Tech Stack**: Spring Boot

## 4. [Project Four](https://github.com/kaouther24/transactionsService)
**Description**: Microservice to manage bank accounts' transactions.

**Tech Stack**: Spring Boot

## 5. [Project Five](https://github.com/kaouther24/financeBFF)
**Description**: Microservice Backend for frontend in between the microservices and the frontend.

**Tech Stack**: Spring Boot

## 5. Docker build
**Build docker image for every microservice**:

docker build -t customers-service:latest .
docker build -t transactions-service:latest .
docker build -t accounts-service:latest .
docker build -t financebff-service:latest .


**run docker compose where the docker compose file exists**:
docker-compose up

***Stop the services**
docker-compose down
