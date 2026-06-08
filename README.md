<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0F172A,45:2563EB,100:14B8A6&text=Minh%20Khoa&fontColor=FFFFFF&fontSize=56&fontAlignY=38&desc=Software%20Engineering%20Student%20%7C%20Cloud%20Infrastructure%20%7C%20Full-Stack%20Systems&descSize=18&descAlignY=58" alt="Minh Khoa - Software Engineering Student" />
</p>

<p align="center">
  <a href="https://github.com/MinhKhoa2209">
    <img src="https://img.shields.io/badge/GitHub-MinhKhoa2209-181717?style=flat-square&logo=github" alt="GitHub" />
  </a>
  <a href="mailto:your-email@example.com">
    <img src="https://img.shields.io/badge/Email-Contact-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://www.linkedin.com/in/your-linkedin-username">
    <img src="https://img.shields.io/badge/LinkedIn-Profile-0A66C2?style=flat-square&logo=linkedin" alt="LinkedIn" />
  </a>
</p>

## About Me

I am a Software Engineering student building toward cloud-focused full-stack engineering. My strongest work combines application development with infrastructure: Terraform-managed AWS environments, containerized services, PostgreSQL-heavy systems, and AI/ML applications that move beyond demo screens into real workflows.

Current focus: **AWS**, **Terraform**, **Kubernetes**, **Docker**, **Cloud Infrastructure**, and **Full Stack Development**.

I care about systems that are understandable, deployable, and testable: clear architecture, explicit infrastructure, database correctness, and practical developer workflows.

## Tech Expertise

### Primary

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

