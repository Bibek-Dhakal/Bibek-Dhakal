# Hi, I'm Bibek Dhakal 👋

### Associate AI / Machine Learning Engineer | PyTorch • LLMs • FastAPI • ML Systems

*Kathmandu, Nepal • [imbibek8366@gmail.com](mailto:imbibek8366@gmail.com)*

I am an **entry-level AI / Machine Learning Engineer** with a software engineering background and a focus on building
machine-learning systems from first principles through deployment.

My work spans **PyTorch, Transformer architectures, tokenization, ML inference, data processing, LLM applications,
FastAPI backends, and Docker-based deployment**. I enjoy understanding how ML systems work underneath high-level
abstractions and turning those implementations into usable software.

**Status & Commitment:** I am fully available for immediate full-time employment with zero academic commitments
remaining. Having completed my degree and short-term project contracts, I am seeking a long-term role as an
Associate/Junior ML Engineer where I can grow with a core engineering team and contribute to production systems over the
coming years.

**🎯 Recent:** Completed AI/ML Internship at FlyRank AI (Published Capstone on Data Leakage & Search Intelligence) <br>
**🎓 Education:** BCA final semester examinations completed in August 2026 <br>
**💼 Status:** **Available immediately for full-time employment** <br>
**🔎 Seeking:** **Associate / Junior ML Engineer, AI Engineer, or Entry-Level ML Engineer roles**

---

## 🚀 What I Work On

* 🧠 **Machine Learning & Deep Learning** — PyTorch, TensorFlow, Scikit-Learn, Transformer architectures
* 🤖 **LLMs & NLP** — tokenization, BPE, RAG, AI agents, Hugging Face
* ⚡ **ML Inference** — ONNX Runtime, INT8 quantization, CPU inference, memory optimization
* 📊 **Data Processing & Pipelines** — Apache Spark, Delta Lake, DuckDB, Airflow, dbt, PostgreSQL
* 🔧 **Backend, MLOps & Deployment** — FastAPI, Docker, Kubernetes, CI/CD, Automated Testing, REST APIs, PyPI Packaging
* 🌐 **Applications** — React, Next.js, Streamlit, Metabase, Power BI

---

## 🛠 Tech Stack

| Category                  | Technologies                                                                               |
|:--------------------------|:-------------------------------------------------------------------------------------------|
| **Languages**             | Python, TypeScript, SQL, C#, Dart                                                          |
| **Machine Learning & AI** | PyTorch, TensorFlow, Scikit-Learn, SciPy, Statsmodels, NumPy, Pandas, OpenCV, Hugging Face |
| **LLM / Inference**       | Transformers, ONNX Runtime, FAISS, FlashAttention, BPE Tokenization                        |
| **Data & BI**             | Apache Spark, Delta Lake, DuckDB, PostgreSQL, BigQuery, Airflow, dbt, Metabase, Power BI   |
| **Backend & MLOps**       | FastAPI, Docker, Kubernetes, GitHub Actions, Pytest, Pydantic, MLflow, Prefect, Prometheus |
| **Frontend & Mobile**     | React, Next.js, TailwindCSS, Streamlit, Flutter                                            |

---

## 📌 Featured Projects

### 🌊 [LakeForge](https://github.com/Bibek-Dhakal/LakeForge)

**Medallion lakehouse ETL/ELT with idempotent incremental processing, quality quarantine, and governed serving.**

* **Idempotent Data Lakehouse:** Architected a 100% Docker-first open-source pipeline utilizing **Apache Spark** and
  **Delta Lake** to process data deterministically through Landing, Bronze, Silver, and Gold layers.
* **Strict Quality Quarantine:** Engineered a declarative YAML-based quality engine that enforces schemas and seamlessly
  routes invalid records into dedicated quarantine tables without silent data drops.
