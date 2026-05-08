# Hassan Laqrabti

**Solutions Architect · DevSecOps Engineer · AI Systems**

Building self-provisioning cloud infrastructure and governed AI systems.

[agenticroam.com](https://agenticroam.com) · [inspiringtrip.com](https://inspiringtrip.com) · laqrabtihassan@gmail.com

---

## What I Build

Production infrastructure that provisions itself — and AI systems that operate within strict governance boundaries.

I own the full surface: Terraform modules, Zero-Trust service mesh, secretless CI/CD, and the Next.js product layer on top. My focus is keeping the technical roadmap aligned with business realities so platforms stay secure, cost-effective, and scale predictably.

---

## Live Platforms

### AgenticRoam — [agenticroam.com](https://agenticroam.com)

Cloud infrastructure automation platform. Enter a domain, choose AWS or Azure — get a complete production-ready environment in under 10 minutes.

**What I built:**

- **Modular Provisioning Engine** — Automates the move from domain purchase to production-ready across AWS and Azure
- **Enterprise Factory CLI** — Bash-based tool using bin-packing density logic to maintain 70%+ hardware profit margins
- **Automated Remediation** — Connected Claude (Amazon Bedrock) to the pipeline to find root causes in logs and trigger automated fixes, achieving under 2 min recovery time
- **Zero-Trust Security** — mTLS 1.3 via Istio + SPIFFE/SPIRE with OIDC federation, eliminating long-lived credentials
- **Resiliency Engineering** — Custom PID-backed idempotency locks and JSON-based rollback staging for safe, concurrent mutations

`Go` `Bash` `Terraform` `Kubernetes` `Istio` `SPIFFE/SPIRE` `AWS` `Azure` `Cloudflare` `GitHub Actions` `Prometheus`

---

### InspiringTrip — [inspiringtrip.com](https://inspiringtrip.com)

AI-powered travel marketplace. Travelers get complete, bookable itineraries; local vendors manage listings and visibility via a dedicated business portal.

**What I built:**

- **Enterprise-Grade Stack** — Built on the AgenticRoam PaaS using a dedicated Amazon EKS cluster for production isolation and performance
- **High-Concurrency Backend** — Go microservice layer using goroutines to pull data from 7+ global APIs in parallel, keeping response times under 350ms
- **Agentic UI** — An autonomous chat system using Claude (Amazon Bedrock) that handles search filters, API queries, and pushes real-time data into Next.js components
- **Dual-Sided Revenue Model** — Tiered structure for B2C travelers and a Business Portal for B2B vendors to manage listings and visibility upgrades
- **Optimized Frontend** — 220+ destination pages using Next.js server components and ISR, achieving sub-100ms LCP (CloudWatch)

`Next.js` `Go` `PostgreSQL` `Amazon Bedrock` `Amazon EKS` `Terraform` `Amadeus API` `Stripe` `Docker` `Redis`

---

## Core Stack

| Layer | Technology |
|---|---|
| Cloud | AWS · Azure |
| IaC / Orchestration | Terraform · Kubernetes (EKS/AKS) · Helm |
| Security | Istio · mTLS 1.3 · SPIFFE/SPIRE · OIDC/IRSA |
| CI/CD | GitHub Actions · Docker · Snyk |
| AI/LLM | Amazon Bedrock (Claude) · Automated Remediation · RAG |
| Backend | Go · Python · FastAPI |
| Frontend | Next.js · TypeScript · GSAP · Three.js |
| Data | PostgreSQL · Redis · Drizzle ORM |
| Observability | Prometheus · Grafana · CloudWatch |

---

## In Progress

- AWS Certified Solutions Architect — Professional *(Exam scheduled: August 2026)*
- **GovernedAgentic** — Enterprise AI governance layer focusing on Bedrock Guardrails and audit trails