### Secondary

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Sanity](https://img.shields.io/badge/Sanity-F03E2F?style=flat-square&logo=sanity&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)

### Currently Learning

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![System Design](https://img.shields.io/badge/System%20Design-111827?style=flat-square)

## Featured Projects

### AWS Accelerator Project

**Value proposition:** Production-style AWS infrastructure built with Terraform, covering networking, application delivery, data migration, observability, and backup evidence.

- **Architecture:** Multi-subnet VPC, public/firewall/private app/private data tiers, CloudFront + S3 frontend, WAF, HTTP API, Lambda authorizer, private ALB, ECS service, ECR, DocumentDB, optional DMS from MongoDB Atlas, Lambda + Bedrock RAG endpoint, EFS, AWS Backup, VPC endpoints, CloudWatch logs, and Secrets Manager.
- **Key technologies:** Terraform, AWS VPC, ECS, ECR, CloudFront, WAF, API Gateway, Lambda, DocumentDB, DMS, Bedrock, EFS, AWS Backup, CloudWatch.
- **Challenges solved:** Infrastructure as Code composition, private networking, secure edge delivery, service-to-service access, secret handling, migration planning, evidence-driven deployment validation.
- **Repository:** [MinhKhoa2209/AWS](https://github.com/MinhKhoa2209/AWS)

### Smart Logistics

**Value proposition:** Warehouse and logistics management system designed around advanced PostgreSQL features rather than only application-layer logic.

- **Architecture:** React + Vite frontend, Express/TypeScript backend, SQL-first repository/service layers, PostgreSQL 17 with pgvector, local Ollama embeddings, Docker Compose environment.
- **Key technologies:** TypeScript, React, Express.js, PostgreSQL, pgvector, PL/pgSQL, Docker, Ollama.
- **Challenges solved:** Inventory consistency, row locking for stock transfers, trigger-based automation, audit logging with JSONB diffs, materialized reporting views, RLS-backed access rules, semantic product search.
- **Repository:** [MinhKhoa2209/smart-logistics](https://github.com/MinhKhoa2209/smart-logistics)

### Semedia - Semantic Media Search

**Value proposition:** AI media search platform for indexing images/videos and retrieving results through hybrid semantic search.

- **Architecture:** Dockerized microservice stack with gateway API, media worker, search API, shared service layer, PostgreSQL, React/TypeScript frontend, and smoke/service test coverage.
- **Key technologies:** Python, FastAPI-style services, React, TypeScript, PostgreSQL, CLIP, BLIP captioning, Hugging Face models, Docker Compose, GPU-aware workers.
- **Challenges solved:** Media processing pipeline design, scene extraction, caption generation, embedding search, model warmup, GPU/CPU runtime configuration, stable frontend API contracts, smoke-testable service orchestration.
- **Repository:** [MinhKhoa2209/SemaMedia](https://github.com/MinhKhoa2209/SemaMedia)

### Customer Churn Prediction Platform

**Value proposition:** End-to-end ML platform for dataset upload, preprocessing, model training, evaluation, prediction, and reporting.

- **Architecture:** Next.js frontend, FastAPI backend, PostgreSQL, Redis, Celery workers, MinIO object storage, Alembic migrations, Docker Compose stack.
- **Key technologies:** Python, FastAPI, scikit-learn, Optuna, SHAP, Celery, Redis, PostgreSQL, MinIO, Next.js, TypeScript.
- **Challenges solved:** Background ML jobs, dataset validation, automated preprocessing, hyperparameter optimization, model artifact storage, threshold tuning, explainable predictions, RBAC for Admin/Analyst workflows.
- **Repository:** [MinhKhoa2209/ChurnPrediction](https://github.com/MinhKhoa2209/ChurnPrediction)

### TrendyFit E-commerce

**Value proposition:** Modern commerce application with product discovery, checkout flow, content management, and customer account workflows.

- **Architecture:** Next.js storefront, Sanity CMS, Clerk authentication, Stripe checkout, server routes/actions, typed product/order models, Vercel deployment.
- **Key technologies:** Next.js, React, TypeScript, Sanity, Clerk, Stripe, Zustand, Tailwind CSS.
- **Challenges solved:** Product/catalog modeling, authenticated user flows, checkout integration, order status updates, CMS-backed content, frontend state management.
- **Repository:** [MinhKhoa2209/TrendyFit_Ecommerce](https://github.com/MinhKhoa2209/TrendyFit_Ecommerce) | [Live](https://trendyfit.vercel.app)

## Engineering Highlights

```text
Infrastructure as Code   Terraform stacks, AWS resource modeling, repeatable deploy workflows
Cloud Architecture       VPC design, private networking, CloudFront, WAF, ECS, Lambda, DocumentDB
Containers               Dockerfiles, Docker Compose, service health checks, local production-like stacks
Data Systems             PostgreSQL, pgvector, PL/pgSQL, row locking, triggers, RLS, materialized views
AI/ML Systems            ML pipelines, embeddings, semantic search, SHAP explainability, background jobs
Delivery Practices       Environment separation, migration scripts, logs, validation steps, evidence docs
```

## GitHub Metrics

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=MinhKhoa2209&show_icons=true&theme=github_dark&hide_border=true&rank_icon=github" alt="GitHub stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MinhKhoa2209&layout=compact&theme=github_dark&hide_border=true&langs_count=8" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=MinhKhoa2209&theme=github-dark-blue&hide_border=true" alt="GitHub streak" />
</p>

## Current Engineering Goals

- Deepen Kubernetes fundamentals: deployments, services, ingress, config/secrets, and observability.
- Build stronger CI/CD workflows for testing, container builds, and cloud deployments.
- Improve Terraform module design, remote state practices, and infrastructure review discipline.
- Continue building full-stack systems where the database, backend, frontend, and infrastructure all fit together coherently.

## Contact

I am open to software engineering internships, cloud/full-stack projects, and technical collaboration.

<p align="left">
  <a href="minhkhoaoik2209@gmail.com">
    <img src="https://img.shields.io/badge/Email-your--email%40example.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://www.linkedin.com/in/khoa-minh-927139298">
    <img src="https://img.shields.io/badge/LinkedIn-your--linkedin--username-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/MinhKhoa2209">
    <img src="https://img.shields.io/badge/GitHub-MinhKhoa2209-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>
