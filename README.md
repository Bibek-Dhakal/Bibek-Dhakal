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
* 📊 **Data Processing** — DuckDB, BigQuery, PostgreSQL, Pandas, NumPy
* 🔧 **Backend, MLOps & Deployment** — FastAPI, Docker, CI/CD, Automated Testing, REST APIs
* 🌐 **Applications** — React, Next.js, Streamlit, Flutter

---

## 🛠 Tech Stack

| Category                  | Technologies                                                           |
|:--------------------------|:-----------------------------------------------------------------------|
| **Languages**             | Python, TypeScript, SQL, C#, Dart                                      |
| **Machine Learning & AI** | PyTorch, TensorFlow, Scikit-Learn, NumPy, Pandas, OpenCV, Hugging Face |
| **LLM / Inference**       | Transformers, ONNX Runtime, FAISS, FlashAttention, BPE Tokenization    |
| **Data & Databases**      | DuckDB, Google BigQuery, PostgreSQL, Redis                             |
| **Backend & MLOps**       | FastAPI, Docker, GitHub Actions, Pytest, Celery, WebSockets, MLflow    |
| **Frontend & Mobile**     | React, Next.js, TailwindCSS, Flutter                                   |

---

## 📌 Featured Projects

### 📊 [Applied Search Intelligence: CTR Opportunity Scoring](https://bibek-dhakal.github.io/applied-search-intelligence/)

**Decision-support ML system for SEO prioritization (FlyRank Capstone).**

* Handled out-of-core data processing by querying and verifying a **~79 million row** production warehouse directly from
  Hugging Face using **DuckDB**.
* Trained a Random Forest classifier on a curated **30,000-row** anonymized dataset to identify pages underperforming
  their exact peer groups.
* Identified and documented a critical data leakage trap: a naive data split yielded an inflated 94% precision due to
  client overlap, which I corrected to an honest 64% using a strict **client-grouped holdout split**.
* Translated the model probabilities into a transparent, rule-backed "Action Playbook" to avoid black-box automated
  decision-making.
