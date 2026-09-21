# Divyansh Negi

**Backend & Systems Engineer** · Distributed Architectures & Columnar OLAP  
Building streaming backend services, analytical query gateways, and protocol-driven fault-tolerant systems.

[LinkedIn](https://linkedin.com/in/divyanshneginot) · [Email](mailto:divyanshneginot@gmail.com) · [Resume (PDF)](https://github.com/Divyanshneginot/Divyanshneginot/blob/main/Divyansh%20Negi%20-%20Resume.pdf) · [Live App](https://omni-query-ai.vercel.app/)

*Open to backend, data-platform, and distributed-systems opportunities.*

---

### What I Build

- **Asynchronous Backend Services:** Scalable streaming pipelines and API gateways using FastAPI, Node.js, and Apollo GraphQL, with connection pooling and Server-Sent Events (SSE).
- **Analytical Query Infrastructure:** Query execution pipelines interfacing with ClickHouse Cloud, supporting runtime schema introspection and fallback execution on in-memory DuckDB.
- **Protocol & Fault-Tolerance Tooling:** Services built on the Model Context Protocol (FastMCP), pairing driver exception interception with dialect reflection loops.

---

### Featured Work

#### [OmniQuery AI](https://github.com/Divyanshneginot/OmniQuery-AI)
*Translates natural language prompts into analytical SQL for ClickHouse, streaming query lifecycle telemetry and results in real time.*

**Highlights:**
- **Dynamic Schema Introspection:** Uses Model Context Protocol (`mcp-clickhouse`) to discover table structures, columns, and data types before SQL compilation.
- **Natural Language to SQL:** Translates natural language questions into ClickHouse SQL, applying reflection logic to correct syntax and dialect mismatches on execution errors.
- **Storage Fallback:** Automatically redirects query execution to in-memory DuckDB if the primary ClickHouse Cloud cluster is unavailable or degraded.
- **Progress & Telemetry Streaming:** Emits query generation status, planning timings, and data records incrementally over an asynchronous SSE channel.
- **Stack:** Python, FastAPI, ClickHouse Cloud, DuckDB, FastMCP, Docker

```
Prompt ──► FastAPI Gateway ──► FastMCP Schema Discovery
                                  │
                                  ▼
ClickHouse Cloud ──[Fallback]──► In-Memory DuckDB ──► SSE Stream ──► Client
```

**Evidence & Demo:**  
[Repository](https://github.com/Divyanshneginot/OmniQuery-AI) · [Live Web Application](https://omni-query-ai.vercel.app/) · [Release v1.0.0](https://github.com/Divyanshneginot/OmniQuery-AI/releases/tag/v1.0.0)  
<!-- Add 15-30 second demo GIF or UI screenshot here: docs/assets/demo.gif -->

<br/>

#### [Turtleneck](https://github.com/Divyanshneginot/turtleneck)
*Design-system policy engine and automated accessibility test runner for AI coding agents.*

**Highlights:**
- **Layout & Design Guidance:** Enforces layout archetypes, spacing scales, and design tokens to prevent common visual bugs in AI-generated frontend code.
- **Automated Verification:** Ships test suites checking contrast ratios, keyboard navigation indicators, and motion budgets against WCAG AA criteria.
- **Multi-Agent Installer:** Zero-dependency Python CLI installer that injects rule configurations into Claude Code, Cursor, Windsurf, Copilot, and Google Antigravity workspaces.
- **Stack:** Python, Shell, Pytest, WCAG 2.2, GitHub Actions CI

**Evidence & Demo:**  
[Repository](https://github.com/Divyanshneginot/turtleneck) · [Release v1.0.0](https://github.com/Divyanshneginot/turtleneck/releases/tag/v1.0.0)

---

### Technical Toolkit

| Category | Technologies |
|---|---|
| **Languages** | Python, TypeScript, JavaScript, SQL, C++, Bash |
| **Backend & APIs** | FastAPI, Node.js, Express, Apollo GraphQL, REST, Server-Sent Events (SSE), AsyncIO |
| **Data & Infrastructure** | ClickHouse, DuckDB, PostgreSQL, Redis, Docker, GitHub Actions (CI/CD), Linux |
| **AI & Protocol Tooling** | Model Context Protocol (FastMCP), Agent Rule Engineering, Prompt Architecture |

---

### Credentials & Verification

- **Full Stack Open: Containers (Docker)** — University of Helsinki · [Verify Certificate](https://courses.mooc.fi/certificates/validate/en46yghwh8mmy4p)
- **Full Stack Open: TypeScript** — University of Helsinki · [Verify Certificate](https://courses.mooc.fi/certificates/validate/ujmksp84ds2xbi3)
- **Full Stack Open: GraphQL** — University of Helsinki · [Verify Certificate](https://courses.mooc.fi/certificates/validate/pzaedinbu35e4aj)
- **Full Stack Open: Core (React, Node, CI/CD)** — University of Helsinki · [Verify Certificate](https://studies.cs.helsinki.fi/stats/api/certificate/fullstackopen/en/9eb2299a446d7e2bf6642ef1db80c49f)
- **LLM Zoomcamp** — DataTalks.Club · Credential ID: `6F7D81`
- **Applied Data Science Lab** — WorldQuant University
- **OCI AI Foundations Associate** — Oracle

---

### Selected Links

- [OmniQuery AI Release v1.0.0](https://github.com/Divyanshneginot/OmniQuery-AI/releases/tag/v1.0.0)
- [Turtleneck Release v1.0.0](https://github.com/Divyanshneginot/turtleneck/releases/tag/v1.0.0)
- [Turtleneck Automated Test Suite](https://github.com/Divyanshneginot/turtleneck/tree/main/tests)

---

### Contact

- **Email:** [divyanshneginot@gmail.com](mailto:divyanshneginot@gmail.com)
- **LinkedIn:** [linkedin.com/in/divyanshneginot](https://linkedin.com/in/divyanshneginot)
- **GitHub:** [github.com/Divyanshneginot](https://github.com/Divyanshneginot)
