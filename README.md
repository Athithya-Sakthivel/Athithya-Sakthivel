## Hi, I'm Athithya 👋

I'm an early-career GenAI & DevOps Engineer based in Chennai, currently pursuing my final-semester B.Tech in Artificial Intelligence & Data Science.

I build and deploy **production-oriented AI systems** — the application, the infrastructure, and the observability that keeps them operable — secure, scalable, and cost-conscious by design.

**Infra & platform:** Python · Kubernetes · Docker · Terraform · Argo CD/Rollouts · AWS & Azure · Prometheus/Grafana

**GenAI:** AWS Bedrock · RAG · AI agents · Evaluation · OpenTelemetry

**Open to internships in** AI, Cloud, DevOps, MLOps, and SRE. 

---

## Projects & Impact

Selected engineering projects, with measurable outcomes and documented trade-offs.

| Project | What it is | Outcomes |
|---|---|---|
| **[AutoSRE](https://github.com/Athithya-Sakthivel/AutoSRE)** | Event-driven autonomous SRE agent for Kubernetes — diagnoses from telemetry, tiered remediation with human approval for high-risk actions, verifies recovery | 12/14 incidents resolved · 0 safety violations · ~98% MTTR reduction · $0.02 per incident |
| **[aks-canary-platform](https://github.com/Athithya-Sakthivel/aks-canary-platform)** | Self-healing canary deployments on AKS (0% → 10% → 100%), where Argo Rollouts automatically rolls back failed k6/Playwright validations | Auto-rollback on failed canary · 0 manual interventions · 0 long-lived secrets · 8 security controls |
| **[RAG8s](https://github.com/Athithya-Sakthivel/RAG8s)** | LLMOps platform for RAG on EKS: streaming inference and batch indexing planes across eight application and connectivity units, with Karpenter-managed Spot compute, GitOps + IaC delivery, OIDC auth with per-user rate limits, and full-stack observability and security | Groundedness: 0.95 · Recall@5: 0.72 · Citation integrity: 0.89 · End-to-end latency: 2.6s · LLM rate limit: 5 req/min per user · 24 alert rules |
| **[Legal GraphRAG](https://github.com/Athithya-Sakthivel/legal-graphrag)** | Retrieval-layer companion to RAG8s — isolates structure-aware parent-child chunking and native PostgreSQL citation graphs over 9.5K US case law opinions to break the fixed-window recall ceiling on highly connected corpora | **0.91 average Recall@10** (vs 0.72 on flat chunking) · sub-250ms p95 latency · single PostgreSQL backend · 150 stratified queries with 95% bootstrap CIs |
| **[TicketWeave](https://github.com/Athithya-Sakthivel/TicketWeave)** | AI-powered ticket triage for e-commerce support teams on Amazon ECS — deterministic routing, 5-layer security architecture | ~$23/month in staging · sub-5ms inline RAG · 0 critical/high DAST findings · CI **8m → 2m40s** via dependency caching |

---

> *All reported metrics and results are measured in self-managed development and staging environments, not production. Results are environment-specific. Each repository documents its evaluation methodology, measurement context, setup instructions, design trade-offs, and known limitations.*

---

## Let's connect

Always happy to talk about GenAI systems, cloud infrastructure, or opportunities.

- LinkedIn: [athithya-sakthivel](https://www.linkedin.com/in/athithya-sakthivel-a23062341/)
- Email: [athithya651@gmail.com](mailto:athithya651@gmail.com)
