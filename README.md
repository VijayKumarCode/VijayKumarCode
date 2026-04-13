# Vijay Kumar — Java Backend Engineer

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-vijaykumarcode.space-2f81f7?style=flat-square&logo=vercel&logoColor=white)](https://vijaykumarcode.space)
[![Nexus Live](https://img.shields.io/badge/Nexus-Live_on_nexusgame.space-3fb950?style=flat-square&logo=spring&logoColor=white)](https://nexusgame.space)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-vijaykumarcode-0a66c2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/vijaykumarcode)
[![X](https://img.shields.io/badge/X-@VijayKumarCode-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/VijayKumarCode)

</div>

---

## About

Backend engineer building production-grade distributed systems.  
Currently shipping [**Nexus**](https://nexusgame.space) — a live multiplayer game platform.

```java
public class VijayKumar {

    String role     = "Backend Engineer";
    String focus    = "Real-time systems, WebSocket, Spring Boot 3";
    String status   = "Open to remote backend roles";
    String location = "India (remote-ready)";

    String[] stack = {
        "Java 17", "Spring Boot 3", "WebSocket (STOMP/SockJS)",
        "PostgreSQL", "Docker", "GitHub Actions", "Linux"
    };
}
```

---

## Featured Project

### [⚔️ Nexus Multiplayer Arena](https://nexusgame.space)

> Real-time multiplayer game platform. Live. Production. Real users.

| Layer | Technology |
|---|---|
| Backend | Java 17 · Spring Boot 3 · Spring Data JPA |
| Real-time | WebSocket (STOMP / SockJS) · SimpMessagingTemplate |
| Database | PostgreSQL (Neon) · Hibernate ORM · JPQL |
| Email | Resend HTTP API (port 443 — SMTP port 587 was blocked) |
| CI/CD | GitHub Actions → SCP → Oracle Cloud VM → systemd |
| Frontend | Vanilla JS · Vercel |

**Production problems I diagnosed and fixed:**

- Port-587 SMTP firewall on Railway → switched to Resend REST API, latency 2 min → <1 sec  
- JPQL `User$UserStatus` inner-class syntax crash → every game move silently rejected  
- `@Payload` missing on WebSocket handler → null roomId → all moves blocked  
- XSS via inline `onclick` username interpolation → replaced with data-attribute delegation  
- Password hash leaking in lobby API → `@JsonIgnore` on sensitive entity fields  

---

## Tech Stack

![Java](https://img.shields.io/badge/Java_17-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux_Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)

---

## Repositories

| Repository | Description | Stack |
|---|---|---|
| [nexus](https://github.com/VijayKumarCode/nexus) | Live multiplayer game platform | Java · Spring Boot · WebSocket |
| [Vijay-Kumar-Portfolio](https://github.com/VijayKumarCode/Vijay-Kumar-Portfolio) | This portfolio website | HTML · CSS · JS · Spring Boot |
| [Java-Data-Structures-and-Algorithms](https://github.com/VijayKumarCode/Java-Data-Structures-and-Algorithms) | DSA in Java 17 | Java |
| [TicTacToe_java](https://github.com/VijayKumarCode/TicTacToe_java) | Socket-based multiplayer | Java · Sockets |

---

## Engineering Log

I write about production bugs I debug and systems I build:

- [Why Your Spring Boot Emails Hang for 2 Minutes on Railway](https://vijaykumarcode.space/blog/smtp-port-587-railway)
- [The JPQL Bug That Crashed My Game Every 10 Seconds](https://vijaykumarcode.space/blog/jpql-enum-inner-class-bug)
- [Building Real-Time Multiplayer with Spring Boot WebSocket](https://vijaykumarcode.space/blog/websocket-stomp-spring-boot)

→ [All entries](https://vijaykumarcode.space/blog)

---

<div align="center">
  <sub>MCA · AKGEC Ghaziabad · Open to remote backend engineering roles</sub>
</div>
