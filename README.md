## Hi, I'm Athithya 👋

I'm a GenAI & DevOps Engineer based in Chennai, focused on building and deploying reliable AI systems and cloud-native infrastructure.

I build **production-oriented AI systems**, spanning application development, infrastructure, and observability, with a focus on security, scalability, and cost efficiency.

I believe building software goes beyond making things work. I emphasize rigorous engineering validation through automated testing, code quality checks, integration testing, evaluation-gated CI/CD pipelines, API contract verification, and safety testing.

**Build with AI. Validate with rigor. Deliver with confidence.**

---

## Core Technical Skills

 - **Cloud & Platform Engineering:**      AWS · Azure · Kubernetes · Docker · Terraform · Argo CD · Argo Rollouts · Karpenter

 - **GenAI & LLMOps :**      AWS Bedrock · RAG · GraphRAG · AI Agents · Evaluation harness · LangGraph · OpenInference

 - **Observability & Monitoring:**     Prometheus · Grafana · OpenTelemetry · OpenObserve

 - **Programming & Data:**     Python · SQL

---

## Projects & Impact

Selected engineering projects demonstrating end-to-end engineering, infrastructure automation, AI integration, and measurable engineering outcomes.

| Project | What it is | Outcomes |
|---|---|---|
| **[AutoSRE](https://github.com/Athithya-Sakthivel/AutoSRE)** | Event-driven autonomous SRE agent for Kubernetes that diagnoses incidents from telemetry, executes tiered remediation with human approval for high-risk actions, and verifies recovery. | 12/14 incidents resolved · 0 safety violations · ~98% MTTR reduction · $0.02 per incident |
| **[RAG8s](https://github.com/Athithya-Sakthivel/RAG8s)** | LLMOps platform for RAG on EKS, with separate streaming inference and batch indexing pipelines, Karpenter-managed Spot compute, GitOps/IaC delivery, OIDC authentication, per-user rate limiting, and full-stack observability. | Groundedness: 0.95 · Recall@5: 0.72 · Citation integrity: 0.89 · End-to-end latency: 2.6s · 5 req/min per user · 24 alert rules |
| **[Legal GraphRAG](https://github.com/Athithya-Sakthivel/legal-graphrag)** | Complementary retrieval-engineering project to RAG8s, combining structure-aware chunking, hybrid search, and PostgreSQL citation-graph traversal across 9.5K US case-law opinions. | 0.9158 macro Recall@10 · 0.8878 macro nDCG@10 · 150 stratified evaluation queries |
| **[aks-canary-platform](https://github.com/Athithya-Sakthivel/aks-canary-platform)** | Self-healing canary deployment platform on AKS (0% → 10% → 100%), using Argo Rollouts to automatically roll back failed k6/Playwright validations. | Automated rollback on failed canaries · 0 manual interventions · 0 long-lived secrets · 8 security controls |
| **[TicketWeave](https://github.com/Athithya-Sakthivel/TicketWeave)** | AI-powered ticket triage for e-commerce support teams on Amazon ECS, combining deterministic routing with a five-layer security architecture. | ~$23/month in staging · Sub-5ms inline RAG · 0 critical/high DAST findings · CI reduced from 8m to 2m40s through dependency caching |

---

> All metrics are measured in self-managed development and staging environments, not production. Results are environment-specific. Each repository documents its evaluation methodology, measurement context, setup instructions, design trade-offs, and limitations.

---

## Let's Connect

Always happy to discuss GenAI systems, cloud infrastructure, platform engineering, or opportunities.

- LinkedIn: [athithya-sakthivel](https://www.linkedin.com/in/athithya-sakthivel-a23062341/)
- Email: [athithya651@gmail.com](mailto:athithya651@gmail.com)
