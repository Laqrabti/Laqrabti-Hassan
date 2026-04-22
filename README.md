# Hassan Laqrabti

Platform Engineer · Solutions Architect · DevSecOps  
Building self-provisioning cloud infrastructure and governed AI systems.

→ [agenticroam.com](https://agenticagile.com) · [inspiringtrip.com](https://inspiringtrip.com/) · laqrabtihassan@gmail.com

---

## What I build

Production infrastructure that provisions itself — and AI 
systems that operate within strict governance boundaries.

I own the full surface: Terraform modules, zero-trust service 
mesh, secretless CI/CD, LLM gateways, and the Next.js product 
layer on top. No handoff to a separate DevOps team, security 
team, or frontend team.

---

## Live platforms

### AgenticRoam — [agenticroam.com](https://agenticagile.com)
Cloud infrastructure automation platform. Enter a domain, 
choose AWS, Azure, or GCP — get a complete production stack 
in under 5 minutes.

**What I built:**
- Modular Terraform provisioning engine — multi-cloud 
  (AWS, Azure, GCP) with per-tenant isolation
- Go/Bash CLI with PID-backed idempotency locks and 
  JSON snapshot rollback — recovery under 2 minutes
- mTLS 1.3 service mesh via Istio + SPIFFE/SPIRE with 
  OIDC/IRSA federation — zero long-lived credentials
- DNS ownership verification via HMAC-signed Cloudflare 
  TXT challenges
- Full observability: Prometheus, Grafana, distributed 
  tracing, structured audit logs
- SOC 2-aligned security posture out of the box

`Go` `Bash` `Terraform` `Kubernetes` `Istio` `SPIFFE/SPIRE` 
`AWS` `Azure` `GCP` `Cloudflare` `GitHub Actions` `Prometheus`

---

### InspiringTrip — [inspiringtrip.com](https://inspiringtrip.com/)
AI-powered travel platform. Two-sided marketplace: 
travelers get AI-planned bookable trips, businesses 
list and get matched to relevant customers automatically.

**What I built:**
- Multi-AZ VPC: ALB, ECS Fargate, RDS (PostgreSQL), 
  ElastiCache Redis — provisioned via Terraform
- 5-stage secretless CI/CD via GitHub Actions + OIDC
- Governed Amazon Bedrock proxy — LLM calls isolated, 
  inputs sanitized, API keys never client-facing
- RAG architecture for contextual travel recommendations
- Amadeus API — live flight search and booking
- Google Maps, Stripe, affiliate partner integrations
- Multi-tenant architecture for traveler and operator profiles
- Multi-stage Docker builds — 62% image reduction
- Zero critical CVEs since launch

`Next.js 15` `FastAPI` `PostgreSQL` `Drizzle ORM` 
`Amazon Bedrock` `ECS Fargate` `Terraform` `Amadeus API` 
`Stripe` `Snyk` `Docker`

---

## Core stack

| Layer | Technology |
|---|---|
| Cloud | AWS · Azure · GCP |
| IaC | Terraform · Helm |
| Orchestration | Kubernetes · ECS Fargate |
| Security | Istio · mTLS 1.3 · SPIFFE/SPIRE · OIDC/IRSA |
| CI/CD | GitHub Actions · Docker · Snyk |
| AI/LLM | Amazon Bedrock · RAG · MCP proxies |
| Backend | Go · Python · FastAPI |
| Frontend | Next.js 15 · TypeScript |
| Data | PostgreSQL · Redis · Drizzle ORM |
| Observability | Prometheus · Grafana · CloudWatch |

---

## In progress

- GovernedAgentic — enterprise AI governance layer: 
  Bedrock Guardrails, audit trails, HITL checkpoints, 
  EU AI Act compliance tooling
- CKA (Certified Kubernetes Administrator)
- AWS Certified Solutions Architect — Professional

---

## Certifications

- AWS Cloud Solutions Architect — Amazon Web Services
- DevOps on AWS — Amazon Web Services
- IBM DevOps and Software Engineering — IBM
- Google Project Management — Google

---

## Education

MS Computer Science — Arizona State University  
*(Distributed Systems · Cloud Computing · In progress)*

Classes Préparatoires Mathematics/Physics — Moulay Abdellah  
*Top 5% nationally in engineering entrance exams*
