<div align="center">

<img src="./banner.svg" alt="Eduardo Lima | Data & AI Engineer" width="100%" />

</div>

<p align="right">
  <a href="./README.md">
    <img src="https://img.shields.io/badge/English-1F6FEB?style=flat-square" alt="English" />
  </a>
</p>

<div align="center">

<h3>Engenheiro de Dados & IA construindo pipelines de dados confiáveis e os agentes de LLM que rodam sobre eles.</h3>

<p>
  Python · SQL · Databricks · dbt · LangGraph · RAG Híbrido · MCP
</p>

</div>

## Sobre

Atuo entre engenharia de dados e IA generativa: pipelines em arquitetura Medallion com dbt, SQL e Python sobre Databricks e Snowflake, e agentes de LLM, sistemas de recuperação e integrações via MCP construídos sobre esses dados.

Meus projetos focam na camada de engenharia que as demos de IA costumam pular: guardrails determinísticos, avaliação automatizada, versionamento de prompts, rastreamento, gates de qualidade em CI e observabilidade de custo e latência.

## Projetos em destaque

### [Multi-Agent Reimbursement Agent](https://github.com/eduardo-ebdl/multiagent-reimbursement-agent) | Sistema Multiagente com MCP

Agente de reembolso de plano de saúde desenvolvido durante o bootcamp de AI Engineering da Triggo.AI. Um supervisor em LangGraph roteia três subagentes (triagem, documento e normas) com estado por sessão, sobre um pipeline de RAG híbrido para um regulamento alterado por circulares: chunking por artigo com metadados de vigência, BM25 + embeddings, Reciprocal Rank Fusion e reranking por LLM. Inclui integração via MCP para elegibilidade e protocolos, classificação de documentos com OCR, cálculo determinístico do reembolso com citação dos artigos e guardrails de LGPD.

**Stack principal:** LangGraph · LlamaIndex · MCP · FastAPI · Pydantic · Tesseract OCR · Gemini · Docker · pytest

### [Sales Report AI](https://github.com/eduardo-ebdl/sales-report-ai) | LLMOps e Confiabilidade

Pipeline com LLM que gera relatórios executivos a partir de dados da camada Gold no Databricks. Combina guardrails numéricos determinísticos, avaliação com Claude, registro versionado de prompts com golden tests em CI e observabilidade em PostgreSQL de tokens, custo, latência, qualidade e drift de prompt.

**Stack principal:** n8n · Claude Haiku · Claude Sonnet · Databricks · PostgreSQL · FastAPI · GitHub Actions · Docker

### [SRAG Agent](https://github.com/eduardo-ebdl/srag-agent) | Agente de Vigilância Epidemiológica

Agente ReAct para vigilância epidemiológica rodando no Azure Databricks. Usa ferramentas SQL, geração de gráficos e busca web fundamentada sobre uma arquitetura Medallion governada, com rastreamento no MLflow, Unity Catalog, Databricks Asset Bundles, gates de qualidade de dados, gestão de segredos e remoção de dados pessoais orientada à LGPD.

**Stack principal:** LangGraph · Llama 3 · Azure Databricks · dbt · Spark SQL · MLflow · Unity Catalog · Tavily

### [Lupus](https://github.com/eduardo-ebdl/lupus) | Agente de Inteligência de Código

Agente em LangGraph para explorar bases de código desconhecidas com 17 ferramentas especializadas. Combina FAISS, BM25, Reciprocal Rank Fusion e reranking com CrossEncoder num pipeline de recuperação híbrida, expõe uma camada FastAPI com streaming e suporta múltiplos provedores de LLM.

**Stack principal:** LangGraph · LangChain · LangSmith · FAISS · BM25 · CrossEncoder · FastAPI · SQLite

## Experiência

- **Trainee em Analytics Engineering** | Indicium AI · dez/2025 a jul/2026
  Transformações de dados com SQL e dbt sobre Databricks e Snowflake (arquitetura Medallion), GitLab CI/CD e automação com Power Automate + Databricks, com rastreamento de aprovações e observabilidade.
- **Estagiário em Analytics Engineering** | Indicium AI · ago/2024 a nov/2025
  Nova arquitetura de automação de dados e alertas do time (58 fluxos consolidados em 6) e monitoramento de processos de dados críticos.
- **FlyRank AI Internship** | Trilha Backend AI Engineering · 2026 · em andamento
  Programa educacional online com projetos revisados por mentores: APIs para aplicações de IA, saída estruturada, RAG com citações e avaliação de LLMs.

## Formação

- **Bacharelado em Engenharia de Inteligência Artificial** | Instituto Infnet · 2026 a 2029 · em andamento
- **Tecnólogo em Big Data e Inteligência Artificial** | PUC Goiás · 2024 a 2026 · formado *summa cum laude*

## Stack

### Linguagens

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" />
</p>

### Agentes e LLMs

<p>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/LangSmith-1C3C3C?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/MCP-111827?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white" />
  <img src="https://img.shields.io/badge/Anthropic-191919?style=flat-square&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" />
</p>

### Recuperação e Embeddings

<p>
  <img src="https://img.shields.io/badge/LlamaIndex-6B21A8?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white" />
  <img src="https://img.shields.io/badge/BM25-6B7280?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/CrossEncoder-6B7280?style=flat-square&logoColor=white" />
</p>

### Avaliação e LLMOps

<p>
  <img src="https://img.shields.io/badge/LLM_Evaluation-7C3AED?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/Guardrails-DC2626?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/Prompt_Registry-2563EB?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white" />
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" />
</p>

### Engenharia de Dados

<p>
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white" />
  <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white" />
  <img src="https://img.shields.io/badge/Spark_SQL-E25A1C?style=flat-square&logo=apachespark&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
</p>

### Automação, APIs e Infra

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white" />
  <img src="https://img.shields.io/badge/Power_Automate-0066FF?style=flat-square&logo=powerautomate&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" />
</p>

## Contato

<p>
  <a href="https://canislupus.dev"><img src="https://img.shields.io/badge/Portfólio-111827?style=flat-square&logo=googlechrome&logoColor=white" /></a>
  <a href="https://linkedin.com/in/eduardoebdl"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:eduardobdel@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" /></a>
</p>
