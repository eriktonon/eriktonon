<div align="center">

# Erik Tonon

**Head of Platform Engineering & Generative AI @ IBM Consulting · Ex-Associate Director at BTG Pactual · Founder @ EdgeSearch Labs**

*Mission-Critical Systems Architecture · Site Reliability Engineering (Build to Manage) · Internal Developer Platforms (IDP) · Regulated Banking AI*

<p>
  <a href="https://eriktonon.com">
    <img src="https://img.shields.io/badge/Executive_Portfolio-eriktonon.com-%230F62FE?style=flat-square&logo=googlechrome&logoColor=white" alt="Executive Portfolio" />
  </a>
  <a href="https://www.linkedin.com/in/erik-tonon/">
    <img src="https://img.shields.io/badge/LinkedIn-in%2Ferik--tonon-%230A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://score.eriktonon.com">
    <img src="https://img.shields.io/badge/DORA_%26_BTM_Assessment-score.eriktonon.com-%2324A148?style=flat-square" alt="Platform Readiness Score" />
  </a>
  <a href="https://tokenomics.eriktonon.com">
    <img src="https://img.shields.io/badge/AI_Tokenomics_%26_FinOps-tokenomics.eriktonon.com-%23161616?style=flat-square" alt="AI Tokenomics Calculator" />
  </a>
  <a href="https://docs.edgesearch.io/">
    <img src="https://img.shields.io/badge/EdgeSearch_Docs-docs.edgesearch.io-%230043CE?style=flat-square" alt="EdgeSearch Documentation" />
  </a>
</p>

</div>

---

## Executive Summary

Engineering leader and principal architect with over a decade of hands-on experience designing, scaling, and operating **mission-critical financial systems**, **Internal Developer Platforms (IDPs)**, **high-volume observability**, and **regulated Enterprise AI**.

