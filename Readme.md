<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b26,50:24283b,100:7aa2f7&height=180&section=header&text=Pulkit%20Arora&fontSize=42&fontColor=ffffff&animation=twinkling&fontAlignY=38&desc=Java%20Backend%20Engineer%20%7C%20Nagarro&descAlignY=58&descSize=18&descColor=c0caf5" width="100%" alt="header" />
</div>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=3500&pause=1200&color=7AA2F7&center=true&vCenter=true&width=720&lines=Java+Backend+Engineer+at+Nagarro;Spring+Boot+%C2%B7+Redis+%C2%B7+AWS+S3;Production+systems+that+stay+up;RAG+and+LLM+integrations+on+the+side" alt="Typing intro" />
</div>

<p align="center">
  <a href="https://github.com/pulkit8690"><img src="https://img.shields.io/badge/GitHub-pulkit8690-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://www.linkedin.com/in/pulkitt-arora/"><img src="https://img.shields.io/badge/LinkedIn-Pulkit%20Arora-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:pulkitarora8690@gmail.com"><img src="https://img.shields.io/badge/Email-pulkitarora8690%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

## About

I'm a **Java Backend Engineer at [Nagarro](https://www.nagarro.com)** in Gurgaon, with a little over a year of production work on Spring Boot services.

Day to day I modernize enterprise Java systems: Java 8 → 21, Spring Boot 2.x → 4.1.0, NFS/FTP file flows onto **Amazon S3**, and in-process caches onto **Valkey/Redis** with Resilience4j fallbacks. I also work on retrieval quality for LLM-backed chat — embeddings, vector stores, and RAG.

```text
Pulkit Arora
├─ role      Software Engineer, Backend  ·  Nagarro (Jul 2025 – present)
├─ previous  Backend Intern  ·  Claw Legal Tech (Apr 2025 – Jun 2025)
├─ focus     reliable Spring Boot services, caching, fault tolerance
└─ also      RAG pipelines, embeddings, Azure AI vector search
```

---

## Tech stack

Only what I use in production or shipped projects.

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,spring,py,postgres,redis,kafka,aws,azure,docker,jenkins,git,githubactions&perline=6" alt="Tech stack" />
</p>

| | |
| :--- | :--- |
| **Languages** | Java 21, Python |
| **Backend** | Spring Boot, Spring Framework, REST APIs, microservices, Spring Data Redis, Apache Tomcat |
| **Data & messaging** | PostgreSQL, Redis / Valkey, Kafka, AWS S3, optimistic locking, transactional outbox |
| **Reliability** | Resilience4j (circuit breaker, retry), JWT, RBAC, Spring Boot Actuator |
| **Cloud & delivery** | AWS, Azure, Docker, Jenkins, GitHub Actions, JUnit, k6 |
| **AI / ML** | LLMs, Claude Haiku, embeddings, Azure AI Vector DB, RAG, LangChain |

---

## Selected work

### Nagarro — enterprise finance application *(US automotive client)*
Java, Spring Boot, AWS S3, Valkey/Redis, Resilience4j

Migrated NFS/FTP file processing to S3 as the source of truth. Removed unbounded static `HashMap` caches that were retaining heap, moved caching to Valkey/Redis (including a cache-key fix that stopped per-millisecond miss storms), and put Resilience4j breakers/retries with database fallbacks around cache calls. Platform path: Java 8 / Spring Boot 2.x → Java 21 / Spring Boot 4.1.0.

### Claw Legal Tech — chatbot retrieval
Claude Haiku, Azure AI Vector DB

Built text embeddings with Claude Haiku and stored them in Azure AI's vector database to improve chatbot retrieval quality.

### Stock Reservation System
Java, Spring Boot, PostgreSQL, Redis, Kafka, JWT, k6, JUnit

Inventory reservation under contention: **100 concurrent users vs 50 units, 0% oversell** (50 × HTTP 201, 50 × HTTP 409). k6 load checks **103/103**. Reservation p95 ~4.56s on the measured laptop run. Modular monolith with optimistic locking, transactional outbox, JWT/RBAC, Resilience4j, and **45/45** tests passing.

> Repo link: add the public GitHub URL here once the project is public — see placeholders below.

---

## GitHub stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=pulkit8690&show_icons=true&count_private=true&hide_border=true&theme=tokyonight&include_all_commits=true" alt="GitHub stats" />
  <img height="165" src="https://streak-stats.demolab.com/?user=pulkit8690&theme=tokyonight&hide_border=true" alt="GitHub streak" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=pulkit8690&layout=compact&hide_border=true&theme=tokyonight&langs_count=8" alt="Top languages" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/pulkit8690/pulkit8690/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/pulkit8690/pulkit8690/output/github-contribution-grid-snake.svg" />
    <img alt="github contribution snake" src="https://raw.githubusercontent.com/pulkit8690/pulkit8690/output/github-contribution-grid-snake.svg" />
  </picture>
</p>

---

## Currently

- Shipping backend changes on a production Spring Boot finance system (S3, Valkey/Redis, Resilience4j)
- Tightening concurrency and correctness patterns (optimistic locking, outbox, load tests)
- Improving RAG retrieval — embeddings + Azure AI vector search

**OCJP** (Oracle Certified Java Programmer) · B.E. Computer Engineering, Thapar Institute of Engineering and Technology (2025)

---

<p align="center">
  <a href="https://github.com/pulkit8690">GitHub</a>
  ·
  <a href="https://www.linkedin.com/in/pulkitt-arora/">LinkedIn</a>
  ·
  <a href="mailto:pulkitarora8690@gmail.com">Email</a>
</p>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:7aa2f7,50:24283b,100:1a1b26&height=120&section=footer" width="100%" alt="footer" />
</div>
