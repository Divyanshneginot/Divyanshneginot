<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,16,28&height=140&section=header" width="100%"/>
</div>

<div align="center">

# Divyansh Negi
**Backend & Systems Engineer · Distributed Architectures · Columnar OLAP**

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=14&duration=2800&pause=1200&color=6366F1&center=true&vCenter=true&width=520&lines=%3E_++High-Throughput+Async+APIs+with+FastAPI+%26+Node.js;%3E_++Low-Latency+Columnar+OLAP+on+ClickHouse+%26+DuckDB;%3E_++Distributed+Systems+%26+Real-Time+SSE+Streaming;%3E_++Model+Context+Protocol+(FastMCP)+Integrations" alt="Typing Animation" />
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
- **Protocol Engineering & Fault Tolerance:** Interfacing services with databases and external runtimes via the **Model Context Protocol (FastMCP)**; self-healing reflection loops that intercept database syntax exceptions and iteratively self-heal queries.

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
- **Self-Healing Execution Loop:** Intercepts database compiler exceptions and SQL dialect errors at the driver level, running reflection logic to iteratively regenerate and execute valid SQL against the target dialect.
- **Zero-Downtime Dual Engine:** Automated failover redirecting analytical queries from ClickHouse Cloud on GCP to in-memory DuckDB during cluster degradation or network partitions.
- **Real-Time Event Streaming:** Implemented an asynchronous Server-Sent Events (SSE) streaming engine delivering live query execution plans, timing metrics, and data payloads.
- **Stack:** `Python` · `FastAPI` · `ClickHouse Cloud` · `FastMCP` · `DuckDB` · `AsyncIO` · `TypeScript` · `Docker`

<br/>

#### 🛡️ [Turtleneck](https://github.com/Divyanshneginot/turtleneck)
*Senior UI/UX architect and runtime policy engine for AI coding agents with automated WCAG AA gates.*

- **Design Taste Enforcement:** Intercepts agent code generation pipelines across Claude Code, Cursor, Windsurf, Copilot, and Google Antigravity, preventing generic AI interface slop (low-contrast opacity, 800ms delays, broken keyboard focus).
- **Automated Quality Gates:** Bundles verifiable test suites asserting contrast ratios, touch targets, and motion budgets with standard-library zero-dependency installers.
- **Stack:** `Python` · `Agentic Frameworks` · `Design Systems` · `WCAG 2.2` · `CI/CD`

---

### 📜 Certifications & Accreditations

- 🐳 **Full Stack Open: Containers (Docker)** — University of Helsinki (*Sep 2026*) · [Verify](https://courses.mooc.fi/certificates/validate/en46yghwh8mmy4p)
- 🔷 **Full Stack Open: TypeScript** — University of Helsinki (*Aug 2026*) · [Verify](https://courses.mooc.fi/certificates/validate/ujmksp84ds2xbi3)
- 🧠 **LLM Zoomcamp 2026** — DataTalks.Club (*Aug 2026*) · *ID: 6F7D81*
- 🕸️ **Full Stack Open: GraphQL** — University of Helsinki (*Jul 2026*) · [Verify](https://courses.mooc.fi/certificates/validate/pzaedinbu35e4aj)
- 🌐 **Full Stack Open: Core (React, Node, CI/CD)** — University of Helsinki (*Jun 2026*) · [Verify](https://studies.cs.helsinki.fi/stats/api/certificate/fullstackopen/en/9eb2299a446d7e2bf6642ef1db80c49f)
- 📊 **Applied Data Science Lab** — WorldQuant University (*Apr 2026*)
- ☁️ **Oracle Cloud Infrastructure 2025 AI Foundations Associate** — Oracle (*Oct 2025*)

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,16,28&height=100&section=footer" width="100%"/>
</div>

<div align="center">
  <sub>Divyansh Negi · <a href="https://linkedin.com/in/divyanshneginot">LinkedIn</a> · <a href="mailto:divyanshneginot@gmail.com">Email</a> · <a href="https://github.com/Divyanshneginot/Divyanshneginot/blob/main/Divyansh%20Negi%20-%20Resume.pdf">Resume</a></sub>
</div>
