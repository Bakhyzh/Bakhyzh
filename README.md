 # Bakhyt

Java backend developer. I like the parts of backend work where correctness matters: money movement, concurrency, reliable events.

## Featured project

### [Esep API](https://github.com/Bakhyzh/esep-api)
Wallet and transfers service with a double-entry ledger.

- **Concurrency:** transfers lock accounts with `SELECT ... FOR UPDATE` in id order. A test with 100 parallel transfers proves no money is lost, and removing the ordering makes it fail with a deadlock.
- **Idempotency:** `Idempotency-Key` plus a request fingerprint. A retry returns the original result, the same key with a different body returns 422.
- **Reliable events:** Transactional Outbox into Kafka, idempotent consumer, retries and a dead letter topic.
- **SQL analytics:** window functions and a composite index took a report over 2M ledger rows from 125 ms to 0.24 ms.
- **Also:** JWT, Redis cache, Flyway, 105 tests on Testcontainers, Docker Compose, GitHub Actions.

Frontend: [esep-web](https://github.com/Bakhyzh/esep-web) (React, TypeScript).

## Stack

**Backend:** Java 21, Spring Boot, Spring Security, Spring Data JPA, Hibernate
**Data:** PostgreSQL, Flyway, Redis, Kafka
**Delivery:** Docker, GitHub Actions, Linux
**Testing:** JUnit 5, Mockito, Testcontainers

## Learning now

JVM internals and garbage collection, the Java memory model, concurrency utilities.

## Contact

[Telegram](https://t.me/bakhyzh) · [LinkedIn](https://www.linkedin.com/in/bakhyt-zharkynbek-891663335/) · zharqynbekov.b@gmail.com
