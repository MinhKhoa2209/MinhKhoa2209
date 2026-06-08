<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=240&color=0:0D1117,40:1e3a5f,70:2563EB,100:14B8A6&text=Minh%20Khoa&fontColor=FFFFFF&fontSize=60&fontAlignY=38&desc=Software%20Engineering%20Student%20%7C%20Cloud%20%26%20Full-Stack%20Developer&descSize=19&descAlignY=58&animation=fadeIn" alt="Minh Khoa — Software Engineering Student" />
</p>

<p align="center">
  <a href="https://github.com/MinhKhoa2209">
    <img src="https://img.shields.io/badge/GitHub-MinhKhoa2209-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  &nbsp;
  <a href="mailto:your-email@example.com">
    <img src="https://img.shields.io/badge/Email-Contact%20Me-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/your-linkedin-username">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;
  <a href="https://minhkhoa2209.github.io/Mixi_Shop/">
    <img src="https://img.shields.io/badge/Live%20Demo-Mixi%20Shop-14B8A6?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Demo" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=MinhKhoa2209&style=for-the-badge&color=2563EB&label=Profile+Views" alt="Profile views" />
</p>

---

## 👋 About Me

> *I build systems where cloud infrastructure, backend logic, databases, and frontend all fit together coherently — not just demos.*

I'm a **Software Engineering student** with a strong focus on **cloud-native full-stack development**. My work spans Terraform-managed AWS infrastructure, containerised microservices, PostgreSQL-heavy backends, and ML/AI pipelines that go beyond prototype screens into real, deployable workflows.

- 🚀 Currently deepening: **AWS**, **Terraform**, **Kubernetes**, **Docker**, **System Design**
- 🧠 I care about: **infrastructure as code**, **database correctness**, **clean architecture**, and **developer experience**
- 🌱 Always shipping: production-style projects with explicit infra, real migrations, and validation evidence
- 💼 Open to: **software engineering internships**, cloud/full-stack roles, and technical collaboration

---

## 🛠️ Tech Stack

### ☁️ Cloud & Infrastructure
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI%2FCD-2088FF?style=flat-square&logo=githubactions&logoColor=white)

### 💻 Languages & Frameworks
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)

### 🗄️ Data & Storage
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72C48?style=flat-square&logo=minio&logoColor=white)