* **Dual-Profile Orchestration:** Configured **Apache Airflow** topologies supporting both a lightweight SQLite executor
  for testing and a production-grade PostgreSQL + LocalExecutor architecture for parameterized backfills.
* **Governed Analytics & Observability:** Served Gold-layer data through a **FastAPI** + **DuckDB** API secured via
  Role-Based Access Control (RBAC), fully monitored via **Prometheus** metrics and **Grafana** dashboards.

### 📈 [InsightLedger](https://github.com/Bibek-Dhakal/InsightLedger)

**End-to-end decision-support analytics stack: governed KPIs, reconciled data, and rigorous A/B testing.**

* **Modern Data Stack:** Deployed a fully containerized pipeline using **PostgreSQL**, **dbt-postgres**, and
  **Metabase** to ingest mock data, transform it into a dimensional model, and serve self-serve parameterized
  dashboards.
* **Governed KPI Transformations:** Implemented strict data-quality tests (uniqueness, non-null, referential) using
  **dbt**, ensuring data totals precisely reconcile and bad data never contaminates downstream reporting.
* **Rigorous Experiment Analysis:** Evaluated A/B testing data programmatically in Python using `scipy` and
  `statsmodels`, enforcing Chi-Square tests to halt analysis on Sample Ratio Mismatch (SRM) anomalies.
* **Statistical Significance:** Computed genuine business impacts (e.g., 28.7% relative conversion lift) backed by
  2-proportion Z-tests, precise p-values, and 95% Confidence Intervals.

### 🏗️ [DataMart-Flex](https://github.com/Bibek-Dhakal/DataMart-Flex)

**Enterprise Star-Schema Data Mart and Self-Serve BI Analytics Hub powered by DuckDB.**

* **Automated Data Pipeline:** Engineered an automated ETL pipeline using Python and DuckDB to transform 100,000+ raw
  transactional records into a strict Kimball-methodology dimensional model.
* **Synthetic Data Generation:** Generated realistic synthetic business datasets (customers, products, channels, and
  orders) using the Python `Faker` library to simulate an enterprise data ecosystem.
* **Advanced BI Integration:** Built a comprehensive Power BI showcase dashboard utilizing explicit DAX and Time
  Intelligence measures (YTD, MoM Growth, Rolling Averages) for executive reporting.

### 🧪 [StatTest-Pro](https://github.com/Bibek-Dhakal/StatTest-Pro)

**End-to-End A/B Testing Analysis Framework with automated SRM safety checks and executive reporting.**

* **Statistical Rigor:** Engineered a Python SDK that calculates required sample sizes pre-test using `statsmodels` to
  ensure well-powered experiments.
* **Automated Safety Invariants:** Enforced automated Sample Ratio Mismatch (SRM) anomaly detection via Chi-Square
  Goodness-of-Fit, halting evaluations if $p < 0.01$.
