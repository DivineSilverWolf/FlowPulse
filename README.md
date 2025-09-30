FlowPulse — SLA-ориентированный трекер задач

Коротко: сервис для управления заявками с жёсткими SLA, очередями и автоэскалацией.

## Стек
Java 17, Spring Boot 3, PostgreSQL, Flyway, JPA/Hibernate, (Kafka|RabbitMQ), Testcontainers, OpenAPI/Swagger. Опционально: React, ClickHouse.

## Быстрый старт
```bash
# 1) локально
./gradlew bootRun
./gradlew test

# 2) через Docker
docker compose up --build
