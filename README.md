# Hi, I'm Bibek Dhakal 👋

### ML & Data Science | BCA Graduate

*Kathmandu, Nepal • [imbibek8366@gmail.com](mailto:imbibek8366@gmail.com)*

I build machine-learning systems from first principles through deployment, with a software engineering background and a
habit of testing my own results honestly (baselines, leakage-safe validation, error analysis).

My work spans **PyTorch, Transformer architectures, tokenization, ML inference, data pipelines, LLM applications,
FastAPI backends, and Docker-based deployment**. I like understanding how ML systems work underneath high-level
abstractions and turning those implementations into tested, usable software.

**🎓 Education:** BCA, Tribhuvan University. Final-semester examinations completed August 2026 <br>
**🔬 Recent:** ML Internship at FlyRank AI, published capstone on data leakage and search intelligence <br>
**📚 Currently:** Preparing for graduate studies in Computer Science / Data Science, and continuing to build open-source
ML projects

---

## 🚀 What I Work On

* 🧠 **Machine Learning & Deep Learning** — PyTorch, TensorFlow, Scikit-Learn, Transformer architectures
* 🤖 **LLMs & NLP** — tokenization, BPE, RAG, AI agents, Hugging Face
* ⚡ **ML Inference** — ONNX Runtime, INT8 quantization, CPU inference, memory optimization
* 📊 **Data Processing & Pipelines** — Apache Spark, Delta Lake, DuckDB, Airflow, dbt, PostgreSQL
* 🔧 **Backend, MLOps & Deployment** — FastAPI, Docker, Kubernetes, CI/CD, automated testing, PyPI packaging
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

### 📊 [Applied Search Intelligence: CTR Opportunity Scoring](https://bibek-dhakal.github.io/applied-search-intelligence/)

**Decision-support ML system for SEO prioritization (FlyRank capstone research paper).**

* Queried and verified a **~79 million row** production warehouse directly from Hugging Face using **DuckDB**, with no
  RAM bottleneck.
* Found a data leakage trap: a naive split gave an inflated 94% precision due to client overlap. A strict
  **client-grouped holdout split** corrected it to an honest 64%.
