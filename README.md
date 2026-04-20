# spring-boot-guardrails-api
Spring Boot 3 microservice with PostgreSQL + Redis implementing virality scoring, atomic guardrails, and scheduled notification batching.
# Backend Engineering Assignment - Core API & Guardrails

This project is a stateless Spring Boot 3.x microservice built with Java 17+, PostgreSQL, and Redis.  
It implements:
- REST APIs for posts, comments, and likes
- Real-time virality scoring in Redis
- Atomic guardrails using Redis (horizontal cap, vertical depth cap, cooldown cap)
- Smart notification throttling and scheduled batching with @Scheduled

## Tech Stack
- Java 17
- Spring Boot 3.x
- Spring Data JPA (PostgreSQL)
- Spring Data Redis
- Docker Compose (Postgres + Redis)

## Run locally
1. Start dependencies:
   ```bash
   docker compose up -d
