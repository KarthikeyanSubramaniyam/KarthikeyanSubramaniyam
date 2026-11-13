<h1 align="center">👋 Karthikeyan Subramaniam</h1>

<p align="center">
  <strong>🧱 Data Engineer · 🤖 AI / ML Systems Engineer · 🛡️ Cybersecurity & Cloud Security Architect</strong>
</p>

<p align="center">
  <em>Designing resilient lakehouse pipelines, building transformer models from the ground up, and architecting zero-trust defensive security systems.</em>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/karthikeyansubramaniam04/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin" alt="LinkedIn"></a>
  <a href="https://karthikeyan-subramaniam.netlify.app/"><img src="https://img.shields.io/badge/Portfolio-Live_Site-blue?style=flat&logo=googlechrome" alt="Portfolio"></a>
  <img src="https://img.shields.io/badge/Status-Open_to_Collaborations-success?style=flat" alt="Status">
</p>

---

> 🔒 **Technical Showcase & Architecture Index**:
> The repositories linked below provide complete architectural specifications, data workflows, design diagrams, and project overviews. Full production source code, proprietary algorithms, and sensitive enterprise credentials are held securely in private repositories.

---

## 🧱 1. Data Engineering & Lakehouse Architectures

Scalable batch/streaming pipelines, medallion lakehouse designs, CDC ingestion engines, and automated data quality controls.