* Published the full methodology, leakage audit, and results as a
  deployed [Research Paper](https://bibek-dhakal.github.io/applied-search-intelligence/).

### 🧪 [TabTrace: Reproducible ML Pipeline](https://github.com/Bibek-Dhakal/tabtrace)

**Reproducible tabular ML pipeline enforcing justified feature engineering and cross-validated evaluation.**

* Rejected "notebook-only" ML: designed the entire pipeline from data ingestion to feature engineering as pure,
  unit-tested Python functions.
* Enforced declarative feature justifications via a custom Python decorator registry, automatically halting the pipeline
  if rationale is missing.
* Implemented deterministic, saved train/val/test splits with strict data leakage checks to guarantee honest model
  evaluation.
* Evaluated a Logistic Regression baseline against a grid-searched Random Forest using 5-fold stratified
  cross-validation.
* Configured automated CI/CD gating using **GitHub Actions**, strictly enforcing **>90% test coverage with Pytest**,
  Ruff formatting, and semantic versioning via Release Please.

### 🚀 [ModelGate: ML Inference API](https://github.com/Bibek-Dhakal/modelgate)

**Production-ready, containerized machine learning inference API with zero boilerplate.**

* **Dynamic Artifact Loading:** Instantly serves `.joblib` or `.pkl` models by fetching them directly via HTTP URLs on
  startup using Environment Variables.
* **Strict Input Validation:** Uses dynamic `schema.json` boundaries to strictly validate incoming payloads, ensuring
  malformed data never hits the execution layer.
* **Error Shielding Architecture:** Overridden FastAPI exception handlers guarantee zero leaked Python stack traces,
  returning only clean `422` and `500` JSON responses.
* **Containerized & CI/CD Enforced:** Fully Docker-native, rigorously tested via **Pytest**, and governed by **GitHub
  Actions** (Ruff Linting, Release Please Versioning).

### 📉 [Customer Churn Risk Intelligence](https://github.com/bibek-dhakal/customer-churn-risk-intelligence)

**Enterprise-grade MLOps pipeline and real-time API for customer churn prediction and risk segmentation.**

* Engineered a production-ready machine learning pipeline featuring experiment tracking and model registry via
  **MLflow**, alongside a real-time inference microservice built with **FastAPI** and containerized using **Docker**.
* Implemented strict declarative data contracts using **Pandera** (training data) and **Pydantic** (API payloads) to
  prevent silent data failures and ensure schema integrity.
* Secured model persistence using **Skops** instead of legacy pickle files to eliminate arbitrary code execution
  vulnerabilities in production environments.
* Evaluated multiple algorithm families using 5-fold Stratified Cross-Validation, ultimately selecting **Logistic
  Regression (0.85 ROC-AUC)** over Random Forest/LightGBM for superior probability ranking sensitivity on imbalanced
  datasets.
* Established a modern CI/CD workflow utilizing **GitHub Actions**, **Pytest**, **Ruff** for linting, and **Google
  Release Please** for automated changelog generation and semantic versioning.

### 🛡️ [Aegis Omnisearch Agent](https://github.com/bibek-dhakal/aegis-api)

**Lightweight RAG agent designed for resource-constrained deployments.**

* Implemented a custom **ReAct-style Reason + Act loop** using Google's Gemini API for tool selection and grounded
  responses.
* Built local retrieval using **FAISS** and used **INT8 ONNX Runtime** for lightweight CPU inference.
* Designed PDF processing around limited memory using page-by-page streaming and micro-batched indexing.
* Configured the inference runtime to reduce memory overhead in constrained environments.
* Implemented a GitHub Webhook-based update mechanism for updating indexed knowledge during deployment.

---

### 📦 [LexiByte](https://github.com/bibek-dhakal/lexibyte)

**Byte-Pair Encoding tokenizer implemented from scratch and published as a Python package on PyPI.**

* Implemented GPT-style regex pre-tokenization using Unicode-aware patterns for words, numbers, and punctuation.
* Built a frequency dictionary during BPE training to reduce unnecessary merge checks.
* Added memoization to avoid repeated tokenization work during inference.
* Implemented UTF-8 byte-level fallbacks to avoid out-of-vocabulary failures.
* Published the package to PyPI.

```bash
pip install lexibyte
```

---

### ⚡ [Forge-LM](https://github.com/bibek-dhakal/forge-lm) & [NanoTransformer](https://github.com/bibek-dhakal/nanotransformer)

**A project exploring Transformer implementation, training, optimization, and lightweight inference.**

#### 🧠 [NanoTransformer](https://github.com/bibek-dhakal/nanotransformer)

* Implemented a GPT-2-style Transformer decoder using PyTorch primitives.
* Integrated the custom **LexiByte BPE tokenizer**.
* Experimented with **FlashAttention** and **bfloat16 mixed precision** for training.
* Built the architecture to understand Transformer components and training mechanics from the implementation level.

#### 🚀 [Forge-LM](https://github.com/bibek-dhakal/forge-lm)

* Scaled the architecture to approximately **28M parameters**.
* Trained the model on the **TinyStories** dataset.
* Used gradient accumulation to work within approximately **6 GB VRAM**.
* Exported the model to **ONNX** and applied **INT8 dynamic quantization** for lightweight inference.
* Built a **FastAPI + NumPy inference service**.
* Containerized the application using Docker and tested it in low-memory deployment environments.

---

### 🛡️ [Multimodal Phishing Detection Platform](https://github.com/bibek-dhakal/multimodal-phishing-detection-platform)

**Phishing detection system combining structured URL features with linguistic signals.**

* Combined structured URL features from **ISCX** with linguistic features from **PhiUSIIL**.
* Implemented a **soft-voting fusion** approach across the models.
* Used XGBoost with **Platt scaling through `CalibratedClassifierCV`** for probability calibration.
* Exposed the model through **FastAPI**.
* Built an interactive **Streamlit** interface for evaluation.
* Used **Docker Compose** to run the application components.

---

### 🌐 [ZeroProp Engine & Live WebSocket Dashboard](https://github.com/Bibek-Dhakal/zero-prop-api/)

**Neural-network engine implemented without a deep-learning framework, with real-time training visualization.**

* Implemented dense layers, ReLU activation, and Softmax Cross-Entropy using **NumPy matrix operations**.
* Implemented the training pipeline to understand forward propagation, loss calculation, and backpropagation at a lower
  level.
* Added **FastAPI WebSockets** to stream training metrics.
* Built a **React + HTML5 Canvas** interface to visualize epoch, loss, and accuracy in real time.

---

## 💼 Experience

### Machine Learning & AI Experience

**AI / ML Engineering Intern** — *FlyRank AI* | **Jul 2026 – Sep 2026**

* Engineered a **CTR Opportunity Scoring** model acting as a decision-support system to prioritize SEO metadata reviews.
* Used **DuckDB** to query and aggregate large-scale Parquet datasets (**~79M rows**) directly from Hugging Face,
  avoiding RAM bottlenecks, while training the final ML models on a 30k-row analytical slice.
* Conducted rigorous model evaluation, successfully identifying and mitigating client-overlap data leakage via strict
  grouped validation splits.
* Framed machine learning outputs as a human-in-the-loop action playbook, focusing on precision and real-world business
  constraints.
* Authored and deployed a comprehensive [Research Paper](https://bibek-dhakal.github.io/applied-search-intelligence/)
  detailing the validation methodology and error analysis.
* Completed various **Anthropic Academy certifications** for AI fluency and Claude API proficiency.

### Training & Apprenticeships

**Data Science & ML Apprentice** — *Skill Shikshya* | **Apr 2026 – June 2026**

* Completed a hands-on learning track covering machine-learning mathematics, vector computation, classical ML, and
  deep-learning concepts.
* Implemented ML concepts through practical exercises and projects.
* Built and served ML applications using **FastAPI**.
* Used **Docker** to containerize applications.
* Completed and defended the final project in **July 2026**.
* Completed **Kaggle certifications for Pandas, Feature Engineering, Intro to ML, and Intermediate ML**.
* Completed **Skill Shikshya certifications for Data Science & ML Diploma**.

---

### Software Engineering Contracts & Internships Along with Bachelor's Degree

**Full-Stack Engineer Intern** — *Walkers Hive IT Professionals* | **Oct 2025 – Dec 2025** *(Mandatory Academic
Internship)*

* Independently designed and implemented the architecture for the **AcademiaOS MVP**.
* Built backend services using **FastAPI and Celery**.
* Developed the frontend using **Next.js**.
* Implemented HTTP-only cookie authentication and **role-based access control (RBAC)**.
* Used Docker as part of the application development and deployment setup.

**Software Engineer** — *Nextwave Technology* | **Apr 2025 – Jul 2025** *(Contract)*

* Worked on new features, bug fixes, UI revamp, and the Google Play Store launch of the **Academia** mobile application.
* Maintained and fixed existing Flutter codebases.
* Migrated corporate websites to **Next.js**-based implementations.

**Software Engineer** — *Walkers Hive IT Professionals* | **Nov 2024 – Apr 2025** *(Contract)*

* Built an e-commerce administration panel using **React, MUI, and Redux-Saga**.
* Developed Next.js frontends integrated with existing PHP backends.
* Worked across frontend development, application integration, and deployment.

**Android Development Intern** — *CodSoft* | **Dec 2023 – Jan 2024** *(Internship)*

* Developed Flutter applications with **Firebase Authentication**.
* Implemented local persistence and **BLoC state management**.
* Worked on application UI and BAAS integration.

---

## 🎓 Education

### Bachelor of Computer Application (BCA)

**Nihareeka College of Management and Information Technology**
*Tribhuvan University, Nepal • Completed Final Semester Coursework and Examination on August 2026*

**Status:** **Fully available with no remaining academic obligations.**

---

## 📜 Certifications

* **FlyRank AI — Machine Learning Internship Certificate**
  [Link](https://internship.flyrank.ai/verify/FR-D11-20CBF-CC2BF?first_name=Bibek)
* **Skill Shikshya — Data Science & ML Diploma** [Link](https://skillshikshya.com/verify-certificates/DSAMLDC260023)

## Anthropic Academy Certifications:

* **Anthropic Academy — Claude Code in Action** [Link](https://verify.skilljar.com/c/ho48cm8wcsa9)
* **Anthropic Academy — Building with the Claude API** [Link](https://verify.skilljar.com/c/hg695uod5bb8)
* **Anthropic Academy — MCP Advanced Topics** [Link](https://verify.skilljar.com/c/bf7vbtdiv8ti)
* **Anthropic Academy — Claude on Amazon Bedrock** [Link](https://verify.skilljar.com/c/gesgzvi2zhk5)
* **Anthropic Academy — Claude on Google Vertex AI** [Link](https://verify.skilljar.com/c/umhhhrba6gkf)

### Kaggle Certificates: [Link](https://www.kaggle.com/bibekdhakal8366)

* **Kaggle — Pandas**
* **Kaggle — Feature Engineering**
* **Kaggle — Intro to Machine Learning**
* **Kaggle — Intermediate Machine Learning**

### 🏆 Artifacts

* **Deployed ML Research Paper: CTR Opportunity Score**
  [Read Here](https://bibek-dhakal.github.io/applied-search-intelligence/)
  A public research paper detailing my methodology on evaluating ML models honestly, mitigating data leakage, and
  framing ML as a decision-support tool.
* **LunarLander-v2 Agent** [Link](https://huggingface.co/imbibek8366/ppo-LunarLander-v2)
  Trained an autonomous agent to safely navigate a lunar module to its landing pad using the Proximal Policy
  Optimization (PPO) algorithm.

---

## 📫 Let's Connect

* **Email:** [imbibek8366@gmail.com](mailto:imbibek8366@gmail.com)
* **LinkedIn:** [linkedin.com/in/bibek-dhakal-771ba5334](https://www.linkedin.com/in/bibek-dhakal-771ba5334/)
* **Portfolio:** [Portfolio](https://bibek-dhakal-fr.vercel.app/)

---
