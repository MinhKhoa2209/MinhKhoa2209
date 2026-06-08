<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=280&color=0:0D1117,30:0a1628,60:0f2447,85:1a3a6e,100:1d4ed8&text=Minh%20Khoa&fontColor=E2E8F0&fontSize=72&fontAlignY=40&fontAlign=50&desc=Cloud%20%26%20Platform%20Engineer%20%E2%80%94%20Building%20Production-Grade%20Systems&descSize=17&descAlignY=60&descAlign=50&descColor=94A3B8&animation=fadeIn&stroke=1d4ed8&strokeWidth=0" alt="Minh Khoa" />
</p>

<p align="center">
  <a href="https://github.com/MinhKhoa2209">
    <img src="https://img.shields.io/badge/GitHub-MinhKhoa2209-0f172a?style=flat-square&logo=github&logoColor=white&labelColor=0f172a&color=1d4ed8" />
  </a>
  &nbsp;
  <a href="mailto:minhkhoa2209@gmail.com">
    <img src="https://img.shields.io/badge/Email-minhkhoa2209@gmail.com-0f172a?style=flat-square&logo=gmail&logoColor=white&labelColor=0f172a&color=0891b2" />
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/khoa-minh-927139298/">
    <img src="https://img.shields.io/badge/LinkedIn-Dinh%20Minh%20Khoa-0f172a?style=flat-square&logo=linkedin&logoColor=white&labelColor=0f172a&color=0a66c2" />
  </a>
  &nbsp;
  <img src="https://komarev.com/ghpvc/?username=MinhKhoa2209&style=flat-square&color=1d4ed8&label=Profile+Views&labelColor=0f172a" />
</p>

<br/>

---

<br/>

<!-- TYPING ANIMATION -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&multiline=false&repeat=true&width=700&height=45&lines=AWS+%E2%80%A2+Terraform+%E2%80%A2+Kubernetes+%E2%80%A2+TypeScript;Infrastructure+as+Code+%7C+Platform+Engineering;Container+Orchestration+%7C+Backend+Systems;Building+systems+that+scale+beyond+prototypes" alt="Typing SVG" />
</p>

<br/>

---

<br/>

## About

Software Engineering student based in Da Nang, Vietnam. I design and build cloud infrastructure, backend systems, and data pipelines using the same tooling you'd find in production at a mid-to-large tech company — Terraform modules with remote state, ECS-deployed microservices, PostgreSQL schemas that enforce business rules in the database layer, and ML pipelines with proper async job queues.

My work is defined by one constraint: **it has to actually deploy**. Every project ships with infrastructure code, migration scripts, Docker Compose stacks for local parity, and observable output — not just a Figma screenshot.

Currently targeting Cloud / Platform / Backend engineering roles where infrastructure, systems design, and delivery practices are first-class concerns.

<br/>

---

<br/>

## Core Expertise

<table>
  <tr>
    <td valign="top" width="50%">

### ☁ Cloud Infrastructure
Terraform-managed AWS environments across VPC, ECS, CloudFront, Lambda, and DocumentDB. Multi-tier networking with private subnets, WAF, VPC endpoints, and Secrets Manager integration. Remote state backends and modular IaC design.

`AWS` `Terraform` `CloudFront` `ECS` `Lambda` `WAF` `VPC`

    </td>
    <td valign="top" width="50%">

### ⚙ Backend Engineering
TypeScript/Node.js and Python/FastAPI service layers with a SQL-first repository pattern. Business logic pushed into the database layer via PL/pgSQL triggers, row-level security, and materialized views. REST API design with typed contracts.

`TypeScript` `Node.js` `FastAPI` `Express.js` `PostgreSQL` `PL/pgSQL`

    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">

### 🚀 DevOps & Container Platforms
Docker Compose stacks designed for production parity. Kubernetes workloads including deployments, services, ingress, and HPA. GitHub Actions pipelines for container builds and automated cloud deployments. Health check patterns and graceful shutdown.

`Docker` `Kubernetes` `GitHub Actions` `Docker Compose` `ECR`

    </td>
    <td valign="top" width="50%">

### 🗄 Database Systems
Advanced PostgreSQL: pgvector for semantic search, RLS for multi-tenant access, JSONB audit trails, Alembic migrations, and concurrent stock locking. Vector similarity search with local and cloud-hosted embedding models.

`PostgreSQL` `pgvector` `Redis` `MongoDB` `MinIO` `Alembic`

    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">

### 🤖 AI & ML Systems
End-to-end ML pipelines: async training jobs via Celery, hyperparameter tuning with Optuna, SHAP explainability, and model artifact storage in MinIO. Semantic search via CLIP/BLIP embeddings and AWS Bedrock RAG endpoints.

`scikit-learn` `Optuna` `SHAP` `CLIP` `BLIP` `AWS Bedrock` `Ollama`

    </td>
    <td valign="top" width="50%">

