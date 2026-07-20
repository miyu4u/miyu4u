# Hi, I'm miyu4u 👋

**Backend Developer · Node.js / TypeScript**

I'm a backend developer with 7+ years of experience building APIs, data pipelines, external integrations, and long-running asynchronous workflows.

I have built and operated Koa and NestJS services backed by PostgreSQL, MariaDB/MySQL, Redis, and Elasticsearch in Kubernetes environments. In my public projects, I focus on developer tooling—CLI applications, MCP servers, and coding-agent extensions designed to make terminal and agent workflows safer and more predictable.

I design with failure modes in mind: clear input contracts, explicit state transitions, controlled retries and fallbacks, safe credential handling, and a clear boundary between preview and execution.

## Current Focus

- TypeScript and Bun CLI tools with stable contracts and useful diagnostics
- MCP servers and coding-agent extensions for tool discovery and persistent session state
- Kubernetes-based homelab automation

## Featured Projects

- **[recurl](https://github.com/miyu4u/recurl)** — A curl-compatible CLI that preserves native `curl` behavior while adding output conversion, HTML sanitization, network policies, and optional browser rendering.

- **[zido-mcp](https://github.com/miyu4u/zido-mcp)** — A TypeScript MCP server that unifies Kakao, Naver, and Google Maps for place search and geocoding, with ordered provider fallback and stdio/HTTP transports.

- **[pi-extensions-skill-registry](https://github.com/miyu4u/pi-extensions-skill-registry)** — A Pi/OMP extension that indexes `SKILL.md` documents with SQLite FTS5 and BM25, resolves names and aliases, and assembles bounded skill packets for agents.

- **[pi-extensions-security](https://github.com/miyu4u/pi-extensions-security)** — OMP extension that Access Control for command execution, execution result, file access.

- **[pi-extensions-todo](https://github.com/miyu4u/pi-extensions-todo)** — A persistent todo extension for coding-agent sessions, with Markdown-backed state, task trees, dependencies, and model-facing reminders.

- **[toss-invest-cli](https://github.com/miyu4u/toss-invest-cli)** — A Bun and TypeScript CLI for interacting with the Toss Invest OpenAPI from terminal and automation workflows.

- **[oci-freetier-idle-avoider](https://github.com/miyu4u/oci-freetier-idle-avoider)** — A Kubernetes automation project using CronJobs, DaemonSets, and `sysbench` to schedule periodic workloads on OCI Free Tier.

## Tech Stack

- **Backend & Tooling:** Node.js · Bun · TypeScript · NestJS · Koa
- **APIs & Protocols:** REST · GraphQL · MCP
- **Data & Processing:** PostgreSQL · MariaDB/MySQL · Redis · Elasticsearch
- **Build & Delivery:** GitHub Actions · GitLab CI · Jenkins
- **Platform:** Kubernetes · Docker · Oracle Cloud Infrastructure