<div align="center">

```
██████████████████████████████████████████
   NILESH DAS
   JAVA BACKEND ENGINEER
██████████████████████████████████████████
```

</div>

<div align="center">

`PORTFOLIO` → [nilesh-das.vercel.app](https://nilesh-das.vercel.app/)&nbsp;&nbsp;|&nbsp;&nbsp;`LINKEDIN` → [nileshdasneel](https://www.linkedin.com/in/nileshdasneel)&nbsp;&nbsp;|&nbsp;&nbsp;`MAIL` → [dasnilesh832@gmail.com](mailto:dasnilesh832@gmail.com)

</div>

<br>

```
────────────────────────────────────────────
 01 / ABOUT
────────────────────────────────────────────
```

I build backends that hold up under load — designing for failure with
circuit breakers and rate limiters, tuning caching layers instead of
just adding them, reasoning about consistency before reaching for a
queue. This GitHub is the raw repository: source code, architectural
experiments, and the internals I've actually gone through.

<br>

```
────────────────────────────────────────────
 02 / STACK
────────────────────────────────────────────
```

```
LANGUAGES        JAVA 21 · C · JAVASCRIPT · SQL · HTML/CSS
BACKEND          SPRING BOOT · SPRING DATA JPA · SPRING SECURITY
                 HIBERNATE · JDBC · NODE.JS
ARCHITECTURE     MICROSERVICES · EVENT-DRIVEN DESIGN
                 RESILIENCE4J — CIRCUIT BREAKER / RATE LIMITER
MESSAGING        APACHE KAFKA
CACHING          REDIS
FRONTEND         REACT · CONTEXT API
DATABASES        MYSQL · MONGODB
DEVOPS           DOCKER · JENKINS · LINUX · AWS S3
DEPLOY           VERCEL · NETLIFY · RENDER
TOOLING          MAVEN · GIT · POSTMAN · JUNIT · LOG4J
```

<br>

```
────────────────────────────────────────────
 03 / PROJECTS
────────────────────────────────────────────
```

**SNAPOS — DIGITAL BUSINESS CARD PLATFORM**
`REACT` `SPRING BOOT`
* Full-stack app letting users create custom-URL digital profiles with QR-code sharing, PIN-protected access, and self-serve account recovery.
* Built a polished interaction layer from scratch — animated PIN entry, expanding-circle button transitions, scroll-triggered reveals — no UI library shortcuts.
* Designed the auth/recovery flow to avoid the "locked out forever" trap common in PIN-based systems.

**CACHING LAYER — SPRING BOOT + REDIS**
`SPRING BOOT` `REDIS` `MYSQL`
* Built a caching layer over a CRUD service, choosing cache-aside vs. write-through per endpoint based on read/write ratio and staleness tolerance.
* Used SpEL-based dynamic cache keys and `@Transactional`-aware eviction to keep cache and DB consistent on writes and deletes.
* Backed by Upstash-hosted Redis, cutting redundant DB hits on hot read paths.

**BOOKING API — IRCTC-STYLE, WITH CI/CD**
`SPRING BOOT` `DOCKER` `JENKINS`
* Designed a REST API with centralized error handling (`@RestControllerAdvice`, custom exception hierarchy) instead of scattered try-catch, so every failure mode returns a consistent, client-usable response.
* Containerized with Docker and shipped a declarative Jenkins pipeline for automated builds — resolved cross-platform build issues along the way (Windows/WSL2 case-sensitivity gotchas).

**EVENT PIPELINE — KAFKA, DOCKER**
`APACHE KAFKA` `DOCKER`
* Stood up a local multi-broker Kafka cluster to work through partitioning strategy, sticky partitioner behavior, and keyed message routing for ordering guarantees.
* Modeled consumer group semantics hands-on — including groupless consumers behaving as pub-sub — to reason correctly about scaling consumers without losing message order.

<br>

```
────────────────────────────────────────────
 04 / STATS
────────────────────────────────────────────
```

`SMART INDIA HACKATHON 2024` — Participant
`LEETCODE / HACKERRANK` — 1000+ solution views

<br>

```
────────────────────────────────────────────
 05 / ANALYTICS
────────────────────────────────────────────
```

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Nilesh123-45&theme=transparent&hide_border=true&title_color=000000&text_color=000000&icon_color=000000" height="165" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Nilesh123-45&theme=transparent&hide_border=true&title_color=000000&text_color=000000&layout=compact" height="165" alt="Top Languages" />
  <br><br>
  <img src="https://nirzak-streak-stats.vercel.app/?user=Nilesh123-45&theme=transparent&hide_border=true&ring=000000&fire=000000&currStreakNum=000000&sideNums=000000&sideLabels=000000&dates=000000" height="165" alt="GitHub Streak" />
</div>

<br>

```
██████████████████████████████████████████
```

<div align="center">
  <a href="https://visitcount.itsvg.in">
    <img src="https://visitcount.itsvg.in/api?id=Nilesh123-45&icon=0&color=0" alt="Profile Views">
  </a>
</div>
