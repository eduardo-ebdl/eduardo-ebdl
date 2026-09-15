<div align="center">

<img src="./banner.svg" alt="Eduardo Lima | Data & AI Engineer" width="100%" />

</div>

<p align="right">
  <a href="./README.pt-BR.md">
    <img src="https://img.shields.io/badge/Português-009C3B?style=flat-square" alt="Português" />
  </a>
</p>

<div align="center">

<h3>Data & AI Engineer building reliable data pipelines and the LLM agents that run on them.</h3>

<p>
  Python · SQL · Databricks · dbt · LangGraph · Hybrid RAG · MCP
</p>

</div>

## About

I work across data engineering and GenAI: Medallion pipelines with dbt, SQL and Python on Databricks and Snowflake, and LLM agents, retrieval systems and MCP integrations built on top of that data.

My projects focus on the engineering layer that AI demos often skip: deterministic guardrails, automated evaluation, prompt versioning, tracing, CI quality gates, and cost and latency observability.

## Featured Projects

### [Multi-Agent Reimbursement Agent](https://github.com/eduardo-ebdl/multiagent-reimbursement-agent) | Multi-Agent System with MCP

Health insurance reimbursement agent built during Triggo.AI's AI Engineering bootcamp. A LangGraph supervisor routes three sub-agents (triage, document and rules) with per-session state, over a hybrid RAG pipeline for a regulation amended by circulars: article-level chunking with effective-date metadata, BM25 + embeddings, Reciprocal Rank Fusion and LLM reranking. Includes MCP integration for eligibility and case protocols, OCR document classification, deterministic reimbursement calculation with cited articles, and LGPD guardrails.

**Core stack:** LangGraph · LlamaIndex · MCP · FastAPI · Pydantic · Tesseract OCR · Gemini · Docker · pytest

### [Sales Report AI](https://github.com/eduardo-ebdl/sales-report-ai) | LLMOps and Reliability

LLM pipeline that generates executive reports from Databricks Gold data. It combines deterministic numeric guardrails, Claude-based evaluation, a versioned prompt registry with golden tests in CI, and PostgreSQL observability for tokens, cost, latency, quality, and prompt drift.

**Core stack:** n8n · Claude Haiku · Claude Sonnet · Databricks · PostgreSQL · FastAPI · GitHub Actions · Docker

### [SRAG Agent](https://github.com/eduardo-ebdl/srag-agent) | Epidemiological Monitoring Agent

ReAct agent for epidemiological surveillance running on Azure Databricks. It uses SQL tools, chart generation, and grounded web search over a governed Medallion architecture with MLflow tracing, Unity Catalog, Databricks Asset Bundles, data quality gates, secrets management, and LGPD-oriented PII removal.

**Core stack:** LangGraph · Llama 3 · Azure Databricks · dbt · Spark SQL · MLflow · Unity Catalog · Tavily

### [Lupus](https://github.com/eduardo-ebdl/lupus) | AI Code Intelligence Agent

LangGraph agent for exploring unfamiliar codebases through 17 specialized tools. It combines FAISS, BM25, Reciprocal Rank Fusion, and CrossEncoder reranking in a hybrid retrieval pipeline, exposes a streaming FastAPI layer, and supports multiple LLM providers.

**Core stack:** LangGraph · LangChain · LangSmith · FAISS · BM25 · CrossEncoder · FastAPI · SQLite

## Experience

- **Analytics Engineering Trainee** | Indicium AI · Dec 2025 to Jul 2026
  Data transformations with SQL and dbt on Databricks and Snowflake (Medallion architecture), GitLab CI/CD, and Power Automate + Databricks automation with approval tracking and observability.
- **Analytics Engineering Intern** | Indicium AI · Aug 2024 to Nov 2025
  Redesigned the team's data and alerting automation architecture (58 flows consolidated into 6) and implemented monitoring for critical data processes.
- **FlyRank AI Internship** | Backend AI Engineering track · 2026 · in progress
  Online educational program with mentor-reviewed projects: APIs for AI applications, structured outputs, RAG with citations and LLM evaluation.

## Education

- **B.Sc. in AI Engineering** | Instituto Infnet · 2026 to 2029 · in progress
- **Technologist Degree in Big Data and Artificial Intelligence** | PUC Goiás · 2024 to 2026 · graduated *summa cum laude*

## Stack

### Languages

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" />
</p>

### Agents and LLMs

<p>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/LangSmith-1C3C3C?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/MCP-111827?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white" />
  <img src="https://img.shields.io/badge/Anthropic-191919?style=flat-square&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" />
</p>

### Retrieval and Embeddings

<p>
  <img src="https://img.shields.io/badge/LlamaIndex-6B21A8?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white" />
  <img src="https://img.shields.io/badge/BM25-6B7280?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/CrossEncoder-6B7280?style=flat-square&logoColor=white" />
</p>

### Evaluation and LLMOps

<p>
  <img src="https://img.shields.io/badge/LLM_Evaluation-7C3AED?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/Guardrails-DC2626?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/Prompt_Registry-2563EB?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white" />
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" />
</p>

### Data Engineering

<p>
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white" />
  <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white" />
  <img src="https://img.shields.io/badge/Spark_SQL-E25A1C?style=flat-square&logo=apachespark&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
</p>

### Automation, APIs and Infra

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white" />
  <img src="https://img.shields.io/badge/Power_Automate-0066FF?style=flat-square&logo=powerautomate&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" />
</p>

## Contact

<p>
  <a href="https://canislupus.dev"><img src="https://img.shields.io/badge/Portfolio-111827?style=flat-square&logo=googlechrome&logoColor=white" /></a>
  <a href="https://linkedin.com/in/eduardoebdl"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:eduardobdel@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" /></a>
</p>
