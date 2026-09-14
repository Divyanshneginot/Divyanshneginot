# Divyansh Negi

B.Tech Computer Science & Engineering student at **Birla Institute of Applied Sciences** (2024–2028).  
Focusing on backend systems, tool protocols (MCP), columnar databases, and full-stack web applications.

[LinkedIn](https://linkedin.com/in/divyanshneginot) · [Email](mailto:divyanshneginot@gmail.com) · [Resume (PDF)](./Divyansh%20Negi%20-%20Resume.pdf)

---

### What I'm Working On

- **Autonomous Tool-Use & Protocols:** Building systems that interface LLMs with real databases via the Model Context Protocol (MCP), using self-healing SQL reflection loops to catch dialect errors.
- **Analytical Data Systems:** Low-latency OLAP queries over ClickHouse Cloud and in-memory DuckDB with automated failover.
- **Full-Stack & APIs:** End-to-end applications using TypeScript, React 19, FastAPI, Node.js, and streaming (SSE).

---

### Featured Projects

#### [OmniQuery AI](https://github.com/Divyanshneginot/OmniQuery-AI) · [Live Demo](https://omni-query-ai.vercel.app/)
Conversational analytics agent that translates natural language questions into ClickHouse SQL for film box office and streaming telemetry.
- **Backend & Protocol:** Built with Google ADK, Gemini 3.6 Flash, and official `mcp-clickhouse` (FastMCP) tools for runtime schema introspection.
- **Reliability:** Self-healing SQL reflection loop catches database compiler exceptions and regenerates valid queries (99%+ success rate). Dual-engine failover from ClickHouse Cloud on GCP to in-memory DuckDB.
- **Frontend & Streaming:** Streams live execution traces, query plans, and Recharts visualizations to a React 19 dashboard via FastAPI Server-Sent Events (SSE).
- **Stack:** Python, FastAPI, ClickHouse Cloud, DuckDB, FastMCP, React 19, Tailwind CSS.

#### [Full-Stack AI Document Intelligence Platform](https://github.com/Divyanshneginot)
Microservices-based document parsing and retrieval engine.
- Express.js API gateway paired with a FastAPI worker for semantic search and conversational extraction.
- Ingestion pipeline combines digital PDF extraction (PyMuPDF) with OCR fallback (EasyOCR), indexing chunks into ChromaDB.
- Dynamic query classifier routes requests between simple lookups and multi-hop reasoning to reduce LLM latency and token cost.
- **Stack:** Python, TypeScript, FastAPI, Express.js, ChromaDB, React.

#### [Legal Contract Summarization & Evaluation](https://github.com/Divyanshneginot)
Automated document analysis pipeline that distills long-form legal contracts into structured summaries.
- Vector indexing and semantic chunking to improve clause retrieval accuracy and reduce search latency.
- Automated multi-agent evaluation harness to benchmark summary coherence and faithfulness against human references.
- **Stack:** Python, LangChain, HuggingFace Transformers, ChromaDB.

---

### Technical Skills

- **Languages:** Python, TypeScript, JavaScript, SQL, C++, Java, Bash
- **AI & Systems:** Google ADK, FastMCP (Model Context Protocol), LangChain, Vector Search, LLM Evaluation
- **Backend & Cloud:** FastAPI, Node.js, Express, Docker, CI/CD (GitHub Actions), REST, GraphQL (Apollo), GCP, Linux
- **Databases:** ClickHouse, PostgreSQL, DuckDB, ChromaDB, Redis

---

### Education & Certifications

- **B.Tech in Computer Science & Engineering** — Birla Institute of Applied Sciences (*2024 – 2028*)
- **Full Stack Open: Containers (Docker)** — University of Helsinki (*Sep 2026*) · [Verify](https://courses.mooc.fi/certificates/validate/en46yghwh8mmy4p)
- **LLM Zoomcamp 2026** — DataTalks.Club (*Aug 2026*) · *ID: 6F7D81*
- **Full Stack Open (React, TypeScript, GraphQL, CI/CD)** — University of Helsinki (*Jun 2026*)
- **Oracle Cloud Infrastructure 2025 AI Foundations Associate** — Oracle (*Oct 2025*)
