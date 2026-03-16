# OpenEx – Simulated Crypto Exchange

## Overview

**OpenEx** is a lightweight simulated cryptocurrency exchange built to demonstrate modern backend development using **Java and Spring Boot**.

The platform simulates **BTC/USD trading**, user wallets, an order book, and a simplified matching engine. It exposes both **REST APIs and WebSocket streams** for trading operations and real-time market updates.

This project is part of **Month 5: Java Frameworks & Web Application Development**, focusing on building scalable backend services and production-style system architecture using open-source tools.

---

# Project Goals

The main objectives of this project are:

* Learn **Java and Spring Boot** for backend service development.
* Build **REST APIs and WebSocket APIs** for real-time trading systems.
* Implement a simplified **matching engine and ledger** for simulated BTC trades.
* Emphasize **testability, observability, and debugging practices** used in production systems.
* Use **containerized infrastructure** so the system can run locally or in CI pipelines.

---

# Features

The OpenEx platform supports the following core features:

* User wallet management with simulated balances
* BTC/USD trading using:

  * Market orders
  * Limit orders
* Order book management
* Basic trade matching engine
* Real-time market data streaming via WebSocket
* REST APIs for trading and wallet operations
* Simulated market data feed
* React dashboard for visualization (future phase)

---

# Technology Stack

## Development Environment

* IntelliJ IDEA Community Edition

## Backend

* Java 17+
* Spring Boot
* Spring Web
* Spring Data JPA
* Spring WebSocket
* Spring Security (optional)

## Persistence

* PostgreSQL (primary database)

## Caching

* Redis (order caching and rate limiting)

## Matching Engine

* Java in-process service
* Optional Kafka event streaming

## Frontend

* React (Create React App or Vite)
* Chart.js (order book and price charts)

## Containerization

* Docker
* Docker Compose

## Observability

* Prometheus
* Grafana
* OpenTelemetry (distributed tracing)

## Testing

* JUnit 5
* Mockito
* Testcontainers (Postgres and Redis)

## Build Tools

* Maven or Gradle

## Logging

* SLF4J
* Logback

## CI/CD

* GitHub Actions

## Optional Tools

* WireMock for external API mocking

---

# Week 1 – Backend Foundations & API Design

## Focus

REST API development and WebSocket streaming using Spring Boot.

## Activities

During Week 1 the following components are implemented:

* User Wallet service module
* Trading service module
* REST APIs for wallet and order management
* WebSocket APIs for real-time market updates
* PostgreSQL database integration
* Redis setup for caching

---

# Deliverables

The Week 1 deliverables include:

* Functional backend REST APIs
* WebSocket market data streaming
* Database schema and **ER diagram**
* Initial project structure for the exchange backend

---

# Project Structure

```
openex-crypto-exchange
│
├── openex-backend
│
├── docs
│   └── ER-Diagram
│
├── docker
│
├── .github
│   └── workflows
│
├── docker-compose.yml
└── README.md
```

---



# Author

**CodeForge**

