<img src="assets/profile-header.svg" alt="Bakhyt, Java backend developer" width="100%"/>

I like the parts of backend work where correctness matters: money movement, concurrency, reliable events.

## Featured project

### [Esep API](https://github.com/Bakhyzh/esep-api)
Wallet and transfers service with a double-entry ledger.

- **Concurrency:** accounts are locked with `SELECT ... FOR UPDATE` in id order. A test with 100 parallel transfers proves no money is lost, and removing the ordering makes it fail with a deadlock.
- **Idempotency:** `Idempotency-Key` plus a request fingerprint. A retry returns the original result.
- **Reliable events:** Transactional Outbox into Kafka, idempotent consumer, retries and a dead letter topic.
- **SQL analytics:** window functions and a composite index took a report over 2M ledger rows from 125 ms to 0.24 ms.
- **Also:** JWT, Redis cache, Flyway, 105 tests on Testcontainers, Docker Compose, GitHub Actions.

Frontend: [esep-web](https://github.com/Bakhyzh/esep-web)

## Stack

**Backend:** Java 21, Spring Boot, Spring Security, Spring Data JPA, Hibernate
**Data:** PostgreSQL, Flyway, Redis, Kafka
**Delivery:** Docker, GitHub Actions, Linux
**Testing:** JUnit 5, Mockito, Testcontainers

## Contact

[Telegram](https://t.me/bakhyzh) · [LinkedIn](https://www.linkedin.com/in/bakhyt-zharkynbek-891663335/) · zharqynbekov.b@gmail.com
<p align='center'>
   <a href="https://t.me/bakhyzh" target="_blank" rel="noopener noreferrer">
       <img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white"/>
   </a>

   <a href="https://www.linkedin.com/in/bakhyt-zharkynbek-891663335/" target="_blank" rel="noopener noreferrer">
       <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
   </a>

   <a href="https://www.instagram.com/bakhyzh/" target="_blank" rel="noopener noreferrer">
       <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/>
   </a>

   <a href="mailto:zharqynbekov.b@gmail.com" target="_blank" rel="noopener noreferrer">
       <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
   </a>
</p>
<picture> 
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg"
  />
  <img
    alt="github contribution grid snake animation"
    src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg"
  />
</picture>

<div align="left">
  
<img src="https://skillicons.dev/icons?i=java" height="40" alt="java logo"/> <img width="12"/> <img src="https://skillicons.dev/icons?i=spring" height="40" alt="spring logo"/> <img width="12"/> <img src="https://skillicons.dev/icons?i=postgres" height="40" alt="postgresql logo"/> <img width="12"/> <img src="https://skillicons.dev/icons?i=mysql" height="40" alt="mysql logo"/> <img width="12"/> <img src="https://skillicons.dev/icons?i=docker" height="40" alt="docker logo"/> <img width="12"/> <img src="https://skillicons.dev/icons?i=kafka" height="40" alt="kafka logo"/> <img width="12"/> <img src="https://skillicons.dev/icons?i=redis" height="40" alt="redis logo"/> <img width="12"/> <img src="https://skillicons.dev/icons?i=git" height="40" alt="git logo"/> <img width="12"/> <img src="https://skillicons.dev/icons?i=github" height="40" alt="github logo"/> <img width="12"/> <img src="https://skillicons.dev/icons?i=idea" height="40" alt="idea logo"/> <img width="12"/> <img src="https://skillicons.dev/icons?i=linux" height="40" alt="linux logo"/> <img width="12"/> <img src="https://skillicons.dev/icons?i=nginx" height="40" alt="nginx logo"/><img width="12"/> <img src="https://skillicons.dev/icons?i=kubernetes" height="40" alt="kubernetes logo"/> <img width="12"/> <img src="https://skillicons.dev/icons?i=hibernate" height="40" alt="hibernate logo"/>
<img width="12"/>



</div>

<br>
<div >
🛠 Technical Skills

- **Backend:** Java, Spring Boot, Spring MVC, Spring Security
- **Database:** PostgreSQL, MySQL, Hibernate, JPA
- **Messaging & Caching:** Apache Kafka, Redis
- **Architecture:** REST API, Multi Module Architecture, Microservices Basics
- **Containerization:** Docker, Docker Compose
- **Security:** JWT Authentication, Role Based Authorization
- **Networking:** HTTP, TCP/IP, Docker Networking
- **Tools:** Git, GitHub, IntelliJ IDEA, Linux
- **Build Tools:** Maven, Gradle
- **Testing:** JUnit, Mockito
   
</div>

<br>
<div align="center">
    <img src="https://komarev.com/ghpvc/?username=Bakhyzh&color=DE002D" alt="Profile Views">
</div>
