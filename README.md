# FitnessGuide
FitnessGuide is a microservices-based fitness backend application built using Spring Boot.
The project focuses on how different services work together in a distributed system and how secure communication is handled between them.

## About the Project
This project is based on a microservices architecture where multiple independent services handle different responsibilities like user management, activity tracking, and AI-based responses.
It also includes an AI service which connects with external APIs to generate fitness-related suggestions.

## Tech Stack

* Java + Spring Boot
* Spring Cloud (Gateway, Eureka, Config Server)
* Apache Kafka (for communication between services)
* Keycloak (authentication & authorization)
* PostgreSQL / MongoDB
* Docker (for containerization)
* Google Gemini API (AI integration)

## Architecture Overview

* API Gateway handles all incoming requests
* Services are registered using Eureka
* Config Server manages centralized configuration
* Kafka is used for event-based communication
* Keycloak secures APIs using OAuth2
* AI Service connects to external AI API for responses

## Services Included

* User Service
* Activity Service
* AI Service
* API Gateway
* Eureka Server
* Config Server

## What I Learned

* How microservices architecture works in real-world systems
* Service-to-service communication using Kafka
* Implementing authentication using Keycloak
* Managing multiple services using Spring Cloud
* Basics of integrating AI APIs into backend systems

-----

