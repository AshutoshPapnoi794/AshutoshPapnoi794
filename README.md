<div align="center">

# Ashutosh Papnoi

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=38BDF8&center=true&vcenter=true&width=650&lines=Software+Engineer;Distributed+Systems+%26+Concurrency;Java+%7C+Spring+Boot+3+%7C+Redis;ICMSCI-2026+Conference+Research+Presenter" alt="Typing SVG" />
</a>

<br/>

[![Degree](https://img.shields.io/badge/BSc_(Hons)_CS-Keshav_Mahavidyalaya_(DU)-0f172a?style=flat-square&logo=academia&logoColor=white)](https://keshav.du.ac.in)
[![Conference](https://img.shields.io/badge/ICMSCI--2026-Research_Presenter-1e293b?style=flat-square&logo=google-scholar&logoColor=white)](https://github.com/AshutoshPapnoi794/AiChessCommentator)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ashutosh--papnoi-0284c7?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ashutosh-papnoi-178a37324)
[![Email](https://img.shields.io/badge/Email-ashutoshpapnoi%40gmail.com-334155?style=flat-square&logo=gmail&logoColor=white)](mailto:ashutoshpapnoi@gmail.com)

</div>

---

### Executive Overview

Software Engineer specializing in **Java, Spring Boot 3, and high-concurrency backend systems**. Graduating with a Bachelor of Science (Honours) in Computer Science from Keshav Mahavidyalaya (University of Delhi) in 2026. 

My engineering focus centers on **distributed consensus, in-memory locking, fault tolerance, and empirical system verification**. Rather than building generic CRUD applications, I design systems that resolve race conditions, enforce financial idempotency, and eliminate LLM hallucinations through deterministic symbolic grounding.

---

### Flagship Systems & Repositories

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="left">
        <a href="https://github.com/AshutoshPapnoi794/seatlock-engine">SeatLock</a>
      </h3>
      <p><strong>High-Concurrency Distributed Seat Reservation Engine</strong></p>
      <ul>
        <li>Mitigates high-contention flash-sale race conditions via atomic Redis <code>SET NX EX</code> distributed locking with 10-minute hold windows.</li>
        <li>Implements transactional <code>X-Idempotency-Key</code> caching (24-hour TTL) to prevent double charges on network retries.</li>
        <li>Enforces defense-in-depth with JPA <code>@Version</code> optimistic locking and automated compensating batch rollbacks.</li>
        <li>Validated via automated <code>CountDownLatch</code> stress suites (50 concurrent threads, 852 ms response, exactly 1 winner, 49 safe rejections).</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
        <img src="https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
        <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
        <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
        <img src="https://img.shields.io/badge/JUnit_5-25A162?style=flat-square&logo=junit5&logoColor=white" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="left">
        <a href="https://github.com/AshutoshPapnoi794/AiChessCommentator">AI Chess Commentator</a>
      </h3>
      <p><strong>Hybrid Neuro-Symbolic Analysis Engine (ICMSCI-2026)</strong></p>
      <ul>
        <li>Couples asynchronous Stockfish 16 (NNUE at depth 18–20) with dual-stage Chain-of-Thought LLM context injection.</li>
        <li>Eliminates hallucinated moves and illegal square references by feeding structured engine telemetry to grandmaster persona prompts.</li>
        <li>Built Tactical Move Analyzer (TMA) algorithms detecting pins, forks, skewers, and king safety imbalances.</li>
        <li>Presented research at the <strong>International Conference on Mathematical Sciences and Computational Intelligence (ICMSCI-2026)</strong>.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" />
        <img src="https://img.shields.io/badge/Stockfish_16-111111?style=flat-square&logo=lichess&logoColor=white" />
        <img src="https://img.shields.io/badge/Gemini_API-4285F4?style=flat-square&logo=google&logoColor=white" />
        <img src="https://img.shields.io/badge/ICMSCI--2026-Accepted-4338ca?style=flat-square" />
      </p>
    </td>
  </tr>
</table>

---

### Technical Arsenal

```text
Languages          Java (17/21), SQL (MySQL, PostgreSQL), Python, Bash
Frameworks         Spring Boot 3, Spring Web, Spring Data JPA, Hibernate, JDBC, Flask
Storage & Cache    Redis (Distributed Locking, Caching), MySQL, PostgreSQL
Core Engineering   Multithreading, Concurrency, ACID Transactions, DSA, OOP, Memory Management
Verification       JUnit 5, Mockito, Postman, Integration Testing, Multi-Threaded Stress Testing
DevOps & Tooling   Linux (Ubuntu), Git, GitHub, Maven, OpenAPI / Swagger
```

<div align="left">

| Domain | Technologies & Standards |
| :--- | :--- |
| **Backend & Enterprise** | `Java 21` `Spring Boot 3` `Spring Data JPA` `Hibernate` `RESTful APIs` |
| **Distributed Systems & Data** | `Redis (SET NX EX)` `MySQL` `PostgreSQL` `Connection Pooling (HikariCP)` |
| **Reliability & Quality** | `JUnit 5` `Mockito` `CountDownLatch` `Idempotency Tokens` `Optimistic Locking` |
| **Environments & Workflow** | `Linux / Bash` `Git` `Maven` `OpenAPI / Swagger UI` `Postman` |

</div>

---

### Engineering Activity & Metrics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=AshutoshPapnoi794&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0b0f19&title_color=38bdf8&icon_color=f59e0b&text_color=cbd5e1" height="155" alt="Ashutosh's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AshutoshPapnoi794&layout=compact&theme=tokyonight&hide_border=true&bg_color=0b0f19&title_color=38bdf8&text_color=cbd5e1" height="155" alt="Ashutosh's Top Languages" />
</div>

---

<div align="center">
  <sub>Engineered by Ashutosh Papnoi • University of Delhi '26</sub>
</div>