Currently serving as **Manager of Platform Engineering & Generative AI at IBM Consulting (Banking Industry)**, leading the **Dojo@Biz** engineering enablement program across dozens of banking squads (19 DORA practices across 4 maturity tiers) and the **ACT Framework (Ask, Check, Tell)** for Central Bank (Bacen) compliant AI governance. Previously served as **Principal SRE & Build to Manage (BTM) Advisor on Projeto HCOM** (Tier-1 Banking & PIX instant payments), **IT Specialist & Associate Director at BTG Pactual** (architecting the bank's centralized enterprise log and telemetry platform), and **Platform SRE at Tiendanube** (creator of the **Nubeportal** Backstage IDP). Founder of **[EdgeSearch Labs](https://github.com/edgesearchlabs)**.

### Core Engineering Principles
- **Shift-Left Operability (Build to Manage)**: Systems must be born operable. Telemetry, deterministic L1–L5 synthetic health probes, First Failure Data Capture (FFDC), and blast-radius containment are design criteria, not post-incident patches.
- **Platform as an Internal Product**: Internal Developer Platforms exist to reduce squad cognitive load and make security, compliance, and FinOps the path of least resistance via Golden Paths.
- **Governance as a Velocity Multiplier**: Regulatory compliance (Bacen, Basel III, LGPD) does not slow down engineering organizations when policy-as-code, SBOM attestation, and error budgets are enforced deterministically in the pipeline.

---

## Career Trajectory & Leadership Roles

| Period | Role | Organization | Architectural & Executive Scope |
| :--- | :--- | :--- | :--- |
| **2026 — Present** | **Manager of Platform Engineering & Generative AI** | **IBM Consulting** *(Banking Industry)* | Executive leadership of Platform Engineering and GenAI for Tier-1 financial institutions. Leads **Dojo@Biz** (19 DORA practices), Docs-as-Code (**BEX TechDocs**), Kubernetes Golden Paths, and the **ACT Framework** for regulated AI. |
| **2025 — 2026** | **Principal SRE & Advisor Build to Manage** | **Tier-1 National Bank & IBM Consulting** *(Projeto HCOM)* | Architected critical-system topology, blast-radius isolation, L1–L5 synthetic health-check APIs, **FFDC (First Failure Data Capture)**, Golden Signals, SLO Error Budgets, and **Dojo@Scale for PIX** (instant payments under high transactional concurrency). |
| **2024 — 2025** | **Site Reliability Engineer · Platform Engineering** | **Tiendanube** *(Latin America)* | Conceived and implemented **Nubeportal** (Internal Developer Platform built on **Backstage**) and self-service Infrastructure as Code using **Crossplane**, **Terraform**, and **Kubernetes** across dozens of product squads. |
| **2022 — 2024** | **IT Specialist · Associate Director** | **BTG Pactual** *(São Paulo)* | Architected the centralized enterprise **Log Aggregation & Mission-Critical Telemetry Platform** (Elasticsearch/OpenSearch, Kubernetes, long-term compliant retention, and FinOps) for Latin America's largest investment bank. |
| **2021 — Present** | **Founder & Principal Architect** | **[EdgeSearch Labs](https://github.com/edgesearchlabs)** | Boutique consultancy and software ecosystem focused on large-scale search (**Elasticsearch / OpenSearch**), distributed observability (**OpenTelemetry**), **EdgePortal IDP**, and Cloud FinOps (up to 40% infrastructure cost reduction for clients including TIVIT, SEBRAE, SASI, and GDM Seeds). |
| **2020 — 2021** | **Observability & SRE Engineer** | **Tier-1 Financial Conglomerate** | Continuous monitoring on **Red Hat OpenShift**, Prometheus/Grafana RED & Golden Signals dashboards, and proactive SLA anomaly detection prior to customer impact. |
| **2018 — 2020** | **Software & DevOps Engineer** | **Holding Gazin** | Architected **API Pagador** (multi-acquirer payment gateway with deterministic transactional split) and **NullRisk** (B2B wholesale credit scoring & CDC platform), plus enterprise Jenkins/GitLab CI/CD pipelines. |
| **2021** | **Creator & Technical Mentor** | **[Projeto Acelera DevOps](https://github.com/Acelera-DevOps)** | Community mentorship initiative training engineers in Linux, Git, Shell, Python, AWS ECS Fargate, CI/CD, and Terraform Infrastructure as Code. |

---

## Architectural Frameworks & Live Engineering Tools

| Initiative / Platform | Domain | Technical Overview | Access |
| :--- | :--- | :--- | :--- |
| **Build to Manage (BTM) v2.0** | SRE & Shift-Left Operability | Reference implementation of the **11 IBM Build to Manage practices**: L1–L5 Synthetic HealthCheck APIs (`/health/deep?synthetic=true`), W3C `traceparent` propagation, **FFDC snapshots**, CloudEvents catalog, Runbooks as Code, and interactive **IBM Carbon v11** SRE Control Plane. | [`eriktonon/build-to-manage`](https://github.com/eriktonon/build-to-manage) |
| **Platform Readiness Score** | DORA & BTM Maturity Diagnostic | Interactive executive diagnostic evaluating engineering organizations across **19 Platform Engineering practices** and 4 DORA maturity tiers (*Beginner, Foundational, High-Performing, Elite & Adaptive*). | [`score.eriktonon.com`](https://score.eriktonon.com) |
| **AI Tokenomics & FinOps Calculator** | GenAI Architecture & FinOps | Financial and architectural modeling tool for enterprise LLM deployments: context-window cost projection, multi-provider routing economics, caching ROI, and infrastructure sizing. | [`tokenomics.eriktonon.com`](https://tokenomics.eriktonon.com) |
| **EdgeSearch & EdgePortal Docs** | Distributed Data & IDP | Reference architecture documentation for **Elasticsearch/OpenSearch** node segregation (Master, Ingest, Data, Coordinator), Index Lifecycle Management (ILM), OpenTelemetry collectors, and **EdgePortal IDP**. | [`docs.edgesearch.io`](https://docs.edgesearch.io/) |
| **Executive Portfolio & Essays** | Systems Architecture | Deep-dive engineering essays on **Martin Kleppmann's distributed consensus in instant payments (PIX)**, **ACT Governance for Banking AI**, **Platform as an Internal Product**, and **Active SRE Resilience**. | [`eriktonon.com`](https://eriktonon.com) |

---

## Featured Open Source & Reference Repositories

- **[`eriktonon/build-to-manage`](https://github.com/eriktonon/build-to-manage)** — **Build to Manage (BTM) Framework v2.0**: IBM Cloud Architecture & SRE reference with L1–L5 synthetic health checks, W3C TraceContext distributed tracing, FFDC engine, and automated contract test suite.
- **[`eriktonon/OmniRoute`](https://github.com/eriktonon/OmniRoute)** — **Enterprise Multi-Provider AI Gateway**: Unified OpenAI-compatible routing endpoint across 290+ providers and 500+ models with quota-aware auto-fallback, token compression, and MCP/A2A integration.
- **[`eriktonon/opentelemetry-demo`](https://github.com/eriktonon/opentelemetry-demo)** — **Distributed Observability Reference Architecture**: Polyglot microservice topology instrumented with OpenTelemetry, Data Prepper, Prometheus, and OpenSearch for end-to-end trace and RED metric correlation.
- **[`eriktonon/openclaude`](https://github.com/eriktonon/openclaude)** — **Autonomous Coding-Agent CLI**: Terminal-first multi-provider agent harness supporting OpenAI, Gemini, DeepSeek, Ollama, and GitHub Models with Model Context Protocol (MCP) tool execution.
- **[`edgesearchlabs/airllm`](https://github.com/edgesearchlabs/airllm)** — **Layer-Wise LLM Inference Optimization**: Execution of 70B+ parameter large language models on constrained GPU memory via shard-by-shard layer streaming and VRAM optimization.
- **[`Acelera-DevOps/terraform-aws-ecs`](https://github.com/Acelera-DevOps/terraform-aws-ecs)** — **Cloud-Native IaC Reference**: Modular Terraform architecture for AWS ECS Fargate, multi-AZ VPC isolation, security groups, and Principle of Least Privilege (PoLP).

---

## Technology Radar & Engineering Stack

| Domain | Technologies & Standards |
| :--- | :--- |
| **Platform Engineering & Cloud-Native** | `Kubernetes` · `Red Hat OpenShift` · `Backstage (IDP)` · `Crossplane` · `Terraform (HCL)` · `Ansible` · `Argo Rollouts` · `ArgoCD` · `OPA / Kyverno (Policy as Code)` · `Cosign / SBOM` · `Docker` |
| **SRE, Observability & Data Scale** | `Build to Manage (BTM)` · `OpenTelemetry (W3C TraceContext)` · `Elasticsearch` · `OpenSearch` · `Prometheus` · `Grafana` · `Qdrant Vector DB` · `PostgreSQL` · `Redis` · `Apache Kafka` · `IBM MQ` |
| **Languages & Backend Systems** | `Rust` · `Python` · `TypeScript / Node.js` · `Go` · `Java (Quarkus 3 / Spring Boot 3)` · `PHP (Mezzio)` · `Shell / Linux (RHEL)` |
| **Enterprise AI & Cloud Providers** | `IBM watsonx` · `Model Context Protocol (MCP)` · `Hybrid Vector RAG` · `ACT AI Governance` · `AWS` · `Microsoft Azure` · `Google Cloud (GCP)` · `IBM Cloud` · `Cloud FinOps` |

---

## Academic Background & Verified Credentials

- **Academic Degrees**:
  - **MBA in Finance, Investments, and Banking**
  - **Postgraduate Specialization in Cloud Computing Projects** *(PUC)*
  - **Bachelor of Science in Information Systems**
- **Verified Executive & Technical Certifications**:
  - [**IBM — License to Lead: First-Line Manager**](https://www.credly.com/badges/1476e693-b0da-4ca9-8232-1bc58510fea2) *(Credly Verified)*
  - [**Google — AI Professional Certificate**](https://www.credly.com/badges/05808bd0-1dcd-4b43-a27f-288193e82f39) *(Credly Verified)*
  - **Cloud, Infrastructure & Security**: AWS · Azure · IBM Cloud · Cisco CCNA R&S · Linux LPI · CompTIA Security+ · Docker · SRE & DevOps

---

<div align="center">
  <sub><b>Erik Tonon</b> · São Paulo / Paraná, Brazil · <a href="https://eriktonon.com">eriktonon.com</a> · <a href="https://www.linkedin.com/in/erik-tonon/">LinkedIn</a> · <a href="mailto:eriktonon@gmail.com">eriktonon@gmail.com</a></sub>
</div>
