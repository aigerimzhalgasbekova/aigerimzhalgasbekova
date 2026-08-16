# Hi there, I'm Aigerim Zhalgasbekova! 👋

![Aigerim Zhalgasbekova — Senior Software Engineer, Identity & Access](https://raw.githubusercontent.com/aigerimzhalgasbekova/aigerimzhalgasbekova/main/banner.svg)

## About Me 🚀

I'm a **Senior Software Engineer** with 8+ years of industry experience, specializing in **identity and access management, authentication systems, and backend infrastructure**. I work hands-on with **OAuth 2.0 and OpenID Connect** — auth flows, token lifecycle, multi-tenant isolation — and I like running auth as a production-critical service, with the observability and disaster recovery that implies.

Most recently I led the extraction and zero-downtime migration of a monolithic authentication service into an independent TypeScript/Node.js microservice now serving close to **1 million requests per minute**.

- 🌱 Currently learning: **AI agents**
- 🔭 Working on: **identity subsystem at CUJO AI**
- 🔤 Languages: **TypeScript, Python, Java, and Golang**
- 📫 How to reach me: **aikazzh@gmail.com**
- 🌏 Beyond code: **traveler (33+ countries), investor, and fitness enthusiast**

## My Skills 🧠

**Languages & Runtimes**

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)

**Identity & Security**

![OAuth 2.0](https://img.shields.io/badge/-OAuth%202.0-EB5424?style=flat-square&logo=auth0&logoColor=white)
![OpenID Connect](https://img.shields.io/badge/-OpenID%20Connect-F78C40?style=flat-square&logo=openid&logoColor=white)
![JWT](https://img.shields.io/badge/-JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![KMS](https://img.shields.io/badge/-AWS%20KMS-DD344C?style=flat-square&logo=amazon-aws&logoColor=white)

**Cloud & Infrastructure**

![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![CDK](https://img.shields.io/badge/-AWS%20CDK-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)

**Observability**

![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![CloudWatch](https://img.shields.io/badge/-CloudWatch-FF4F8B?style=flat-square&logo=amazon-cloudwatch&logoColor=white)

## Featured Projects 💻

### Identity & Access 🔐

**[Meridian — IAM Platform](https://github.com/aigerimzhalgasbekova/meridian)** · `Go` `TypeScript` `Terraform`

A from-scratch identity platform built as seven interlocking services: a multi-tenant OAuth 2.0 / OIDC authorization server, a key management and JWT signing service with zero-downtime rotation, a Redis-backed distributed session store with a provable staleness bound, an SSO federation gateway for Google and Entra ID, a tamper-evident hash-chained audit log, a self-service identity portal, and an RBAC control plane that returns a full decision trace with every verdict. Deployed to AWS ECS Fargate with Terraform, and bootable locally with a single command.

**[Secure Authentication API](https://github.com/aigerimzhalgasbekova/auth-api)** · `TypeScript` `AWS`

A serverless authentication API featuring a JWT token issuer and an authorizer for protected endpoints, built with AWS Lambda, API Gateway, DynamoDB, and KMS for secure key management.

### Cloud Infrastructure ☁️

**[AWS CodeBuild Runners Infrastructure](https://github.com/aigerimzhalgasbekova/codebuild-runners-infrastructure)** · `Python` `AWS CDK`

Infrastructure for running GitHub Actions workflows on AWS CodeBuild runners — VPC integration, scoped IAM roles, and secure GitHub token management.

**[Live Infrastructure Management](https://github.com/aigerimzhalgasbekova/live-infrastructure)** · `Terraform` `Terragrunt`

A modular infrastructure-as-code repository for AWS, with remote state in S3, state locking via DynamoDB, and support for multiple environments and regions. Manages S3 buckets, KMS keys, and IAM policies.

### Automation & Tooling 🛠️

**[perplexity-client](https://github.com/aigerimzhalgasbekova/perplexity-client)** · `Python`

Automate your own Perplexity Pro account from Python and the shell. Perplexity Pro ships no API, so this drives a real, manually-authenticated Chrome session over CDP — session bootstrap, cross-process pacing, model selection, multi-turn threads, and Deep Research with detachable long-running tasks.

**[OCR Scanned PDF Converter](https://github.com/aigerimzhalgasbekova/ocr-scanned-pdf-converter)** · `Python`

Turns scanned financial-disclosure PDFs into structured Markdown. Auto-tests all four page rotations, scores them by OCR confidence plus table keywords, then maps each mark to its nearest transaction or amount-code column.

**[Beauty Salon Admin System](https://github.com/aigerimzhalgasbekova/beauty-salon-admin-system)** · `TypeScript`

An administration system for beauty salons with integrated calendar management and multi-user access through Telegram bots, built on a hierarchical three-agent architecture (Admin, Master, Client). Uses Telegraf, the Google Calendar API, and OAuth 2.0.

## AI-Assisted Development 🤖

I use AI-assisted engineering workflows — Claude Code, GitHub Copilot, and Cursor — to accelerate design exploration, implementation, and code review, following security best practices and confidentiality policies: no secrets and no access to real environments are ever granted to AI tools.

## Get in Touch 📬

- [LinkedIn](https://www.linkedin.com/in/azhalgasbekova/)
- 📧 aikazzh@gmail.com
