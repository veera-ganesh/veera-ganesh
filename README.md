# Hi there, I'm Veera Ganesh Ponugoti 👋

### Data Scientist | Generative AI & Agentic Systems Orchestration
📍 United States *(Open to Relocation)*

I am a Data Science professional specializing in building stateful LLM orchestration frameworks, training predictive machine learning models, and optimizing scalable cloud data architectures. I bridge the gap between advanced statistical modeling and intelligent generative AI systems.

---

### 🛠️ Core Stack & Expertise

*   **Data & Analytics Engineering:** SQL (Advanced), Python, dbt, Airflow, Data Pipelines, Tableau
*   **Cloud Data Platforms:** Snowflake, Databricks, AWS (Bedrock, S3, EC2, IAM, Lambda)
*   **AI & Orchestration:** LangGraph, LangChain, LLM-as-a-Judge Evals, OpenTelemetry (Arize Phoenix)
*   **Machine Learning:** XGBoost, Scikit-Learn, Text Embeddings, Predictive Modeling
*   **Professional Credentials:** Certified Apache Airflow [Fundamentals](https://www.credly.com/badges/d651c37e-593e-42d4-9762-7fbe9821648f/linked_in_profile) / [Associate](https://www.credly.com/badges/40d127fe-a921-4a35-9168-8a9b657088fe/linked_in?t=tb1qa2) 🎖️
*   **Education:** M.S. in Data Science — Florida State University 🎓

---

### 🚀 Key Projects (Featured)

#### 🤖 Hybrid ML + GenAI Customer Exception Triage Platform
*Built a dual-layer automation engine designed to parse and resolve enterprise-scale volume safely.*
*   **The Gatekeeper:** Engineered a local XGBoost classifier using open-source text embeddings (`all-MiniLM-L6-v2` 384-dimensional dense vectors) to triage 90% of predictable corporate data for free.
*   **The GenAI Engine:** Routed low-confidence anomalies into a stateful **LangGraph pipeline** powered by **AWS Bedrock (Claude 3.5 Sonnet)** for deep semantic analysis, RAG context gathering, and response drafting.
*   **Enterprise Safety:** Implemented a human-in-the-loop state memory checkpointer to instantly freeze execution via interrupt gates on high-risk corporate anomalies.
*   **Observability:** Integrated production-grade tracing and token-cost monitoring via **OpenTelemetry & Arize Phoenix**.

---

### 🚀 Key Projects (Featured)
#### 🤖 1. Hybrid ML + GenAI Customer Exception Triage Platform
Built a dual-layer automation engine to parse and resolve enterprise-scale complaint volume cost-effectively.
*   **The Gatekeeper:** Engineered a local XGBoost classifier using open-source dense vector embeddings (all-MiniLM-L6-v2, 384-dim) to instantly triage 90% of high-confidence, routine corporate complaints at zero LLM cost.
*   **The GenAI Engine:** Routed low-confidence anomalies into a stateful LangGraph pipeline powered by AWS Bedrock (Claude 3.5 Sonnet) for deep semantic analysis, RAG context retrieval, and automated response drafting.
*   **Human-in-the-Loop Safety:** Implemented state memory checkpointers to freeze execution via interrupt gates on high-risk corporate anomalies, requiring human manager sign-off.
*   **Observability:** Integrated production-grade OpenTelemetry tracing and token-cost monitoring via Arize Phoenix.

#### 🛍️ 2. Stateful Retail Customer Support AI Agent Architecture
Engineered a real-time, multi-turn conversational agent with deterministic tool execution and hard guardrails.
*   **Deterministic Agent Orchestration:** Built a multi-turn support agent using LangGraph and AWS Bedrock (Nova Lite) to execute order tracking, return label generation, and escalation workflows.
*   **Two-Tier Intent Guardrails:** Implemented a zero-shot intent router using lightweight LLM classification and Pydantic structured output to intercept out-of-scope queries ($<300\text{ms}$) while preserving ongoing workflow state using custom flags (awaiting_input).
*   **Tool-Level Idempotency & Persistence:** Designed Python-level edge interceptors and AWS RDS PostgreSQL (PostgresSaver) connection pools to eliminate infinite tool loops (e.g., duplicate support tickets) and persist state across user sessions.
*   **Context Optimization & Tracing:** Mitigated context drift using dynamic sliding-window message trimming (trim_messages) and instrumented end-to-end tracing in Arize Phoenix for turn-by-turn latency and token usage tracking.

---

📫 **Let's Connect:** [LinkedIn](https://www.linkedin.com/in/veera-ganesh-ponugoti/) | [E-mail](mailto:veeraganesh30497@gmail.com)