* **Enterprise CI/CD & Packaging:** Packaged and published natively to [PyPI](https://pypi.org/project/stattest-pro/),
  maintained with rigorous standards including `Pytest` coverage and semantic versioning via GitHub Actions.

### ⚙️ [CohortLTV-Engine](https://github.com/Bibek-Dhakal/CohortLTVEngine)

**Automated Customer Cohort Retention and Lifetime Value (LTV) Analytics Engine.**

* **High-Performance Execution:** In-process analytics using **DuckDB** to process 1,000,000+ transactional rows locally
  in **~174ms**, massively exceeding the sub-5 second SLA constraint.
* **Advanced SQL Transformations:** Engineered complex data pipelines utilizing Window Functions, CTEs, and aggregated
  joins to accurately compute month-over-month retention and rolling LTV metrics.

### 📉 [ExecPulse-BI](https://github.com/Bibek-Dhakal/exec-pulse-BI)

**Interactive Sales & Operations BI Dashboard built on automated Star-Schema Data Modeling.**

* **Automated ETL Pipeline:** Pushed heavy row-level transformations into programmatic Python/Pandas ETL steps,
  converting 50,000+ raw transactions into a strict dimensional Star Schema.
* **Optimized Storage & BI Consumption:** Exported normalized dimensional tables into a local **SQLite** database via
  **SQLAlchemy** and generated flat CSVs for highly-performant, cross-platform BI ingestion.

### 📊 [Applied Search Intelligence: CTR Opportunity Scoring](https://bibek-dhakal.github.io/applied-search-intelligence/)

**Decision-support ML system for SEO prioritization (FlyRank Capstone).**

* Handled out-of-core data processing by querying and verifying a **~79 million row** production warehouse directly from
  Hugging Face using **DuckDB**.
* Identified and documented a critical data leakage trap: a naive data split yielded an inflated 94% precision due to
  client overlap, which I corrected to an honest 64% using a strict **client-grouped holdout split**.
* Published the full methodology, leakage audit, and results as a
  deployed [Research Paper](https://bibek-dhakal.github.io/applied-search-intelligence/).

### 📊 [InsightStory-EDA](https://github.com/Bibek-Dhakal/InsightStory-EDA)

**SQL-driven exploratory analysis of e-commerce customer behavior, automated into an executive presentation.**

* **Automated Data Storytelling:** Developed a Python CLI tool that runs the analytical pipeline end-to-end—from
  building a database to programmatically generating a 5-slide executive deck (`.pptx` & `.pdf`).
* **SQL & DuckDB Analytics:** Engineered 9 complex SQL queries and views using **DuckDB** to analyze RFM segments,
  cohort retention, profit concentration, and monthly churn trends.

### 🧹 [DataCleanse-Lite](https://github.com/Bibek-Dhakal/data-cleanse-lite)

**Automated Multi-Source E-Commerce ETL Pipeline with Pandas Data Cleaning, Validation Checks, and SQL Storage.**

* **High Throughput ETL:** Extracted, cleaned, validated, and loaded **100,000 messy records** in **~2.24 seconds**
  using in-memory `pandas` manipulation, outperforming the strict 30-second SLA by over 13x.
* **Strict Validation & Quarantine:** Leveraged **Pydantic** to assert strict data contracts (null constraints, typing),
  gracefully trapping and quarantining ~21% of corrupted records.

### 🌊 [FlowTrace: DAG-Orchestrated ML Pipeline](https://github.com/Bibek-Dhakal/flowtrace)

**DAG-orchestrated, parameterized, lineage-tracked ML pipeline with strict data quality gating.**

* **DAG Orchestration:** Built an explicit Directed Acyclic Graph (DAG) using **Prefect** to isolate, monitor, and scale
  pipeline stages.
* **Strict Quality Gating:** Enforced declarative data boundaries with **Pandera**, natively halting execution before
  expensive training jobs if data is corrupt.

### 🧪 [TabTrace: Reproducible ML Pipeline](https://github.com/Bibek-Dhakal/tabtrace)

**Reproducible tabular ML pipeline enforcing justified feature engineering and cross-validated evaluation.**

* Enforced declarative feature justifications via a custom Python decorator registry, automatically halting the pipeline
  if rationale is missing.
* Evaluated a Logistic Regression baseline against a grid-searched Random Forest using 5-fold stratified
  cross-validation.

### 🚀 [ModelGate: ML Inference API & Python SDK](https://github.com/Bibek-Dhakal/modelgate)

**Production-ready, containerized machine learning inference API and native Python SDK with zero boilerplate.**

* **Dynamic Artifact Loading:** Instantly serves `.joblib` or `.pkl` models by fetching them directly via HTTP URLs on
  startup using Environment Variables.
* **Native Python SDK:** Published on [PyPI](https://pypi.org/project/modelgate-py/) to integrate dynamic loading and
  strict validation directly into existing codebases.

### ☸️ [ServeScale: Kubernetes ML Serving System](https://github.com/Bibek-Dhakal/servescale)

**Horizontally scalable, latency-optimized machine learning model serving system built on Kubernetes.**

* **Inference Optimization:** Leveraged **ONNX Runtime** and **8-bit Dynamic Quantization** to significantly minimize
  the model's container memory footprint and CPU latency.
* **Zero-Downtime Rollouts:** Integrated **Locust** load testing to explicitly verify that exactly **0 requests are
  dropped** during live RollingUpdates under concurrent HTTP traffic.

### 📉 [Customer Churn Risk Intelligence](https://github.com/bibek-dhakal/customer-churn-risk-intelligence)

**Enterprise-grade MLOps pipeline and real-time API for customer churn prediction and risk segmentation.**

* Engineered a production-ready machine learning pipeline featuring experiment tracking and model registry via
  **MLflow**, alongside a real-time inference microservice built with **FastAPI**.
* Secured model persistence using **Skops** instead of legacy pickle files to eliminate arbitrary code execution
  vulnerabilities in production environments.

### 🛡️ [Aegis Omnisearch Agent](https://github.com/bibek-dhakal/aegis-api)

**Lightweight RAG agent designed for resource-constrained deployments.**

* Implemented a custom **ReAct-style Reason + Act loop** using Google's Gemini API for tool selection and grounded
  responses.
* Built local retrieval using **FAISS** and used **INT8 ONNX Runtime** for lightweight CPU inference.

### 📦 [LexiByte](https://github.com/bibek-dhakal/lexibyte)

**Byte-Pair Encoding tokenizer implemented from scratch and published as a Python package on PyPI.**

* Implemented GPT-style regex pre-tokenization using Unicode-aware patterns for words, numbers, and punctuation.
* Published the package to PyPI (`pip install lexibyte`).

### ⚡ [Forge-LM](https://github.com/bibek-dhakal/forge-lm) & [NanoTransformer](https://github.com/bibek-dhakal/nanotransformer)

**A project exploring Transformer implementation, training, optimization, and lightweight inference.**

* Scaled the architecture to approximately **28M parameters** and trained on TinyStories using gradient accumulation to
  work within ~6 GB VRAM.
* Exported the model to **ONNX** and applied **INT8 dynamic quantization** for lightweight inference via FastAPI.

### 🛡️ [Multimodal Phishing Detection Platform](https://github.com/bibek-dhakal/multimodal-phishing-detection-platform)

**Phishing detection system combining structured URL features with linguistic signals.**

* Combined structured URL features from **ISCX** with linguistic features from **PhiUSIIL** using soft-voting fusion.

### 🌐 [ZeroProp Engine & Live WebSocket Dashboard](https://github.com/Bibek-Dhakal/zero-prop-api/)

**Neural-network engine implemented without a deep-learning framework, with real-time training visualization.**

* Implemented dense layers, ReLU activation, and Softmax Cross-Entropy using **NumPy matrix operations**.
* Added **FastAPI WebSockets** to stream training metrics to a live **React + HTML5 Canvas** dashboard.

### 📉 [OverfitLab](https://github.com/Bibek-Dhakal/overfitlab)

**A deep learning experiment demonstrating the diagnosis and correction of overfitting.**

* Diagnosed train/validation loss divergence and restored generalization by applying **Dropout (p=0.5)** and **L2 Weight
  Decay** in **PyTorch**.

### 🚀 [LunarLander-v2 Agent](https://huggingface.co/imbibek8366/ppo-LunarLander-v2)

**Reinforcement-learning agent trained with PPO.**

* Trained an autonomous agent to safely navigate a lunar module to its landing pad using Proximal Policy Optimization
  (PPO).

---

## 💼 Experience

### Machine Learning & AI Experience

**AI / ML Engineering Intern** — *FlyRank AI* | **Jul 2026 – Sep 2026**

* Engineered a **CTR Opportunity Scoring** model acting as a decision-support system to prioritize SEO metadata reviews.
* Used **DuckDB** to query and aggregate large-scale Parquet datasets (**~79M rows**) directly from Hugging Face,
  avoiding RAM bottlenecks.
* Conducted rigorous model evaluation, successfully identifying and mitigating client-overlap data leakage via strict
  grouped validation splits.
* Authored and deployed a comprehensive [Research Paper](https://bibek-dhakal.github.io/applied-search-intelligence/)
  detailing the validation methodology and error analysis.
* Completed various **Anthropic Academy certifications** for AI fluency and Claude API proficiency.

### Training & Apprenticeships

**Data Science & ML Apprentice** — *Skill Shikshya* | **Apr 2026 – June 2026**

* Completed a hands-on learning track covering machine-learning mathematics, vector computation, classical ML, and
  deep-learning concepts.
* Built and served ML applications using **FastAPI** and containerized them using **Docker**.
* Completed **Kaggle certifications for Pandas, Feature Engineering, Intro to ML, and Intermediate ML**.

---

### Software Engineering Contracts & Internships Along with Bachelor's Degree

**Full-Stack Engineer Intern** — *Walkers Hive IT Professionals* | **Oct 2025 – Dec 2025** *(Mandatory Academic
Internship)*

* Independently designed and implemented the architecture for the **AcademiaOS MVP** using **FastAPI, Celery, and
  Next.js**.

**Software Engineer** — *Nextwave Technology* | **Apr 2025 – Jul 2025** *(Contract)*

* Worked on new features, bug fixes, UI revamp, and the Google Play Store launch of the **Academia** mobile application.

**Software Engineer** — *Walkers Hive IT Professionals* | **Nov 2024 – Apr 2025** *(Contract)*

* Built an e-commerce administration panel using **React, MUI, and Redux-Saga**.

**Android Development Intern** — *CodSoft* | **Dec 2023 – Jan 2024** *(Internship)*

* Developed Flutter applications with **Firebase Authentication** and **BLoC state management**.

---

## 🎓 Education

### Bachelor of Computer Application (BCA)

**Nihareeka College of Management and Information Technology**
*Tribhuvan University, Nepal • Completed Final Semester Coursework and Examination on August 2026*
**Status:** **Fully available with no remaining academic obligations.**

---

## 📜 Certifications

* **FlyRank AI — Machine Learning Internship
  Certificate** [Link](https://internship.flyrank.ai/verify/FR-D11-20CBF-CC2BF?first_name=Bibek)
* **Skill Shikshya — Data Science & ML Diploma** [Link](https://skillshikshya.com/verify-certificates/DSAMLDC260023)

## Anthropic Academy Certifications:

* **Anthropic Academy — Claude Code in Action** [Link](https://verify.skilljar.com/c/ho48cm8wcsa9)
* **Anthropic Academy — Building with the Claude API** [Link](https://verify.skilljar.com/c/hg695uod5bb8)
* **Anthropic Academy — MCP Advanced Topics** [Link](https://verify.skilljar.com/c/bf7vbtdiv8ti)
* **Anthropic Academy — Claude on Amazon Bedrock** [Link](https://verify.skilljar.com/c/gesgzvi2zhk5)
* **Anthropic Academy — Claude on Google Vertex AI** [Link](https://verify.skilljar.com/c/umhhhrba6gkf)

### Kaggle Certificates: [Link](https://www.kaggle.com/bibekdhakal8366)

* **Kaggle — Pandas, Feature Engineering, Intro to Machine Learning, Intermediate Machine Learning**

---

## 📫 Let's Connect

* **Email:** [imbibek8366@gmail.com](mailto:imbibek8366@gmail.com)
* **LinkedIn:** [linkedin.com/in/bibek-dhakal-771ba5334](https://www.linkedin.com/in/bibek-dhakal-771ba5334/)
* **Portfolio:** [Portfolio](https://bibek-dhakal-fr.vercel.app/)

---
