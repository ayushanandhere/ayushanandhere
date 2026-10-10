# Ayush Anand

**Software Developer 1 at Oracle · Backend & Full-Stack Engineering · Bengaluru, India**

[Portfolio](https://ayushanandhere.vercel.app) · [LinkedIn](https://www.linkedin.com/in/ayush-anand-a5675a223/) · [Email](mailto:ayushanand8575@gmail.com) · [Codeforces](https://codeforces.com/profile/aa008)

I build database-backed applications, APIs, and developer tools. At **Oracle**, I work on enterprise analytics and workflows across application logic, SQL/PL/SQL, and JavaScript. My personal projects extend that work into **Java/Spring Boot**, cloud-hosted AI tools, real-time applications, and concurrent services in Go and C.

I’m interested in software engineering roles focused on backend services, data-intensive applications, and developer infrastructure.

## Engineering at Oracle

- Develop server-side validation and data-processing rules that enforce business constraints and preserve consistency across enterprise workflows.
- Diagnose routing, notification, and validation defects across SQL queries, application processes, and UI behavior; carry fixes through review and release verification.
- Integrate weather data into safety-risk forecasting and build KPI and trend dashboards, coordinating data quality, location mapping, and application behavior.

**Work stack:** SQL, PL/SQL, Oracle Database, JavaScript, Oracle APEX.

## Selected Projects

### [AgentLens](https://github.com/ayushanandhere/AgentLens) — AI Agent Observability & Governance

A Java backend and React dashboard for inspecting agent traces, evaluating policies, and reviewing actions that require operator approval.

- Implements policy checks at trace creation, event ingestion, and completion, with approval/rejection workflows and scoped API-key access.
- Stores traces and violations in PostgreSQL, uses Redis for rate limiting, and publishes audit and lifecycle events through Kafka.
- Includes OpenTelemetry tracing, Micrometer metrics, Flyway migrations, and JUnit/Mockito tests with Testcontainers integration tests.

**Stack:** Java 21, Spring Boot, PostgreSQL, Redis, Kafka, React, TypeScript, Docker Compose.  
[Code & setup](https://github.com/ayushanandhere/AgentLens) · [Architecture](https://github.com/ayushanandhere/AgentLens/blob/main/docs/architecture.md)

### [DeployLens](https://github.com/ayushanandhere/deploylens) — Deployment Investigation Assistant

A deployed tool that combines deterministic log analysis with streamed AI guidance, keeping source evidence separate from unconfirmed hypotheses.

- Persists conversations, logs, and investigation state with Cloudflare Durable Objects and SQLite; exports findings as Markdown handoffs.
- Enforces GitHub sign-in and ownership checks across HTTP, WebSocket, and RPC paths, with shared model-request quotas and session expiry.
- Includes automated tests and GitHub Actions checks for TypeScript, tests, and production builds.

**Stack:** TypeScript, React, Cloudflare Workers, Agents SDK, Workers AI, SQLite, Vitest.  
[Try the demo](https://deploylens.ayushanandhere.workers.dev/) · [Code & design notes](https://github.com/ayushanandhere/deploylens)

### [HireMe](https://github.com/ayushanandhere/HireMe) — Real-Time Hiring Platform

An end-to-end application for job applications, screening, interview preparation, video interviews, and recruiter feedback.

- Connects candidate and recruiter workflows through shared application state, submission-time profile snapshots, and role-based REST APIs.
- Supports JWT/Google OAuth authentication, authenticated Socket.IO notifications, and WebRTC video interviews.
- Integrates resume parsing and contextual interview preparation, while keeping core workflows available without an AI API key.

**Stack:** React, Node.js, Express, MongoDB, Socket.IO, WebRTC, OpenAI API, Docker Compose.  
[Code & walkthrough](https://github.com/ayushanandhere/HireMe)

### More Engineering Projects

| Project | Engineering focus |
| --- | --- |
| [GoProbe](https://github.com/ayushanandhere/GoProbe) | HTTP/TCP monitoring in **Go** using per-target goroutines, channels, rolling health history, authenticated API mutations, and graceful shutdown. |
| [CacheThreader](https://github.com/ayushanandhere/CacheThreader) | Concurrent HTTP proxy in **C** using POSIX sockets, pthreads, semaphores, and a mutex-protected, size-bounded LRU cache. |
| [Virtual Doctor](https://github.com/ayushanandhere/Virtual-Doctor) | **Python RAG prototype** over PDF documents using LangChain, sentence-transformer embeddings, FAISS, Llama 2, and Chainlit. |

## Technologies

| Area | Technologies used in my work and projects |
| --- | --- |
| Languages | Java, TypeScript, JavaScript, SQL, PL/SQL, Go, C, C++, Python |
| Backend & data | Spring Boot, Spring Data JPA, Node.js, Express, PostgreSQL, Oracle Database, MongoDB, SQLite, Redis, Kafka |
| Frontend & real-time | React, HTML/CSS, Tailwind CSS, Socket.IO, WebRTC |
| Cloud & tooling | Cloudflare Workers, Durable Objects, Docker, Docker Compose, Git, GitHub Actions, Linux |
| Testing & observability | JUnit, Mockito, Testcontainers, Vitest, OpenTelemetry, Micrometer, Jaeger |
| Applied AI | Workers AI, OpenAI API, LangChain, FAISS, retrieval-augmented generation |

## Competitive Programming

- **Codeforces Candidate Master** — peak rating **1948** · [aa008](https://codeforces.com/profile/aa008)
- **CodeChef 4★** — peak rating **1987** · [ci008](https://www.codechef.com/users/ci008)
- **ICPC 2024 Asia Chennai Onsite Regional** — team rank **86**, BitByeBit · [ICPC profile](https://icpc.global/ICPCID/P1UTEG816DHV)
- **Meta Hacker Cup 2024** — qualified for **Round 2** · [Certificate](https://www.facebook.com/codingcompetitions/hacker-cup/2024/certificate/357856790084272)

## Education & Certifications

**B.E., Computer Science & Engineering (AI & ML)**  
Ramaiah Institute of Technology, Bengaluru · Class of 2025 · **CGPA: 9.70/10**

- [Oracle Cloud Infrastructure 2024 Certified AI Foundations Associate](https://catalog-education.oracle.com/ords/certview/sharebadge?id=E7C82B07BA8330494AC0F513B8D9B3C9E4A3F9439B64AB73F1E3224688C658BF)
- [Oracle APEX Cloud Certified Developer Professional](https://catalog-education.oracle.com/ords/certview/sharebadge?id=775D3954C27554C98047E88E05C016BFDD8AF62DF58EE9A1A8E0C0C5AF7DF7AC)

---

For software engineering opportunities or project discussions, reach me at **[ayushanand8575@gmail.com](mailto:ayushanand8575@gmail.com)** or on **[LinkedIn](https://www.linkedin.com/in/ayush-anand-a5675a223/)**. More about my work: **[ayushanandhere.vercel.app](https://ayushanandhere.vercel.app)**.
