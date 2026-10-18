# Divyansh Negi

Software engineer based in Uttarakhand, India. I build backend systems, query engines, and evaluation pipelines for LLM tools, with a focus on database internals and distributed systems.

[Email](mailto:divyanshneginot@gmail.com) / [LinkedIn](https://linkedin.com/in/divyanshneginot) / [Resume](./Divyansh%20Negi%20-%20Resume.pdf)

---

### Projects

#### [OmniQuery AI](https://github.com/Divyanshneginot/OmniQuery-AI) ([demo](https://omni-query-ai.vercel.app/))
Query gateway that fronts ClickHouse Cloud OLAP with automatic fallback to in-memory DuckDB when the cluster degrades or hits network timeouts. Uses FastMCP over `information_schema` so AI agents can inspect table layouts without passing massive schema definitions into context. Includes a reflection loop that catches dialect syntax errors and repairs queries on the fly.
* `Python`, `FastAPI`, `ClickHouse Cloud`, `DuckDB`, `FastMCP`, `Docker`, `React 19`

#### [Open-Source Support Assistant](https://github.com/Divyanshneginot/LLM-Datatalks-Project)
ReAct support agent and evaluation pipeline for FastAPI documentation and closed GitHub issues. Uses SQLite FTS5 for fast text search and includes an offline evaluation harness that scored a 90.00% top-5 hit rate and 0.7542 MRR across synthetic ground-truth test sets. Deployed with Docker Compose, storing latency and token metrics in PostgreSQL with Grafana dashboards.
* `Python`, `Groq (Llama 3.3)`, `SQLite FTS5`, `PostgreSQL`, `Grafana`, `Docker Compose`

#### [BidSahayak](https://github.com/Divyanshneginot/BidSahayak)
Municipal tender PDFs in India are often messy, multi-page scans with split tables. Built an ingestion service in FastAPI that pairs PyMuPDF text parsing with deterministic regex fallbacks to extract tender values, earnest money deposits, and submission deadlines without hallucinated numbers. Packaged in a multi-stage Docker image with health checks.
* `Python`, `FastAPI`, `Pydantic v2`, `PyMuPDF`, `Docker`, `Pytest`

#### [turtleneck](https://github.com/Divyanshneginot/turtleneck) ([v1.0.0](https://github.com/Divyanshneginot/turtleneck/releases/tag/v1.0.0))
Zero-dependency Python CLI that checks codebases for accessibility rules and layout invariants (WCAG 2.2 AA contrast math, keyboard focus indicators). Tested with 74 hermetic Pytest cases (100% CI pass rate). Includes an installer script to configure rule sets across Cursor, Claude Code, Windsurf, and Antigravity.
* `Python`, `Pytest`, `Shell`, `GitHub Actions`

---

### Stack

- **Languages:** Python, TypeScript, SQL, C++, C, JavaScript, Bash
- **Backend and storage:** FastAPI, Node.js, Express, PostgreSQL, ClickHouse Cloud, DuckDB, Redis, GraphQL
- **Tooling and infra:** Docker, GitHub Actions, Linux, Pytest, Git, FastMCP

---

### Certifications

- **Full Stack Open (University of Helsinki):** [Docker](https://courses.mooc.fi/certificates/validate/en46yghwh8mmy4p), [TypeScript](https://courses.mooc.fi/certificates/validate/ujmksp84ds2xbi3), [GraphQL](https://courses.mooc.fi/certificates/validate/pzaedinbu35e4aj), [Core Architecture](https://studies.cs.helsinki.fi/stats/api/certificate/fullstackopen/en/9eb2299a446d7e2bf6642ef1db80c49f)
- **LLM Zoomcamp (DataTalks.Club):** Evaluation harnesses, vector search, production LLM pipelines (ID: `6F7D81`)
- **Applied Data Science Lab (WorldQuant University):** Data pipelines and statistical modeling
- **OCI AI Foundations Associate (Oracle):** Cloud infrastructure and foundational AI (ID: `323406956OCI25AICFA`)
