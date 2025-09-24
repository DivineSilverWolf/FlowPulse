FlowPulse — SLA-ориентированный трекер задач

Коротко: сервис для управления заявками с жёсткими SLA, очередями и автоэскалацией.

## Стек
Java 21, Spring Boot 3, PostgreSQL, Flyway, JPA/Hibernate, (Kafka|RabbitMQ), Testcontainers, OpenAPI/Swagger. Опционально: React, ClickHouse.

## Быстрый старт
```bash
# 1) локально
./mvnw spring-boot:run

# 2) через Docker
docker compose up --build