* Published the methodology, leakage audit, and results as
  a [research paper](https://bibek-dhakal.github.io/applied-search-intelligence/).

### ⚡ [Forge-LM](https://github.com/bibek-dhakal/forge-lm) & [NanoTransformer](https://github.com/bibek-dhakal/nanotransformer)

**Transformer implementation, training, optimization, and lightweight inference.**

* Scaled the architecture to roughly **28M parameters** and trained on TinyStories with gradient accumulation to fit ~6
  GB VRAM.
* Exported to **ONNX** with **INT8 dynamic quantization** for lightweight inference through FastAPI.

### 🌊 [LakeForge](https://github.com/Bibek-Dhakal/LakeForge)

**Medallion lakehouse ETL/ELT with idempotent incremental processing, quality quarantine, and governed serving.**

* Docker-first **Apache Spark + Delta Lake** pipeline through Landing, Bronze, Silver, and Gold layers.
* Declarative YAML quality engine that routes invalid records to quarantine tables with no silent drops.
* **Airflow** with a lightweight SQLite profile for testing and a PostgreSQL + LocalExecutor profile for backfills.
* Gold data served by **FastAPI + DuckDB** with RBAC, monitored with **Prometheus** and **Grafana**.

### ☸️ [ServeScale: Kubernetes ML Serving System](https://github.com/Bibek-Dhakal/servescale)

**Horizontally scalable, latency-optimized model serving on Kubernetes.**

* **ONNX Runtime** with 8-bit dynamic quantization to cut container memory and CPU latency.
* **Locust** load tests verifying exactly **0 dropped requests** during live RollingUpdates.

### 🚀 [ModelGate: ML Inference API & Python SDK](https://github.com/Bibek-Dhakal/modelgate)

**Containerized inference API and native SDK with zero boilerplate.**

* Serves `.joblib` / `.pkl` models fetched over HTTP at startup via environment variables.
* Published on [PyPI](https://pypi.org/project/modelgate-py/) with strict input validation.

### 📈 [InsightLedger](https://github.com/Bibek-Dhakal/InsightLedger)

**Decision-support analytics stack: governed KPIs, reconciled data, and rigorous A/B testing.**

* Containerized **PostgreSQL + dbt + Metabase** pipeline with uniqueness, non-null, and referential tests.
* A/B analysis with `scipy` and `statsmodels`: Chi-Square SRM gate, 2-proportion Z-tests, p-values, and 95% CIs (28.7%
  relative conversion lift in the demo data).

---

## 🗂 More Projects

| Project                                                                                                 | What it is                   | Highlights                                                                                                                       |
|:--------------------------------------------------------------------------------------------------------|:-----------------------------|:---------------------------------------------------------------------------------------------------------------------------------|
| [StatTest-Pro](https://github.com/Bibek-Dhakal/StatTest-Pro)                                            | A/B testing framework        | Sample-size planning, SRM halt at p < 0.01, published on [PyPI](https://pypi.org/project/stattest-pro/), Pytest + GitHub Actions |
| [LexiByte](https://github.com/bibek-dhakal/lexibyte)                                                    | BPE tokenizer from scratch   | GPT-style Unicode-aware regex pre-tokenization, `pip install lexibyte`                                                           |
| [Aegis Omnisearch Agent](https://github.com/bibek-dhakal/aegis-api)                                     | Lightweight RAG agent        | Custom ReAct loop with Gemini, local FAISS retrieval, INT8 ONNX CPU inference                                                    |
| [ZeroProp Engine](https://github.com/Bibek-Dhakal/zero-prop-api/)                                       | Neural net in pure NumPy     | Dense layers, ReLU, Softmax Cross-Entropy, live React + Canvas training dashboard over WebSockets                                |
| [FlowTrace](https://github.com/Bibek-Dhakal/flowtrace)                                                  | DAG-orchestrated ML pipeline | Prefect DAG, Pandera gates that halt training on bad data                                                                        |
| [TabTrace](https://github.com/Bibek-Dhakal/tabtrace)                                                    | Reproducible tabular ML      | Feature-justification decorator registry, 5-fold stratified CV, LogReg vs. Random Forest                                         |
| [Customer Churn Risk Intelligence](https://github.com/bibek-dhakal/customer-churn-risk-intelligence)    | MLOps churn pipeline         | MLflow tracking and registry, FastAPI inference, Skops instead of pickle                                                         |
| [Multimodal Phishing Detection](https://github.com/bibek-dhakal/multimodal-phishing-detection-platform) | URL + linguistic fusion      | ISCX URL features and PhiUSIIL text features with soft-voting fusion                                                             |
| [OverfitLab](https://github.com/Bibek-Dhakal/overfitlab)                                                | Overfitting diagnosis        | Dropout (p=0.5) and L2 weight decay in PyTorch                                                                                   |
| [LunarLander-v2 Agent](https://huggingface.co/imbibek8366/ppo-LunarLander-v2)                           | RL agent                     | Trained with PPO                                                                                                                 |
| [DataMart-Flex](https://github.com/Bibek-Dhakal/DataMart-Flex)                                          | Star-schema data mart        | 100k+ records, Kimball model, DuckDB, Power BI DAX measures                                                                      |
| [CohortLTV-Engine](https://github.com/Bibek-Dhakal/CohortLTVEngine)                                     | Retention and LTV analytics  | 1M+ rows in ~174 ms with DuckDB window functions and CTEs                                                                        |
| [ExecPulse-BI](https://github.com/Bibek-Dhakal/exec-pulse-BI)                                           | Sales BI dashboard           | 50k+ transactions to a star schema, SQLite via SQLAlchemy                                                                        |
| [InsightStory-EDA](https://github.com/Bibek-Dhakal/InsightStory-EDA)                                    | Automated data storytelling  | 9 DuckDB SQL queries, auto-generated 5-slide `.pptx` / `.pdf` deck                                                               |
| [DataCleanse-Lite](https://github.com/Bibek-Dhakal/data-cleanse-lite)                                   | Multi-source ETL             | 100k messy records in ~2.24 s, Pydantic contracts, ~21% quarantined                                                              |

---

## 💼 Experience

**AI / ML Engineering Intern** — *FlyRank AI* | Jul 2026 – Sep 2026

* Built a **CTR Opportunity Scoring** model to prioritize SEO metadata reviews, querying ~79M Parquet rows with
  **DuckDB**.
* Identified and mitigated client-overlap leakage with grouped validation, and published
  a [research paper](https://bibek-dhakal.github.io/applied-search-intelligence/).

**Data Science & ML Apprentice** — *Skill Shikshya* | Apr 2026 – Jun 2026

* Covered ML mathematics, classical ML, and deep learning; built and containerized FastAPI ML applications with Docker.

**Software Engineering Internships & Contracts (alongside BCA)**

* **Walkers Hive**, Full-Stack Intern (Oct – Dec 2025): designed the **AcademiaOS MVP** with FastAPI, Celery, and
  Next.js.
* **Nextwave Technology**, Software Engineer (Apr – Jul 2025): features, fixes, UI revamp, and Play Store launch of the
  Academia mobile app.
* **Walkers Hive**, Software Engineer (Nov 2024 – Apr 2025): e-commerce admin panel with React, MUI, and Redux-Saga.
* **CodSoft**, Android Development Intern (Dec 2023 – Jan 2024): Flutter apps with Firebase Auth and BLoC.

---

## 🎓 Education

**Bachelor of Computer Application (BCA)** — Nihareeka College of Management and Information Technology, Tribhuvan
University, Nepal *Final-semester examinations completed August 2026*

---

## 📜 Certifications

* [FlyRank AI — Machine Learning Internship Certificate](https://internship.flyrank.ai/verify/FR-D11-20CBF-CC2BF?first_name=Bibek)
* [Skill Shikshya — Data Science & ML Diploma](https://skillshikshya.com/verify-certificates/DSAMLDC260023)
* **Anthropic
  Academy:** [Claude Code in Action](https://verify.skilljar.com/c/ho48cm8wcsa9) · [Building with the Claude API](https://verify.skilljar.com/c/hg695uod5bb8) · [MCP Advanced Topics](https://verify.skilljar.com/c/bf7vbtdiv8ti) · [Claude on Amazon Bedrock](https://verify.skilljar.com/c/gesgzvi2zhk5) · [Claude on Google Vertex AI](https://verify.skilljar.com/c/umhhhrba6gkf)
* [Kaggle](https://www.kaggle.com/bibekdhakal8366): Pandas, Feature Engineering, Intro to ML, Intermediate ML

---

## 📫 Let's Connect

* **Email:** [imbibek8366@gmail.com](mailto:imbibek8366@gmail.com)
* **LinkedIn:** [linkedin.com/in/bibek-dhakal-771ba5334](https://www.linkedin.com/in/bibek-dhakal-771ba5334/)
* **Portfolio:** [bibek-dhakal-fr.vercel.app](https://bibek-dhakal-fr.vercel.app/)