### 🌟 Enterprise Data Pipelines & Infrastructure
* **[B2B Data Pipeline](https://github.com/KarthikeyanSubramaniyam/b2b-data-pipeline)** — Production-grade multi-stage B2B pipeline: automated ingestion, multi-vendor waterfall enrichment, automated data quality scoring, and Snowflake warehouse staging with automated HTML executive reporting.
* **[Company Waterfall Enrichment API](https://github.com/KarthikeyanSubramaniyam/company-enrichment-api)** — High-concurrency Go service executing waterfall enrichment across primary, secondary, and web scraping fallbacks with connection-pooled PostgreSQL caching.
* **[ICP Launch-List Ingestion & Enrichment](https://github.com/KarthikeyanSubramaniyam/ICP-L1-Enrichment)** — ICP list normalization, automated deduplication, company enrichment, and LinkedIn discovery automation.
* **[OGraph Enrichment Engine](https://github.com/KarthikeyanSubramaniyam/OGraph-Enrichment)** — Graph-based contact and organization enrichment engine with verification and consistency validation.
* **[Enterprise Data Taxonomy & SSOT](https://github.com/KarthikeyanSubramaniyam/Taxonomy)** — Standardized taxonomy mapping, attribute normalization, and Single-Source-of-Truth schema enforcement.
* **[DataHub Governance & Quality](https://github.com/KarthikeyanSubramaniyam/DataHub)** — Automated schema validation, data anomaly detection, and automated cleaning routines for structured enterprise datasets.

### ⚡ 10 Specialized Pipeline Suites *(Architecture Highlights)*
1. **Real-Time Clickstream & Funnel Engine** — Micro-batch stream processing, session windowing, and parquet sink lakehouse partitioning.
2. **Medallion Architecture Engine** — Tiered Lakehouse pipeline enforcing Raw (Bronze) $\to$ Cleansed (Silver) $\to$ Aggregated (Gold) marts.
3. **Change Data Capture (CDC) Stream Replay** — Database transaction log parsing, out-of-order event replay, and checkpoint state recovery.
4. **dbt-Style SQL Transform Engine** — Custom DAG dependency resolver, SQL transform pipeline, and automated schema test assertions.
5. **Slowly Changing Dimensions (SCD Type 2)** — High-efficiency temporal dimension tracking, validity interval management, and point-in-time joins.
6. **Streaming Financial Fraud Feature Store** — Sliding-window aggregation engine calculating rolling velocity metrics for real-time inference.
7. **Automated Data Quality Circuit Breaker** — Statistical threshold profiling, anomaly detection, and automated ingestion pipeline abort mechanisms.
8. **IoT Partitioned Data Lake & Compactor** — Multi-tier temporal partitioning engine with automated small-file compaction.
9. **Vectorized Multi-Threaded Batch Mart** — High-throughput parallelized batch ETL transforming transactional data into analytics-ready marts.
10. **Vector ETL Knowledge Lakehouse** — Text chunking, tokenization, embedding generation, and vector lake ingestion for RAG systems.

---

## 🤖 2. Artificial Intelligence & Machine Learning Systems

Developing autonomous agentic workflows, hybrid graph retrieval, zero-trust MCP gateways, and transformer architectures from mathematical first principles.

* **[Agentic Deep Research & Synthesis Engine](https://github.com/KarthikeyanSubramaniyam/agentic-deep-research-public)** — Autonomous multi-agent deep research engine featuring recursive question decomposition, cross-source fact verification, citation credibility scoring, and executive dossier synthesis.
* **[Enterprise Hybrid GraphRAG Engine](https://github.com/KarthikeyanSubramaniyam/graph-rag-engine-public)** — Next-generation hybrid retrieval engine combining multi-hop Knowledge Graph traversal (entity-relation-entity networks) with dense vector embeddings and Reciprocal Rank Fusion (RRF) to eliminate multi-hop hallucinations.
* **[MCP Security & Tool Gateway for AI Agents](https://github.com/KarthikeyanSubramaniyam/mcp-agent-gateway-public)** — Zero-Trust Model Context Protocol (MCP) gateway featuring Role-Based Tool Access Control (RBAC), parameter boundary verification, sliding-window rate limiting, and SHA-256 cryptographic audit logs for autonomous AI agents.
* **[scratchformer](https://github.com/KarthikeyanSubramaniyam/scratchformer-public)** — Complete modern Large Language Model architecture engineered purely from mathematical foundations: Rotary Position Embeddings (RoPE), Grouped-Query Attention (GQA), KV-caching, LoRA parameter-efficient fine-tuning, and speculative decoding.
* **[AI Daily Task Copilot](https://github.com/KarthikeyanSubramaniyam/ai-daily-task-copilot-public)** — Intelligent offline task management copilot featuring NLP action decomposition, priority matrix scoring, duplicate detection, and automated scheduling heuristics.
* **[NumPy Neural Net](https://github.com/KarthikeyanSubramaniyam/numpy-neural-net-public)** — Deep neural network built from absolute scratch in pure NumPy (hand-coded forward pass, backpropagation, and mini-batch gradient descent achieving ~97% accuracy on MNIST).
* **[Intent Classification Chatbot](https://github.com/KarthikeyanSubramaniyam/intent-chatbot-public)** — Lightweight ML-powered intent classifier combining TF-IDF vectorization and Naive Bayes with confidence fallbacks for FAQ automation.
* **[AI Resume Matcher](https://github.com/KarthikeyanSubramaniyam/ai-resume-matcher-public)** — Offline NLP engine computing cosine similarity between resumes and job requirements with granular skill-gap reporting.
* **[AI Evidence Workbench](https://github.com/KarthikeyanSubramaniyam/ai-evidence-workbench)** — Offline retrieval system utilizing BM25 ranking and source provenance verification for grounded AI responses.

---

## 🛡️ 3. Cybersecurity, SOC & Threat Detection

Designing threat detection pipelines, self-hosted SIEM infrastructures, deception honeypots, and tabletop response simulators.

* **[Home SOC & SIEM Lab](https://github.com/KarthikeyanSubramaniyam/home-soc-siem-lab-public)** — Enterprise SIEM deployment on Wazuh and Docker Compose: multi-node log aggregation, custom detection rules mapped to MITRE ATT&CK, and automated response playbooks.
* **[Wazuh HomeLab](https://github.com/KarthikeyanSubramaniyam/wazuh-homelab-public)** — Hardened Wazuh SIEM configuration, custom rule tuning, alert pipelines, and agent health telemetry.
* **[Deception Honeypot](https://github.com/KarthikeyanSubramaniyam/deception-honeypot-public)** — Multi-protocol deception environment emulating production servers (`prod-db-01`), capturing attacker credentials, command logs, and lateral traversal indicators.
* **[IR-Sim (Incident Response Simulator)](https://github.com/KarthikeyanSubramaniyam/ir-sim-public)** — Interactive tabletop incident-response simulator scoring defensive decision trees against MITRE ATT&CK scenarios with MTTD/MTTR analytics.
* **[Malware Analysis Sandbox](https://github.com/KarthikeyanSubramaniyam/malsandbox)** — Self-hosted static and behavioral triage sandbox computing composite 0–100 threat scores and mapped attack indicators.
* **[Zero Trust Policy Engine](https://github.com/KarthikeyanSubramaniyam/zero-trust-policy-engine)** — Attribute-Based Access Control (ABAC) engine evaluating real-time contextual signals for access decisions.
* **[Endpoint & Network Telemetry Suite](https://github.com/KarthikeyanSubramaniyam/authorized-endpoint-telemetry)** — Go-based lightweight host telemetry, network packet inspection, credential vaults, and real-time File Integrity Monitoring (FIM).

---

## ☁️ 4. Cloud Security, IAM & Defensive Auditing

Suite of defensive audit tools for automated posture verification, access governance, and infrastructure-as-code security.

| Cloud Governance & IAM | Defensive Posture & Auditing |
| :--- | :--- |
| **[IAM Escalation Analyzer](https://github.com/KarthikeyanSubramaniyam/iam-escalation-analyzer)** — Privilege escalation detection | **[Zero Trust Review](https://github.com/KarthikeyanSubramaniyam/zero-trust-architecture-review)** — Segmentation & identity review |
| **[CloudTrail Threat Detector](https://github.com/KarthikeyanSubramaniyam/cloudtrail-threat-detector)** — Anomaly & threat pattern analysis | **[Desktop Hardening](https://github.com/KarthikeyanSubramaniyam/desktop-hardening-checker)** — Endpoint security posture auditing |
| **[Cloud Security Drift](https://github.com/KarthikeyanSubramaniyam/cloud-security-drift)** — Multi-region baseline drift detector | **[Firewall Rules Auditor](https://github.com/KarthikeyanSubramaniyam/firewall-rules-auditor)** — Risky port and rule analyzer |
| **[Terraform Security Scanner](https://github.com/KarthikeyanSubramaniyam/terraform-cloud-security)** — IaC plan static analysis | **[Website Security](https://github.com/KarthikeyanSubramaniyam/website-security-auditor)** — HTTP header and posture evaluation |
| **[Cloud Encryption Review](https://github.com/KarthikeyanSubramaniyam/cloud-encryption-review)** — At-rest and in-transit audit | **[Crypto Agility](https://github.com/KarthikeyanSubramaniyam/cryptographic-agility-planner)** — Post-quantum migration planner |
| **[Cloud Network Analyzer](https://github.com/KarthikeyanSubramaniyam/cloud-network-path-analyzer)** — Public ingress exposure check | **[AI Model Risk](https://github.com/KarthikeyanSubramaniyam/ai-model-risk-scanner)** — AI model release compliance scanner |

---

## 🌐 5. Production Web Systems & Cloudflare Workers

* **[Finnet Diwali Store](https://github.com/KarthikeyanSubramaniyam/finnet-diwali-store-public)** — Security-hardened e-commerce storefront, automated ordering pipeline, and Cloudflare Worker telemetry ticker.
* **[Finnet Web & Payment Systems](https://github.com/KarthikeyanSubramaniyam/Finnet-new)** — Serverless Cloudflare Worker architecture integrating signed payment sessions, rate-limited APIs, and responsive design.

---

## 🧰 Technical Skills

* **Data Engineering**: Python · SQL · Snowflake · Apache Spark · Delta / Parquet · Medallion Architecture · CDC · dbt Patterns · Vector ETL
* **AI & Machine Learning**: Deep Learning (NumPy / PyTorch) · Transformer Math (RoPE, GQA, LoRA) · NLP · TF-IDF · BM25 Search
* **Cybersecurity & SIEM**: Wazuh · Docker · MITRE ATT&CK · Zero Trust · Incident Response Playbooks · Deception Systems · Endpoint Telemetry
* **Cloud & Infrastructure**: AWS (IAM, CloudTrail, S3, VPC) · Cloudflare Workers / D1 · Terraform · Linux / Bash · Git / GitHub Actions

---

<p align="center">
  <em>Open to high-impact opportunities in Data Engineering, AI Systems, and Cybersecurity Architecture.</em><br>
  <strong>Reach out via <a href="https://www.linkedin.com/in/karthikeyansubramaniam04/">LinkedIn</a> or explore my <a href="https://karthikeyansubramaniyam.github.io">Interactive Portfolio</a>.</strong>
</p>
