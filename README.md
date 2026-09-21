# Divyansh Negi

**Backend & Systems Engineer** · Distributed Architectures & Columnar OLAP  
Building low-latency query gateways, streaming APIs, and protocol-driven fault-tolerant services.

[LinkedIn](https://linkedin.com/in/divyanshneginot) · [Email](mailto:divyanshneginot@gmail.com) · [Resume (PDF)](https://github.com/Divyanshneginot/Divyanshneginot/blob/main/Divyansh%20Negi%20-%20Resume.pdf) · [Live Demo](https://omni-query-ai.vercel.app/)

*Open to backend, data platform, and distributed systems engineering opportunities.*

---

### What I Build

- **High-Throughput Streaming APIs:** Asynchronous services using FastAPI, Node.js, and Apollo GraphQL, with connection pooling and Server-Sent Events (SSE) for incremental execution feedback.
- **Analytical Query Gateways:** Analytical query execution layers leveraging ClickHouse Cloud, dynamic schema introspection, and automated fallback to in-memory DuckDB during cluster disruptions.
- **Protocol & Fault-Tolerance Engineering:** Structured runtime integrations via the Model Context Protocol (FastMCP), pairing driver-level error interception with iterative SQL syntax reflection.

---

### Featured Systems

#### [OmniQuery AI](https://github.com/Divyanshneginot/OmniQuery-AI)
*Translates natural language questions into executable ClickHouse OLAP SQL with real-time SSE execution telemetry.*

- **Dynamic Schema Discovery:** Connects to ClickHouse via Model Context Protocol (`mcp-clickhouse`) to dynamically inspect table structures, constraints, and partitions before compiling queries.
- **Iterative Error Recovery:** Intercepts driver-level compilation and syntax errors, submitting execution context back through reflection logic to correct dialect-specific syntax before retrying.
- **Resilient Storage Fallback:** Routes analytical workloads to in-memory DuckDB when ClickHouse Cloud clusters encounter connectivity degradation or rate limits.
- **Live Telemetry Streaming:** Emits step-by-step query planning status, execution timing, and final record batches over an asynchronous Server-Sent Events (SSE) stream.
- **Stack:** Python, FastAPI, ClickHouse Cloud, DuckDB, FastMCP, AsyncIO, Docker

```
User Prompt ──► FastAPI SSE Gateway ──► Schema Introspection (FastMCP)
                                                │
                                                ▼
ClickHouse Cloud ──[Fallback on Failure]──► In-Memory DuckDB ──► SSE Stream ──► Client
```

**Evidence & Demo:**  
[Repository](https://github.com/Divyanshneginot/OmniQuery-AI) · [Live Web Application](https://omni-query-ai.vercel.app/) · [Release v1.0.0](https://github.com/Divyanshneginot/OmniQuery-AI/releases/tag/v1.0.0)  
<!-- Add 15-30s product demo GIF or screenshot: docs/assets/omniquery-demo.gif -->

<br/>

#### [Turtleneck](https://github.com/Divyanshneginot/turtleneck)
*Senior UI/UX architect and runtime policy engine enforcing design systems and accessibility rules on AI coding agents.*

- **Design Policy Enforcement:** Provides structured prompt rules and workspace analysis to prevent common failure modes in AI-generated UIs (low-contrast text, missing focus states, unconstrained animations).
- **Automated Verification:** Integrates test suites validating color contrast ratios, layout densities, and motion budgets against WCAG AA standards.
- **Zero-Dependency Tooling:** Lightweight Python standard-library installer supporting Claude Code, Cursor, Windsurf, Copilot, and Antigravity.
- **Stack:** Python, Shell, Design Tokens, WCAG 2.2, GitHub Actions CI

**Evidence & Demo:**  
[Repository](https://github.com/Divyanshneginot/turtleneck) · [Release v1.0.0](https://github.com/Divyanshneginot/turtleneck/releases/tag/v1.0.0)

---

### Technical Toolkit

| Category | Tools & Technologies |
|---|---|
| **Languages** | Python, TypeScript, JavaScript, SQL, C++, Bash |
| **Backend & APIs** | FastAPI, Node.js, Express, Apollo GraphQL, REST, Server-Sent Events (SSE), AsyncIO |
| **Data & Infrastructure** | ClickHouse, DuckDB, PostgreSQL, Redis, Docker, GitHub Actions (CI/CD), Linux |
| **Protocols & Agent Tooling** | Model Context Protocol (FastMCP), Agent Architectures, Prompt Frameworks |

---

### Certifications & Verification

- **Full Stack Open: Containers (Docker)** — University of Helsinki · [Verify](https://courses.mooc.fi/certificates/validate/en46yghwh8mmy4p)
- **Full Stack Open: TypeScript** — University of Helsinki · [Verify](https://courses.mooc.fi/certificates/validate/ujmksp84ds2xbi3)
- **Full Stack Open: GraphQL** — University of Helsinki · [Verify](https://courses.mooc.fi/certificates/validate/pzaedinbu35e4aj)
- **Full Stack Open: Core (React, Node, CI/CD)** — University of Helsinki · [Verify](https://studies.cs.helsinki.fi/stats/api/certificate/fullstackopen/en/9eb2299a446d7e2bf6642ef1db80c49f)
- **LLM Zoomcamp** — DataTalks.Club (Credential ID: `6F7D81`)
- **Applied Data Science Lab** — WorldQuant University
- **OCI AI Foundations Associate** — Oracle

---

### Contact

- **Email:** [divyanshneginot@gmail.com](mailto:divyanshneginot@gmail.com)
- **LinkedIn:** [linkedin.com/in/divyanshneginot](https://linkedin.com/in/divyanshneginot)
- **GitHub:** [github.com/Divyanshneginot](https://github.com/Divyanshneginot)