### 🌐 Full-Stack Delivery
React and Next.js frontends with TypeScript, Zustand state management, and Sanity CMS. Stripe Checkout with webhook-driven order flows. Clerk auth with RBAC. Deployments to Vercel with production-ready configurations.

`React` `Next.js` `Tailwind CSS` `Zustand` `Sanity` `Stripe` `Clerk`

    </td>
  </tr>
</table>

<br/>

---

<br/>

## Featured Projects

<table>
  <tr>
    <td valign="top" width="50%">

### [AWS Infrastructure Accelerator](https://github.com/MinhKhoa2209/AWS)

Production-grade AWS environment provisioned end-to-end with Terraform — multi-tier VPC, CloudFront + WAF edge delivery, ECS/ECR compute, DocumentDB data layer, and a Lambda + Bedrock RAG endpoint. Every module ships with CloudWatch observability and Secrets Manager integration.

`Terraform` `AWS ECS` `CloudFront` `WAF` `Lambda` `Bedrock` `DocumentDB`

[![View Repo](https://img.shields.io/badge/Repo-AWS-FF9900?style=flat-square&logo=github&logoColor=white)](https://github.com/MinhKhoa2209/AWS)
[![Part 2](https://img.shields.io/badge/Repo-Accelerator%20P2-FF9900?style=flat-square&logo=github&logoColor=white)](https://github.com/MinhKhoa2209/minhkhoa-aws-accelerator-p2)

    </td>
    <td valign="top" width="50%">

### [Smart Logistics — WMS](https://github.com/MinhKhoa2209/smart-logistics)

Warehouse management system built database-first. Business rules live in PL/pgSQL — inventory triggers, concurrent row locking, materialized views, JSONB audit diffs, and RLS access control. pgvector + Ollama power semantic product search.

`PostgreSQL 17` `PL/pgSQL` `pgvector` `TypeScript` `Express.js` `Ollama` `Docker`

[![View Repo](https://img.shields.io/badge/Repo-smart--logistics-4169E1?style=flat-square&logo=github&logoColor=white)](https://github.com/MinhKhoa2209/smart-logistics)

    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">

### [SemaMedia — AI Media Search](https://github.com/MinhKhoa2209/SemaMedia)

Dockerized microservice stack for semantic media indexing. Uploaded images and videos flow through scene extraction → BLIP captioning → CLIP embedding → pgvector storage. GPU-aware workers with CPU fallback. Smoke tests cover the full pipeline.

`Python` `CLIP` `BLIP` `pgvector` `PostgreSQL` `Docker Compose` `React`

[![View Repo](https://img.shields.io/badge/Repo-SemaMedia-0891b2?style=flat-square&logo=github&logoColor=white)](https://github.com/MinhKhoa2209/SemaMedia)

    </td>
    <td valign="top" width="50%">

### [ChurnPrediction — ML Platform](https://github.com/MinhKhoa2209/ChurnPrediction)

Full ML lifecycle platform: upload → preprocess → train → explain → predict. Celery + Redis handle async training jobs. Optuna drives hyperparameter search. SHAP generates per-prediction waterfall explanations. RBAC separates Admin and Analyst access.

`FastAPI` `Celery` `Redis` `scikit-learn` `Optuna` `SHAP` `MinIO` `Next.js`

[![View Repo](https://img.shields.io/badge/Repo-ChurnPrediction-f59e0b?style=flat-square&logo=github&logoColor=white)](https://github.com/MinhKhoa2209/ChurnPrediction)

    </td>
  </tr>
  <tr>
    <td valign="top">

### [TrendyFit — E-commerce Storefront](https://github.com/MinhKhoa2209/TrendyFit_Ecommerce)

Production Next.js commerce app: Sanity CMS for content, Clerk for auth and session management, Stripe Checkout with webhook-driven order state, and Zustand cart. Live on Vercel. Typed product and order models are shared across server actions and API routes.

`Next.js` `TypeScript` `Sanity` `Clerk` `Stripe` `Zustand` `Vercel`

[![View Repo](https://img.shields.io/badge/Repo-TrendyFit-6d28d9?style=flat-square&logo=github&logoColor=white)](https://github.com/MinhKhoa2209/TrendyFit_Ecommerce)
[![Live Demo](https://img.shields.io/badge/Live-trendyfit.vercel.app-10b981?style=flat-square&logo=vercel&logoColor=white)](https://trendyfit.vercel.app)

    </td>
    <td valign="top">

### [g8-costctl — AWS Cost Control CLI](https://github.com/MinhKhoa2209/g8-costctl)

Python CLI tool built during an AWS Hackathon for real-time AWS cost visibility. Queries Cost Explorer, analyses resource tagging coverage, and surfaces budget alert status — designed as a portable ops tool for cloud cost governance.

`Python` `AWS Cost Explorer` `AWS Budgets` `CLI` `Boto3`

[![View Repo](https://img.shields.io/badge/Repo-g8--costctl-FF9900?style=flat-square&logo=github&logoColor=white)](https://github.com/MinhKhoa2209/g8-costctl)
[![Hackathon](https://img.shields.io/badge/Event-AWS%20Hackathon-FF6B35?style=flat-square&logo=amazonaws&logoColor=white)](https://github.com/MinhKhoa2209/Hackathon_AWS)

    </td>
  </tr>
</table>

<br/>

---

<br/>

## Engineering Highlights

<table>
  <tr>
    <td align="center" width="33%">
      <strong>Infrastructure as Code</strong><br/>
      <sub>Terraform module libraries with variable validation, remote S3 state, and Atlantis-style workflow patterns. No click-ops.</sub>
    </td>
    <td align="center" width="33%">
      <strong>Cloud Architecture</strong><br/>
      <sub>Multi-tier VPC design, private networking, WAF rule groups, CloudFront distributions, and IAM least-privilege scoping.</sub>
    </td>
    <td align="center" width="33%">
      <strong>Database-First Design</strong><br/>
      <sub>Business logic in PL/pgSQL, not just application code. Row-level security, concurrent locking, materialized views, vector search.</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%">
      <strong>Container Platforms</strong><br/>
      <sub>Production-parity Docker Compose stacks, multi-stage Dockerfiles, health checks, graceful shutdown, and ECS task definitions.</sub>
    </td>
    <td align="center" width="33%">
      <strong>Async ML Pipelines</strong><br/>
      <sub>Celery worker pools with Redis broker, Optuna HPO, SHAP explainability, artifact versioning, and RBAC-gated model management.</sub>
    </td>
    <td align="center" width="33%">
      <strong>Delivery Practices</strong><br/>
      <sub>Migration scripts, environment separation, structured CloudWatch logs, validation evidence, and smoke test coverage from day one.</sub>
    </td>
  </tr>
</table>

<br/>

---

<br/>

## GitHub Dashboard

<p align="center">
  <img height="175" src="https://github-readme-stats.vercel.app/api?username=MinhKhoa2209&show_icons=true&theme=github_dark&hide_border=true&rank_icon=github&include_all_commits=true&count_private=true&bg_color=0d1117&title_color=38bdf8&icon_color=1d4ed8&text_color=94a3b8" alt="GitHub Stats" />
  &nbsp;&nbsp;
  <img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MinhKhoa2209&layout=compact&theme=github_dark&hide_border=true&langs_count=8&bg_color=0d1117&title_color=38bdf8&text_color=94a3b8" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=MinhKhoa2209&theme=github-dark-blue&hide_border=true&date_format=M%20j%5B%2C%20Y%5D&background=0D1117&ring=1D4ED8&fire=38BDF8&currStreakLabel=38BDF8&sideLabels=94A3B8&currStreakNum=E2E8F0&sideNums=E2E8F0&dates=64748B" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=MinhKhoa2209&bg_color=0d1117&color=38bdf8&line=1d4ed8&point=e2e8f0&area=true&hide_border=true&area_color=1d4ed820" alt="Contribution Graph" />
</p>

<br/>

---

<br/>

## Current Focus

> Actively building toward production-grade Cloud / Platform engineering roles.

| Area | Status | Target |
|---|---|---|
| **Kubernetes** | Deployments, services, ingress, HPA | Production workload management |
| **Terraform Advanced** | Module composition, remote state, drift detection | Multi-account org patterns |
| **AWS Solutions Architect** | SAA-C03 preparation | Associate certification |
| **Platform Engineering** | Internal tooling, developer platforms | IDP design patterns |
| **Distributed Systems** | Event-driven architecture, tracing, reliability | Production-grade resilience |

<br/>

---

<br/>

## Let's Connect

Building cloud infrastructure, backend systems, or platform tooling? Open to **engineering internships** and **Cloud / Backend / Platform roles** where delivery and technical depth matter.

<p align="left">
  <a href="mailto:minhkhoa2209@gmail.com">
    <img src="https://img.shields.io/badge/Email-minhkhoa2209@gmail.com-0f172a?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0f172a&color=ea4335" />
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/khoa-minh-927139298/">
    <img src="https://img.shields.io/badge/LinkedIn-Dinh%20Minh%20Khoa-0f172a?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0f172a&color=0a66c2" />
  </a>
  &nbsp;
  <a href="https://github.com/MinhKhoa2209">
    <img src="https://img.shields.io/badge/GitHub-MinhKhoa2209-0f172a?style=for-the-badge&logo=github&logoColor=white&labelColor=0f172a&color=1d4ed8" />
  </a>
</p>

<br/>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:1d4ed8,50:0891b2,100:0d1117&section=footer&reversal=false" alt="footer" />
</p>
