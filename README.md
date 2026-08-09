<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=000000&height=90&section=header&text=NILESH%20DAS&fontColor=76B900&fontSize=38&fontAlign=50&fontAlignY=60&desc=JAVA%20BACKEND%20ENGINEER&descAlign=50&descAlignY=85&descSize=16" width="100%"/>

</div>

<div align="center">

`PORTFOLIO` → [nilesh-das.vercel.app](https://nilesh-das.vercel.app/)&nbsp;&nbsp;|&nbsp;&nbsp;`LINKEDIN` → [nileshdasneil](https://www.linkedin.com/in/nileshdasneil)&nbsp;&nbsp;|&nbsp;&nbsp;`MAIL` → [nileshdas.work@gmail.com](mailto:nileshdas.work@gmail.com)

</div>

<br>

![](https://img.shields.io/badge/01-ABOUT-76B900?style=for-the-badge&labelColor=000000)

I build backends that hold up under load — designing for failure with
circuit breakers and rate limiters, tuning caching layers instead of
just adding them, reasoning about consistency before reaching for a
queue. This GitHub is the raw repository: source code, architectural
experiments, and the internals I've actually gone through.

<br>

![](https://img.shields.io/badge/02-STACK-76B900?style=for-the-badge&labelColor=000000)

```
LANGUAGES        JAVA 21 · JAVA 17 · JAVA 8 · C · JAVASCRIPT
                 SQL · HTML/CSS
BACKEND          SPRING BOOT · SPRING DATA JPA · SPRING SECURITY
                 HIBERNATE · JDBC · NODE.JS
ARCHITECTURE     MICROSERVICES · EVENT-DRIVEN DESIGN
                 RESILIENCE4J — CIRCUIT BREAKER / RATE LIMITER
MESSAGING        APACHE KAFKA
CACHING          REDIS · UPSTASH
SERVERS          APACHE TOMCAT · APACHE
FRONTEND         REACT · CONTEXT API
DATABASES        MYSQL · MONGODB · MONGODB ATLAS
DEVOPS / CI-CD   DOCKER · JENKINS · LINUX · AWS S3
DEPLOY           VERCEL · NETLIFY · RENDER
IDEs             INTELLIJ IDEA · ECLIPSE · VS CODE
TOOLING          MAVEN · GIT · GITHUB · POSTMAN · JUNIT · LOG4J
LEARNING         LABEX
```

<div align="center">

![Java](https://img.shields.io/badge/Java-000000?style=for-the-badge&logo=openjdk&logoColor=76B900)
![C](https://img.shields.io/badge/C-000000?style=for-the-badge&logo=c&logoColor=76B900)
![JavaScript](https://img.shields.io/badge/JavaScript-000000?style=for-the-badge&logo=javascript&logoColor=76B900)
![CSS3](https://img.shields.io/badge/CSS3-000000?style=for-the-badge&logo=css3&logoColor=76B900)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-000000?style=for-the-badge&logo=spring&logoColor=76B900)
![Hibernate](https://img.shields.io/badge/Hibernate-000000?style=for-the-badge&logo=hibernate&logoColor=76B900)
![Node.js](https://img.shields.io/badge/Node.js-000000?style=for-the-badge&logo=node.js&logoColor=76B900)
![React](https://img.shields.io/badge/React-000000?style=for-the-badge&logo=react&logoColor=76B900)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-000000?style=for-the-badge&logo=apachekafka&logoColor=76B900)
![Redis](https://img.shields.io/badge/Redis-000000?style=for-the-badge&logo=redis&logoColor=76B900)
![Apache Tomcat](https://img.shields.io/badge/Tomcat-000000?style=for-the-badge&logo=apache-tomcat&logoColor=76B900)
![Apache](https://img.shields.io/badge/Apache-000000?style=for-the-badge&logo=apache&logoColor=76B900)
![MySQL](https://img.shields.io/badge/MySQL-000000?style=for-the-badge&logo=mysql&logoColor=76B900)
![MongoDB](https://img.shields.io/badge/MongoDB-000000?style=for-the-badge&logo=mongodb&logoColor=76B900)
![Linux](https://img.shields.io/badge/Linux-000000?style=for-the-badge&logo=linux&logoColor=76B900)
![Docker](https://img.shields.io/badge/Docker-000000?style=for-the-badge&logo=docker&logoColor=76B900)
![Jenkins](https://img.shields.io/badge/Jenkins-000000?style=for-the-badge&logo=jenkins&logoColor=76B900)
![AWS](https://img.shields.io/badge/AWS-000000?style=for-the-badge&logo=amazon-aws&logoColor=76B900)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=76B900)
![Netlify](https://img.shields.io/badge/Netlify-000000?style=for-the-badge&logo=netlify&logoColor=76B900)
![Render](https://img.shields.io/badge/Render-000000?style=for-the-badge&logo=render&logoColor=76B900)
![Maven](https://img.shields.io/badge/Maven-000000?style=for-the-badge&logo=apachemaven&logoColor=76B900)
![Git](https://img.shields.io/badge/Git-000000?style=for-the-badge&logo=git&logoColor=76B900)
![GitHub](https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=76B900)
![Postman](https://img.shields.io/badge/Postman-000000?style=for-the-badge&logo=postman&logoColor=76B900)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellij-idea&logoColor=76B900)
![Eclipse](https://img.shields.io/badge/Eclipse-000000?style=for-the-badge&logo=eclipse&logoColor=76B900)
![VS Code](https://img.shields.io/badge/VS_Code-000000?style=for-the-badge&logo=visual-studio-code&logoColor=76B900)

</div>

<br>

![](https://img.shields.io/badge/03-PROJECTS-76B900?style=for-the-badge&labelColor=000000)

<img src="assets/01-snapos.svg" alt="Snapos"/>
* Full-stack app letting users create custom-URL digital profiles with QR-code sharing, PIN-protected access, and self-serve account recovery.
* Built a polished interaction layer from scratch — animated PIN entry, expanding-circle button transitions, scroll-triggered reveals — no UI library shortcuts.
* Designed the auth/recovery flow to avoid the "locked out forever" trap common in PIN-based systems.

<br><br>
<img src="assets/02-caching.svg" alt="Caching Layer"/>
* Built a caching layer over a CRUD service, choosing cache-aside vs. write-through per endpoint based on read/write ratio and staleness tolerance.
* Used SpEL-based dynamic cache keys and `@Transactional`-aware eviction to keep cache and DB consistent on writes and deletes.
* Backed by Upstash-hosted Redis, cutting redundant DB hits on hot read paths.

<br><br>
<img src="assets/03-booking.svg" alt="Booking API"/>
* Designed a REST API with centralized error handling (`@RestControllerAdvice`, custom exception hierarchy) instead of scattered try-catch, so every failure mode returns a consistent, client-usable response.
* Containerized with Docker and shipped a declarative Jenkins pipeline for automated builds — resolved cross-platform build issues along the way (Windows/WSL2 case-sensitivity gotchas).

<br><br>
<img src="assets/04-kafka.svg" alt="Event Pipeline"/>
* Stood up a local multi-broker Kafka cluster to work through partitioning strategy, sticky partitioner behavior, and keyed message routing for ordering guarantees.
* Modeled consumer group semantics hands-on — including groupless consumers behaving as pub-sub — to reason correctly about scaling consumers without losing message order.

<br><br>
<img src="assets/05-pos.svg" alt="Billing &amp; Inventory POS"/>
* Built a high-concurrency RESTful application handling billing and inventory in real time.
* Integrated AWS S3 for digital asset storage and Razorpay for secure payments.
* Cut server load by ~40% through cloud-native optimizations.

<br><br>
<img src="assets/06-expense.svg" alt="Expense Tracker"/>
* Full-stack app to track, categorize, and analyze monthly expenses.
* Backend built with Spring Boot + Spring Data JPA, dependencies managed via Maven.
* React + Context API frontend for efficient state management; automated email notifications for financial summaries.

<br><br>
<img src="assets/07-leave.svg" alt="Leave Management"/>
* Responsive MERN stack application built to digitize HR leave workflows end to end.

<br><br>
<img src="assets/08-hospital.svg" alt="Hospital Management"/>
* Console-based healthcare application built on raw fundamentals — strictly Core Java and JDBC for database connectivity, no framework scaffolding.

<br><br>
![](https://img.shields.io/badge/04-STATS-76B900?style=for-the-badge&labelColor=000000)

`LEETCODE / HACKERRANK` — 1000+ solution views

<br>

![](https://img.shields.io/badge/05-ANALYTICS-76B900?style=for-the-badge&labelColor=000000)

<div align="center">
  <img src="https://github-stats-extended.vercel.app/api?username=Nilesh123-45&theme=transparent&hide_border=true&title_color=76B900&text_color=888888&icon_color=76B900" height="165" alt="GitHub Stats" />
  <img src="https://github-stats-extended.vercel.app/api/top-langs/?username=Nilesh123-45&theme=transparent&hide_border=true&title_color=76B900&text_color=888888&layout=compact" height="165" alt="Top Languages" />
  <br><br>
  <img src="https://streak-stats.demolab.com/?user=Nilesh123-45&hide_border=true&background=00000000&ring=76B900&fire=76B900&currStreakNum=76B900&sideNums=888888&sideLabels=888888&dates=888888" height="165" alt="GitHub Streak" />
</div>
<br>
<img src="https://capsule-render.vercel.app/api?type=rect&color=000000&height=6&section=footer" width="100%"/>
<div align="center">
  <a href="https://github.com/antonkomarev/github-profile-views-counter">
    <img src="https://komarev.com/ghpvc/?username=Nilesh123-45&style=for-the-badge&color=76B900&label=PROFILE+VIEWS" alt="Profile Views">
  </a>
</div>
 
