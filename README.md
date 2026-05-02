# Leonardo Colangelo

**Cloud & DevOps Engineer · Platform Engineer**  
Building infrastructure that doesn't wake you up at 3am.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/leonardocolangelo/?locale=en)
[![AWS SAA](https://img.shields.io/badge/AWS-Solutions_Architect_Associate-FF9900?style=flat&logo=amazonaws&logoColor=white)](https://aws.amazon.com/certification/certified-solutions-architect-associate/)
[![Azure](https://img.shields.io/badge/Azure-Network_Engineer_Associate-0078D4?style=flat&logo=microsoftazure&logoColor=white)](https://learn.microsoft.com/en-us/certifications/azure-network-engineer-associate/)

---

## What I Actually Do

I design and operate cloud infrastructure at scale — multi-cloud environments, Kubernetes platforms, IaC pipelines, and the observability that makes all of it trustworthy.

My daily stack is **Terragrunt + Azure Verified Modules** on enterprise Azure (hub-spoke architecture, DNS Private Resolver, VPN Gateway, enterprise-scale networking). I'm equally at home on AWS and have production experience on GCP.

I'm not a developer who learned DevOps. I'm infrastructure-first — I think in VNets, IAM boundaries, and blast radius before I think in code.

**What I care about:**
- Infrastructure that's DRY, maintainable, and uses battle-tested modules — not custom reinvented wheels
- Kubernetes platforms that the dev teams *want* to use, not fight against
- Observability baked in from day one, not bolted on after the first incident
- IaC that tells a clear story: Terraform as foundation, Terragrunt as the production evolution

---

## Certifications

| Certification | Provider |
|---|---|
| Solutions Architect – Associate | AWS |
| Network Engineer Associate | Azure |

---

## 🚧 Current Build — Platform Engineering 2026

A production-grade monorepo demonstrating the full Platform Engineering loop.

**`platform-microservices`** — Google's Online Boutique (11-service microservices) deployed on Kubernetes with:
- Helm umbrella chart with subcharts (mirrors real multi-team ownership)
- GitHub Actions CI/CD with OIDC authentication (no long-lived credentials)
- kube-prometheus-stack: Prometheus + Grafana with custom dashboards and alerting rules
- HPA, PodDisruptionBudgets, Network Policies, resource requests/limits

**`cloud-infrastructure`** — Cloud Landing Zone built in two explicit iterations:
- Iteration 1: Plain Terraform + Babenko (`terraform-aws-modules`) — the readable foundation
- Iteration 2: Terragrunt refactor — DRY, environment-composable, production pattern

The Terraform → Terragrunt refactor is an intentional portfolio artifact. It shows the *why*, not just the *how*.

> Architecture Decision Records document every non-obvious choice. Because "we always did it this way" isn't a reason.

---

## Tech Stack

**Cloud**  
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=FF9900)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat&logo=googlecloud&logoColor=white)

**IaC**  
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Terragrunt](https://img.shields.io/badge/Terragrunt-white?style=flat)

**Containers & Orchestration**  
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat&logo=helm&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

**CI/CD**  
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat&logo=azuredevops&logoColor=white)

**Observability**  
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)

---

## GitHub Stats

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=LeonTH096&theme=github_dark" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=LeonTH096&theme=dark&hide_border=true" />
</p>

---

## Outside the Terminal

15 years of consistent training at the gym — the same mindset that builds infrastructure: show up, be consistent, trust the process.

Travelling, reading, and staying genuinely curious about how things work.  
Turin-based. Always open to a technical conversation.
