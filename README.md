<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,16,28&height=140&section=header" width="100%"/>
</div>

<div align="center">

# Divyansh Negi
**Backend & Systems Engineer · Distributed Architectures · Columnar OLAP**

<p align="center">
  <a href="https://readme-typing-svg.demolab.com">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=15&duration=2500&pause=1000&color=6366F1&multiline=true&width=620&height=105&lines=curl+-s+https%3A%2F%2Fapi.divyansh.dev%2Fstatus;%7B+%22role%22%3A+%22Backend+%26+Systems+Engineer%22%2C+%22focus%22%3A+%22OLAP+%26+FastMCP%22+%7D;%7B+%22core_stack%22%3A+%5B%22FastAPI%22%2C+%22ClickHouse%22%2C+%22Node.js%22%2C+%22Docker%22%5D+%7D" alt="Terminal Command Animation" />
  </a>
</p>

<p align="center">
  <a href="https://linkedin.com/in/divyanshneginot"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:divyanshneginot@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/Divyanshneginot/Divyanshneginot/blob/main/Divyansh%20Negi%20-%20Resume.pdf"><img src="https://img.shields.io/badge/Resume-PDF-red?style=flat-square&logo=adobe&logoColor=white" alt="Resume" /></a>
  <a href="https://omni-query-ai.vercel.app/"><img src="https://img.shields.io/badge/Live_App-omni--query--ai.vercel.app-6366F1?style=flat-square&logo=vercel&logoColor=white" alt="OmniQuery AI" /></a>
</p>

</div>

---

### ⚡ Core Focus

I architect and build **backend infrastructure**, **high-throughput asynchronous services**, and **low-latency analytical data systems**.

- **High-Throughput APIs & Microservices:** Async architectures in **FastAPI**, **Node.js**, and **Apollo GraphQL**; implementing low-latency REST/RPC gateways, real-time event streaming (SSE), and connection pooling.
- **Columnar OLAP & Storage Engines:** Sub-200ms analytical execution over **ClickHouse Cloud**, automated runtime schema discovery, and zero-downtime failover to in-memory **DuckDB**.
- **Protocol Engineering & Fault Tolerance:** Interfacing services with databases and external runtimes via the **Model Context Protocol (FastMCP)**; self-healing reflection loops that intercept database syntax exceptions and self-correct with a **99%+ success rate**.

---

### 🛠️ Technical Stack

<div align="center">
  <p align="center">
    <a href="https://skillicons.dev">
      <img src="https://skillicons.dev/icons?i=py,ts,fastapi,nodejs,express,graphql,postgres,docker,gcp,linux,bash,cpp&theme=dark" alt="Technical Stack Icons" />
    </a>
  </p>
</div>

<div align="center">

| Domain | Technologies |
|---|---|
| **Core Languages** | Python, TypeScript, JavaScript, SQL, C++, Java, Bash |
| **Backend & Distributed Systems** | FastAPI, Node.js, Express, Apollo GraphQL, REST APIs, Server-Sent Events (SSE), AsyncIO, Concurrency, Microservices |
| **Databases & Storage Engines** | ClickHouse Cloud, DuckDB, PostgreSQL, ChromaDB, Redis, MongoDB |
| **Protocols & Infrastructure** | Model Context Protocol (FastMCP), Docker, GitHub Actions (CI/CD), Linux/Unix, Google Cloud (GCP), OCI |

</div>

---

### 🚀 Featured System

#### 🎬 [OmniQuery AI](https://github.com/Divyanshneginot/OmniQuery-AI) · [Live Application](https://omni-query-ai.vercel.app/)
*High-performance analytical query gateway translating natural language into ClickHouse OLAP SQL with real-time SSE streaming.*

```
User Request ──► FastAPI SSE Gateway ──► Query Planning & Introspection (Google ADK)
                                                         │
      ┌──────────────────────────────────────────────────┴────────────────────────────────┐
      ▼                                                                                   ▼
Runtime Protocol Handler (FastMCP)                                          Execution & Self-Healing Loop
(mcp-clickhouse: table discovery)                                           (Catches compiler errors & heals)
      │                                                                                   │
      ▼                                                                                   ▼
ClickHouse Cloud (GCP) ──[Automatic Failover]──► In-Memory DuckDB ─────────► Async SSE Stream ──► Client
```

- **Query Gateway & Protocol:** Built a high-performance backend gateway utilizing FastAPI and Model Context Protocol (`mcp-clickhouse`), dynamically introspecting schemas and compiling natural language queries into optimized ClickHouse SQL.
- **Self-Healing Execution Loop:** Intercepts database compiler exceptions and SQL dialect errors at the driver level, running reflection logic to regenerate valid queries on the fly with a **99%+ success rate**.
- **Zero-Downtime Dual Engine:** Automated failover redirecting analytical queries from ClickHouse Cloud on GCP to in-memory DuckDB during cluster degradation or network partitions.
- **Real-Time Event Streaming:** Implemented an asynchronous Server-Sent Events (SSE) streaming engine delivering live query execution plans, timing metrics, and data payloads.
- **Stack:** `Python` · `FastAPI` · `ClickHouse Cloud` · `FastMCP` · `DuckDB` · `AsyncIO` · `TypeScript` · `Docker`

---

### 📜 Certifications & Accreditations

- 🐳 **Full Stack Open: Containers (Docker)** — University of Helsinki (*Sep 2026*) · [Verify](https://courses.mooc.fi/certificates/validate/en46yghwh8mmy4p)
- 🧠 **LLM Zoomcamp 2026** — DataTalks.Club (*Aug 2026*) · *ID: 6F7D81*
- 🌐 **Full Stack Open Certification (React, TypeScript, GraphQL, CI/CD)** — University of Helsinki (*Jun 2026*)
- 📊 **Applied Data Science Lab** — WorldQuant University (*Apr 2026*)
- ☁️ **Oracle Cloud Infrastructure 2025 AI Foundations Associate** — Oracle (*Oct 2025*)

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,16,28&height=100&section=footer" width="100%"/>
</div>

<div align="center">
  <sub>Divyansh Negi · <a href="https://linkedin.com/in/divyanshneginot">LinkedIn</a> · <a href="mailto:divyanshneginot@gmail.com">Email</a> · <a href="https://github.com/Divyanshneginot/Divyanshneginot/blob/main/Divyansh%20Negi%20-%20Resume.pdf">Resume</a></sub>
</div>
