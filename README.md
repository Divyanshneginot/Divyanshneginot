<div align="center">

# Divyansh Negi
**Systems & Backend Engineer · Autonomous Agent Architectures · Columnar OLAP**

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=15&duration=2800&pause=1200&color=6366F1&center=true&vCenter=true&width=550&lines=%3E_++Autonomous+Agent+Architectures+%26+Reasoning+Loops;%3E_++Model+Context+Protocol+(FastMCP)+Integrations;%3E_++Sub-200ms+OLAP+Analytics+with+ClickHouse;%3E_++Real-Time+Full-Stack+Systems+with+FastAPI+%26+React" alt="Typing Animation" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/divyanshneginot"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:divyanshneginot@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/Divyanshneginot/Divyanshneginot/blob/main/Divyansh%20Negi%20-%20Resume.pdf"><img src="https://img.shields.io/badge/Resume-PDF-red?style=flat-square&logo=adobe&logoColor=white" alt="Resume" /></a>
  <a href="https://omni-query-ai.vercel.app/"><img src="https://img.shields.io/badge/Live_App-omni--query--ai.vercel.app-6366F1?style=flat-square&logo=vercel&logoColor=white" alt="OmniQuery AI" /></a>
</p>

</div>

---

### Core Focus

I design and build **autonomous tool-using agents**, **low-latency analytical backends**, and **reliable distributed systems**.

- **Protocol-Driven Agents:** Connecting LLMs to real production environments via the **Model Context Protocol (FastMCP)**, utilizing dynamic schema introspection and self-healing reflection loops.
- **Columnar & Analytical Data:** Sub-200ms OLAP queries over **ClickHouse Cloud** paired with in-memory **DuckDB** failover engines for zero-downtime execution.
- **Full-Stack & Real-Time APIs:** High-throughput async backends with **FastAPI**, **Node.js**, **TypeScript**, and **Server-Sent Events (SSE)**.

---

### Featured Systems

#### 🎬 [OmniQuery AI](https://github.com/Divyanshneginot/OmniQuery-AI) · [Live Application](https://omni-query-ai.vercel.app/)
*Autonomous conversational analytics agent translating natural language into ClickHouse OLAP SQL with real-time SSE streaming.*

```
User Query (Natural Language) ──► FastAPI SSE Gateway ──► Google ADK (Gemini 3.6 Flash)
                                                                 │
      ┌──────────────────────────────────────────────────────────┴────────────────────────┐
      ▼                                                                                   ▼
Schema Introspection & Planning                                             Execution & Reflection Loop
(Official mcp-clickhouse / FastMCP)                                         (Dialect catch & self-healing)
      │                                                                                   │
      ▼                                                                                   ▼
ClickHouse Cloud (GCP) ──[Automatic Failover]──► In-Memory DuckDB ─────────► React 19 Canvas (Live SSE)
```

- **Runtime MCP Integration:** Direct integration with official `mcp-clickhouse` server for dynamic runtime schema discovery, metadata introspection, and isolated query execution.
- **Self-Healing SQL Loop:** Automatically intercepts database compiler exceptions and SQL dialect errors, diagnosing error traces and regenerating valid queries with a **99%+ success rate**.
- **Zero-Downtime Dual Engine:** Primary execution on ClickHouse Cloud on GCP with transparent automatic fallback to in-memory DuckDB.
- **Real-Time Trace Streaming:** Streams execution traces, multi-turn reasoning steps, and responsive Recharts visual cards to React 19 via Server-Sent Events (SSE).
- **Stack:** `Python` · `FastAPI` · `ClickHouse Cloud` · `FastMCP` · `DuckDB` · `React 19` · `TypeScript` · `Tailwind CSS`

---

#### 📄 [Full-Stack AI Document Intelligence Platform](https://github.com/Divyanshneginot)
*Microservices-based document parsing, hybrid extraction, and conversational semantic search.*

- **Dynamic Query Routing:** Deployed an intelligent LLM query classification agent to distinguish between single-hop factual retrieval and multi-hop synthesis, reducing LLM token consumption and latency by **35%**.
- **Resilient Hybrid Ingestion:** Ingestion harness pairing digital text extraction (PyMuPDF) with OCR fallback (EasyOCR) for complex scans and tables, indexing semantic chunks into ChromaDB.
- **Provider Failover:** Real-time Server-Sent Events (SSE) streaming with multi-provider failover (Gemini 1.5 Flash to Groq LLaMA 3.3 70B) to guarantee continuous availability.
- **Stack:** `Python` · `FastAPI` · `Express.js` · `TypeScript` · `ChromaDB` · `React` · `Docker`

---

#### ⚖️ [Legal Contract Summarization & Evaluation Engine](https://github.com/Divyanshneginot)
*Automated contract analysis pipeline with autonomous multi-agent evaluation.*

- **Document Distillation:** Condenses complex 50+ page legal agreements into structured 1-page executive briefs using semantic chunking and dense vector retrieval.
- **Autonomous Evaluation Harness:** Systematic multi-agent benchmarking harness to evaluate output coherence, summary completeness, and factual faithfulness against human reference briefs.
- **Stack:** `Python` · `LangChain` · `HuggingFace Transformers` · `ChromaDB` · `RAG`

---

### Technical Arsenal

| Domain | Technologies |
|---|---|
| **Languages** | Python, TypeScript, JavaScript, SQL, C++, Java, Bash |
| **Agent Architecture & Protocols** | Model Context Protocol (FastMCP), Google ADK, LangChain, Multi-Turn ReAct Loops, Self-Healing Reflection |
| **Backend & Cloud** | FastAPI, Node.js, Express, Docker, CI/CD (GitHub Actions), REST, GraphQL (Apollo), Server-Sent Events (SSE), GCP, Linux |
| **Databases & Vector Stores** | ClickHouse Cloud, DuckDB, PostgreSQL, ChromaDB, Redis, MongoDB |

---

### Certifications & Accreditations

- 🐳 **Full Stack Open: Containers (Docker)** — University of Helsinki (*Sep 2026*) · [Verify](https://courses.mooc.fi/certificates/validate/en46yghwh8mmy4p)
- 🧠 **LLM Zoomcamp 2026** — DataTalks.Club (*Aug 2026*) · *ID: 6F7D81*
- 🌐 **Full Stack Open Certification (React, TypeScript, GraphQL, CI/CD)** — University of Helsinki (*Jun 2026*)
- 📊 **Applied Data Science Lab** — WorldQuant University (*Apr 2026*)
- ☁️ **Oracle Cloud Infrastructure 2025 AI Foundations Associate** — Oracle (*Oct 2025*)

---

<div align="center">
  <sub>Divyansh Negi · <a href="https://linkedin.com/in/divyanshneginot">LinkedIn</a> · <a href="mailto:divyanshneginot@gmail.com">Email</a> · <a href="./Divyansh%20Negi%20-%20Resume.pdf">Resume</a></sub>
</div>