### 🤖 AI / ML
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![AWS Bedrock](https://img.shields.io/badge/AWS%20Bedrock-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square)

### 🎨 Frontend & UI
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-433e38?style=flat-square)
![Sanity](https://img.shields.io/badge/Sanity-F03E2F?style=flat-square&logo=sanity&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![Clerk](https://img.shields.io/badge/Clerk-6C47FF?style=flat-square&logo=clerk&logoColor=white)

---

## 🚀 Featured Projects

### 🟠 AWS Infrastructure Accelerator
> **Production-style AWS environment built end-to-end with Terraform**

**Architecture & Logic:**
The infrastructure is modelled as layered Terraform modules — networking first (multi-tier VPC with public, firewall, private-app, and private-data subnets), then edge delivery (CloudFront + S3 + WAF), then compute (ECS + ECR with private ALB), and finally data (DocumentDB, EFS, DMS from MongoDB Atlas). A Lambda + AWS Bedrock RAG endpoint enables AI-augmented query flows. Every module is validated with CloudWatch logs, Secrets Manager integration, and AWS Backup evidence.

**UI/UX Approach:** Infrastructure is the "UI" — deployment evidence docs, structured Terraform outputs, and clear module boundaries are the developer experience deliverable. Human-readable variable naming and logical resource grouping make infra self-documenting.

| Layer | Technologies |
|---|---|
| Networking | VPC, Multi-subnet tiers, VPC Endpoints |
| Edge | CloudFront, WAF, S3 |
| Compute | ECS, ECR, Private ALB, Lambda |
| Data | DocumentDB, DMS, EFS, AWS Backup |
| AI | Lambda + Bedrock RAG |
| Observability | CloudWatch, Secrets Manager |

[![Repo](https://img.shields.io/badge/Repo-AWS-FF9900?style=flat-square&logo=github)](https://github.com/MinhKhoa2209/AWS)
[![Repo P2](https://img.shields.io/badge/Repo-AWS%20Accelerator%20P2-FF9900?style=flat-square&logo=github)](https://github.com/MinhKhoa2209/minhkhoa-aws-accelerator-p2)

---

### 🏭 Smart Logistics — Warehouse Management System
> **Warehouse platform designed around advanced PostgreSQL features, not just application-layer logic**

**Architecture & Logic:**
The system flips the conventional approach: business rules live *in the database* — PL/pgSQL triggers for inventory automation, row-level locking for concurrent stock transfers, materialized views for reporting, JSONB audit diffs, and RLS-backed access control. The application layer (Express/TypeScript) is kept intentionally thin with a SQL-first repository pattern. pgvector + local Ollama embeddings power semantic product search.

**UI/UX Approach:** React + Vite frontend with component-driven layout. The UI surfaces warehouse operations (inventory, transfers, audit logs) with clean data tables, status badges, and role-aware views. Docker Compose makes the local dev stack reproduce production parity.

| Layer | Technologies |
|---|---|
| Frontend | React, Vite, TypeScript |
| Backend | Express.js, TypeScript |
| Database | PostgreSQL 17, PL/pgSQL, pgvector, RLS |
| AI Search | Ollama embeddings, vector similarity |
| DevOps | Docker Compose |

[![Repo](https://img.shields.io/badge/Repo-smart--logistics-4169E1?style=flat-square&logo=github)](https://github.com/MinhKhoa2209/smart-logistics)

---

### 🔍 SemaMedia — Semantic AI Media Search Platform
> **AI-powered media indexing & hybrid semantic search for images and videos**

**Architecture & Logic:**
A Dockerized microservice stack — API gateway, media worker, search API, and shared service layer — processes uploaded media through a multi-stage pipeline: scene extraction → BLIP caption generation → CLIP embedding → pgvector storage. The GPU-aware worker handles model warmup and CPU/GPU runtime switching. Smoke tests validate the full pipeline from upload to retrieval.

**UI/UX Approach:** React + TypeScript frontend with a media grid UI. Search results update via semantic relevance ranking rather than keyword matching. The design separates upload, processing status, and retrieval views — each with clean loading states and error boundaries. Stable frontend API contracts are enforced by contract tests.

| Layer | Technologies |
|---|---|
| Frontend | React, TypeScript |
| Services | Python microservices, FastAPI-style |
| AI Models | CLIP, BLIP (Hugging Face) |
| Database | PostgreSQL + pgvector |
| DevOps | Docker Compose, GPU-aware workers |

[![Repo](https://img.shields.io/badge/Repo-SemaMedia-009688?style=flat-square&logo=github)](https://github.com/MinhKhoa2209/SemaMedia)

---

### 📉 ChurnPrediction — End-to-End ML Platform
> **Full ML lifecycle: upload → preprocess → train → explain → predict → report**

**Architecture & Logic:**
Celery + Redis workers handle long-running ML jobs asynchronously. Users upload datasets via a Next.js frontend, which triggers background preprocessing (validation, cleaning, feature engineering), model training with scikit-learn + Optuna hyperparameter tuning, and SHAP explainability generation. Model artefacts are stored in MinIO. Alembic manages DB schema migrations. RBAC separates Admin and Analyst workflows.

**UI/UX Approach:** Next.js frontend with a dashboard-style layout. Training progress is surfaced with real-time job status polling. Prediction results display SHAP waterfall charts alongside probability scores. The Analyst view hides admin controls; the Admin view exposes dataset management, model registry, and user controls.

| Layer | Technologies |
|---|---|
| Frontend | Next.js, TypeScript |
| Backend | FastAPI, Celery, Redis |
| ML | scikit-learn, Optuna, SHAP |
| Storage | PostgreSQL, MinIO |
| DevOps | Docker Compose, Alembic |

[![Repo](https://img.shields.io/badge/Repo-ChurnPrediction-F7931E?style=flat-square&logo=github)](https://github.com/MinhKhoa2209/ChurnPrediction)

---

### 🛍️ TrendyFit — Modern E-commerce Storefront
> **Full-featured commerce application with CMS, auth, and Stripe checkout**

**Architecture & Logic:**
Next.js server components handle product/catalog rendering with Sanity CMS as the content source. Clerk manages authentication and user sessions. Stripe Checkout handles payment flows with webhook-driven order status updates. Zustand manages client-side cart state. Typed product and order models are shared across server actions and API routes.

**UI/UX Approach:** Modern storefront with responsive grid layouts, animated product cards, and a seamless multi-step checkout flow. Sanity's live preview enables real-time content editing. The UI adapts for authenticated vs guest users — showing personalised order history and wishlists for signed-in users. Deployed and live on Vercel.

| Layer | Technologies |
|---|---|
| Frontend | Next.js, React, TypeScript, Tailwind CSS |
| CMS | Sanity |
| Auth | Clerk |
| Payments | Stripe |
| State | Zustand |
| Deploy | Vercel |

[![Repo](https://img.shields.io/badge/Repo-TrendyFit-635BFF?style=flat-square&logo=github)](https://github.com/MinhKhoa2209/TrendyFit_Ecommerce)
[![Live](https://img.shields.io/badge/Live-trendyfit.vercel.app-14B8A6?style=flat-square&logo=vercel)](https://trendyfit.vercel.app)

---

### 🏦 Banking Desktop App — Java Application
> **Desktop banking application built with Java**

[![Repo](https://img.shields.io/badge/Repo-Banking--DesktopApp-ED8B00?style=flat-square&logo=github)](https://github.com/MinhKhoa2209/Banking_DesktopApp)

---

## 🏆 AWS Hackathon — g8-costctl
> **Cloud cost control CLI tool built during the AWS Hackathon**

A Python CLI tool (`g8-costctl`) for AWS cost visibility and control. Built as a team project during an AWS-themed hackathon, demonstrating real-time cost querying, resource tagging analysis, and budget alert integration.

[![Repo](https://img.shields.io/badge/Repo-g8--costctl-FF9900?style=flat-square&logo=github)](https://github.com/MinhKhoa2209/g8-costctl)
[![Hackathon](https://img.shields.io/badge/Repo-Hackathon__AWS-FF6B35?style=flat-square&logo=github)](https://github.com/MinhKhoa2209/Hackathon_AWS)

---

## ⚙️ Engineering Principles

```
┌─────────────────────────────────────────────────────────────────┐
│  Infrastructure as Code   │  Terraform modules, repeatable      │
│                           │  deploy workflows, remote state      │
├─────────────────────────────────────────────────────────────────┤
│  Cloud Architecture       │  VPC design, private networking,    │
│                           │  CloudFront, WAF, ECS, Lambda        │
├─────────────────────────────────────────────────────────────────┤
│  Database-First Design    │  PL/pgSQL, triggers, RLS, pgvector, │
│                           │  row locking, materialized views     │
├─────────────────────────────────────────────────────────────────┤
│  Containers & Compose     │  Dockerfiles, health checks,        │
│                           │  production-like local stacks        │
├─────────────────────────────────────────────────────────────────┤
│  AI/ML Pipelines          │  Embeddings, semantic search, SHAP, │
│                           │  background jobs, Bedrock RAG        │
├─────────────────────────────────────────────────────────────────┤
│  Delivery Practices       │  Migration scripts, env separation, │
│                           │  logs, validation evidence docs      │
└─────────────────────────────────────────────────────────────────┘
```

---

## 📊 GitHub Stats

<p align="center">
  <img height="180" src="https://github-readme-stats.vercel.app/api?username=MinhKhoa2209&show_icons=true&theme=github_dark&hide_border=true&rank_icon=github&include_all_commits=true&count_private=true" alt="GitHub stats" />
  &nbsp;
  <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MinhKhoa2209&layout=compact&theme=github_dark&hide_border=true&langs_count=8" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=MinhKhoa2209&theme=github-dark-blue&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" alt="GitHub streak" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=MinhKhoa2209&theme=algolia&no-frame=true&no-bg=true&column=7" alt="GitHub trophies" />
</p>

---

## 🎯 Current Learning Goals

- [ ] **Kubernetes** — deployments, services, ingress, ConfigMaps/Secrets, HPA, and cluster observability
- [ ] **CI/CD** — GitHub Actions pipelines for testing, container builds, and automated cloud deployments
- [ ] **Terraform** — advanced module design, remote state backends, and drift detection workflows
- [ ] **System Design** — distributed tracing, event-driven patterns, and reliability engineering
- [ ] **AWS Solutions Architect** — preparing toward Associate certification

---

## 📬 Let's Connect

I'm actively looking for **software engineering internships** and **cloud/full-stack roles**. If you're building something interesting with cloud infrastructure, AI/ML systems, or complex backend platforms — I'd love to talk.

<p align="left">
  <a href="minhkhoa2209@gmail.com">
    <img src="https://img.shields.io/badge/Email-your--email%40example.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/khoa-minh-927139298/">
    <img src="https://img.shields.io/badge/LinkedIn-your--linkedin--username-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;
  <a href="https://github.com/MinhKhoa2209">
    <img src="https://img.shields.io/badge/GitHub-MinhKhoa2209-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:14B8A6,50:2563EB,100:0D1117&section=footer" alt="footer wave" />
</p>
