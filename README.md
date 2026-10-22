# Vikrant Jain

Architect and engineer with 20+ years building identity platforms, workflow engines, and multi-tenant systems

---

## About

I've spent most of my career deep in identity management and enterprise platforms — designing orchestration engines, metering systems, and multi-tenant architectures at Oracle and Avalara. Three of those designs became US patents.

More recently, I've been working at the intersection of AI and architecture. I use agentic frameworks like LangGraph and CrewAI not as experiments but as part of how I work — from red-teaming AI agents against OWASP LLM guidelines to generating architecture documents that pass formal review boards. I treat AI as a second engineer in the workflow, not a novelty.

Currently consulting independently, building open source tooling around MCP servers, and writing about architecture practices on my blog.

---

## Tech Stack

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

**AI & Agentic**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white)
![CrewAI](https://img.shields.io/badge/CrewAI-FF6B6B?style=flat)
![MCP](https://img.shields.io/badge/MCP-5A67D8?style=flat)
![Cursor](https://img.shields.io/badge/Cursor-000000?style=flat&logo=cursor&logoColor=white)

**Frameworks**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=spring&logoColor=white)
![RxJava](https://img.shields.io/badge/RxJava-B7178C?style=flat&logo=reactivex&logoColor=white)
![Dropwizard](https://img.shields.io/badge/Dropwizard-44A833?style=flat)

**Cloud & Infrastructure**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat&logo=terraform&logoColor=white)

**Workflow & BPM**

![Camunda](https://img.shields.io/badge/Camunda-FC5D0D?style=flat&logo=camunda&logoColor=white)
![Node-RED](https://img.shields.io/badge/Node--RED-8F0000?style=flat&logo=nodered&logoColor=white)
![N8n](https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white)

**Security & Identity**

![Keycloak](https://img.shields.io/badge/Keycloak-4D4D4D?style=flat&logo=keycloak&logoColor=white)
![OAuth2](https://img.shields.io/badge/OAuth2%2FOIDC-3C3C3C?style=flat)
![HashiCorp Vault](https://img.shields.io/badge/Vault-FFEC6E?style=flat&logo=vault&logoColor=black)

**Data & Messaging**

![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat&logo=redis&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat&logo=elasticsearch&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle_DB-F80000?style=flat&logo=oracle&logoColor=white)

**Observability**

![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)

---

## Featured Projects

### [profile-builder](https://github.com/vikrantjain/profile-builder)

A Claude Code plugin for managing professional profiles with AI. Collects data from multiple sources, generates a structured profile document, and exports platform-ready content for LinkedIn, GitHub, and tailored resumes.

- Built as a full plugin with skills for initialization, section management, validation, and multi-platform export
- Demonstrates practical AI-augmented tooling — using Claude Code's plugin system to solve a real workflow problem

### [mcp-high-availability](https://github.com/vikrantjain/mcp-high-availability)

High availability setup for stateful MCP servers using HAProxy sticky sessions, Redis-backed state, and automatic failover.

- Addresses a real gap in MCP infrastructure — stateful servers need session affinity and resilience patterns that don't exist out of the box
- Combines HAProxy, Redis, and health-check-driven failover into a working reference architecture

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat&logo=redis&logoColor=white)

### [mcp-oauth-proxy-demo](https://github.com/vikrantjain/mcp-oauth-proxy-demo)

Sample FastMCP server demonstrating the OAuth Proxy pattern for Keycloak authentication without Dynamic Client Registration support.

- Solves a common pain point — many Keycloak deployments don't enable DCR, making standard MCP OAuth flows unusable
- Provides a working proxy pattern that bridges the gap

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Keycloak](https://img.shields.io/badge/Keycloak-4D4D4D?style=flat&logo=keycloak&logoColor=white)

---

## Patents

- [**US10585682B2**](https://patents.google.com/patent/US10585682B2) — Tenant self-service troubleshooting for multi-tenant cloud services
- [**US9391972B2**](https://patents.google.com/patent/US9391972B2) — Hierarchical bean factory containers for multi-tenant applications
- [**US8554798B2**](https://patents.google.com/patent/US8554798B2) — Asynchronous state engine with plug-ins for flexible development

---

## Recent Blog Posts

- [Verifiable Credentials Are Ready. Are We?](https://vikrantjain.dev/verifiable-credentials-are-ready/) — Sharing only what a check needs, not the whole ID
- [Your AI Agent Will Carry Out a Weak Plan Very Well](https://vikrantjain.dev/collaborate-with-your-ai-agent/) — Why handing an agent orders fails, and what to do instead
- [I Ran Three Claude Code Agents as Three Teams — and They Shipped a Real Feature](https://vikrantjain.dev/three-claude-code-instances-one-feature/) — Splitting one feature across three agents, by service boundary
- [A Coding Agent Is Not an IDE](https://vikrantjain.dev/coding-agent-is-not-an-ide/) — Why dropping an AI tool on every laptop doesn't deliver 10x
- [I Cut My AI Coding Agent's Cost by 60% — By Watching What It Actually Does](https://vikrantjain.dev/profiling-claude-code-sessions-cut-cost-60-percent/) — Profiling agent sessions to find where the tokens go

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vikrantj)
[![Blog](https://img.shields.io/badge/Blog-The%20Architect%27s%20Ledger-2962FF?style=flat&logo=rss&logoColor=white)](https://vikrantjain.dev)
