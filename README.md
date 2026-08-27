# Hi, I'm Bibek Dhakal 👋

### AI / Machine Learning Engineer | PyTorch • LLMs • FastAPI • ML Systems

*Kathmandu, Nepal • [imbibek8366@gmail.com](mailto:imbibek8366@gmail.com)*

I am an **entry-level AI / Machine Learning Engineer** with a software engineering background and a focus on building
machine-learning systems from first principles through deployment.

My work spans **PyTorch, Transformer architectures, tokenization, ML inference, data processing, LLM applications,
FastAPI backends, and Docker-based deployment**. I enjoy understanding how ML systems work underneath high-level
abstractions and turning those implementations into usable software.

**🎯 Current:** AI / ML Intern at FlyRank AI  
**🎓 Education:** BCA final examinations completed in August 2026; official degree pending  
**💼 Status:** **Available immediately for full-time employment**  
**🔎 Seeking:** **Associate / Junior ML Engineer, AI Engineer, or Entry-Level ML Engineer roles**

---

## 🚀 What I Work On

* 🧠 **Machine Learning & Deep Learning** — PyTorch, TensorFlow, Scikit-Learn, Transformer architectures
* 🤖 **LLMs & NLP** — tokenization, BPE, RAG, AI agents, Hugging Face
* ⚡ **ML Inference** — ONNX Runtime, INT8 quantization, CPU inference, memory optimization
* 📊 **Data Processing** — DuckDB, BigQuery, PostgreSQL, Pandas, NumPy
* 🔧 **Backend & Deployment** — FastAPI, Docker, Celery, Redis, REST APIs, WebSockets
* 🌐 **Applications** — React, Next.js, Streamlit, Flutter

---

## 🛠 Tech Stack

| Category                  | Technologies                                                           |
|:--------------------------|:-----------------------------------------------------------------------|
| **Languages**             | Python, TypeScript, SQL, C#, Dart                                      |
| **Machine Learning & AI** | PyTorch, TensorFlow, Scikit-Learn, NumPy, Pandas, OpenCV, Hugging Face |
| **LLM / Inference**       | Transformers, ONNX Runtime, FAISS, FlashAttention, BPE Tokenization    |
| **Data & Databases**      | DuckDB, Google BigQuery, PostgreSQL, Redis                             |
| **Backend & Deployment**  | FastAPI, Celery, Docker, REST APIs, WebSockets, Flower                 |
| **Frontend & Mobile**     | React, Next.js, TailwindCSS, Flutter                                   |

---

# 📌 Featured Projects

## 🛡️ [Aegis Omnisearch Agent](https://github.com/bibek-dhakal/aegis-api)

**Lightweight RAG agent designed for resource-constrained deployments.**

* Implemented a custom **ReAct-style Reason + Act loop** using Google's Gemini API for tool selection and grounded
  responses.
* Built local retrieval using **FAISS** and used **INT8 ONNX Runtime** for lightweight CPU inference.
* Designed PDF processing around limited memory using page-by-page streaming and micro-batched indexing.
* Configured the inference runtime to reduce memory overhead in constrained environments.
* Implemented a GitHub Webhook-based update mechanism for updating indexed knowledge during deployment.

---

## 📦 [LexiByte](https://github.com/bibek-dhakal/lexibyte)

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

## ⚡ [Forge-LM](https://github.com/bibek-dhakal/forge-lm) & [NanoTransformer](https://github.com/bibek-dhakal/nanotransformer)

**A project exploring Transformer implementation, training, optimization, and lightweight inference.**

### 🧠 [NanoTransformer](https://github.com/bibek-dhakal/nanotransformer)

* Implemented a GPT-2-style Transformer decoder using PyTorch primitives.
* Integrated the custom **LexiByte BPE tokenizer**.
* Experimented with **FlashAttention** and **bfloat16 mixed precision** for training.
* Built the architecture to understand Transformer components and training mechanics from the implementation level.

### 🚀 [Forge-LM](https://github.com/bibek-dhakal/forge-lm)

* Scaled the architecture to approximately **28M parameters**.
* Trained the model on the **TinyStories** dataset.
* Used gradient accumulation to work within approximately **6 GB VRAM**.
* Exported the model to **ONNX** and applied **INT8 dynamic quantization** for lightweight inference.
* Built a **FastAPI + NumPy inference service**.
* Containerized the application using Docker and tested it in low-memory deployment environments.

---

## 🛡️ [Multimodal Phishing Detection Platform](https://github.com/bibek-dhakal/multimodal-phishing-detection-platform)

**Phishing detection system combining structured URL features with linguistic signals.**

* Combined structured URL features from **ISCX** with linguistic features from **PhiUSIIL**.
* Implemented a **soft-voting fusion** approach across the models.
* Used XGBoost with **Platt scaling through `CalibratedClassifierCV`** for probability calibration.
* Exposed the model through **FastAPI**.
* Built an interactive **Streamlit** interface for evaluation.
* Used **Docker Compose** to run the application components.

---

## 🌐 [ZeroProp Engine & Live WebSocket Dashboard](https://github.com/Bibek-Dhakal/zero-prop-api/)

**Neural-network engine implemented without a deep-learning framework, with real-time training visualization.**

* Implemented dense layers, ReLU activation, and Softmax Cross-Entropy using **NumPy matrix operations**.
* Implemented the training pipeline to understand forward propagation, loss calculation, and backpropagation at a lower
  level.
* Added **FastAPI WebSockets** to stream training metrics.
* Built a **React + HTML5 Canvas** interface to visualize epoch, loss, and accuracy in real time.

---

# 💼 Experience

### AI / ML Intern — FlyRank AI

**Jul 2026 – Present**

* Working on **CTR Opportunity Scoring** and decision-support ML work using datasets containing **70M+ rows**.
* Using **DuckDB and Google BigQuery** for large-scale data querying and analysis.
* Working on feature preparation and ML workflows for decision-support use cases.
* Working with modern AI development tools, including Claude and Claude Code.
* Completed **Anthropic Academy certifications for Claude and Claude Code**.

### Data Science & ML Apprentice — Skill Shikshya

**Apr 2026 – Jul 2026**

* Completed a hands-on learning track covering machine-learning mathematics, vector computation, classical ML, and
  deep-learning concepts.
* Implemented ML concepts through practical exercises and projects.
* Built and served ML applications using **FastAPI**.
* Used **Docker** to containerize applications.
* Completed and defended the final project in **July 2026**.
* **Certification pending.**

### Full-Stack Engineer Intern — Walkers Hive IT Professionals

**Oct 2025 – Dec 2025**

*Academic internship*

* Independently designed and implemented the architecture for the **AcademiaOS MVP**.
* Built backend services using **FastAPI and Celery**.
* Developed the frontend using **Next.js**.
* Implemented HTTP-only cookie authentication and **role-based access control (RBAC)**.
* Used Docker as part of the application development and deployment setup.

### Software Engineer — Nextwave Technology

**Apr 2025 – Jul 2025**

*Contract*

* Worked on the Google Play Store launch of the **Academia** mobile application.
* Maintained and fixed existing Flutter codebases.
* Migrated corporate websites to **Next.js**-based implementations.

### Software Engineer — Walkers Hive IT Professionals

**Nov 2024 – Apr 2025**

*Contract*

* Built an e-commerce administration panel using **React, MUI, and Redux-Saga**.
* Developed Next.js frontends integrated with existing PHP backends.
* Worked across frontend development, application integration, and deployment.

### Android Development Intern — CodSoft

**Dec 2023 – Jan 2024**

* Developed Flutter applications with **Firebase Authentication**.
* Implemented local persistence and **BLoC state management**.
* Worked on application UI and backend integration.

---

# 🎓 Education

### Bachelor of Computer Application (BCA)

**Nihareeka College of Management and Information Technology**
*Tribhuvan University, Nepal • 2021 – 2026*

**Status:** Final examinations completed in **August 2026**. Official degree pending.

---

# 📜 Certifications

* **Anthropic Academy — Claude**
* **Anthropic Academy — Claude Code**
* **Skill Shikshya — Data Science & ML Track** *(certification pending)*

---

# 📫 Let's Connect

* **Email:** [imbibek8366@gmail.com](mailto:imbibek8366@gmail.com)
* **LinkedIn:** [linkedin.com/in/bibek-dhakal-771ba5334](https://www.linkedin.com/in/bibek-dhakal-771ba5334/)

---

## 💼 Open to Full-Time Opportunities

I'm currently seeking **entry-level / associate roles** in:

`Associate ML Engineer` · `Junior ML Engineer` · `AI Engineer` · `Entry-Level ML Engineer`

I'm particularly interested in teams working on **LLM applications, machine-learning systems, inference optimization,
intelligent backend services, and ML/data pipelines**.

I'm also open to **MLOps / ML Platform opportunities** where the role is suitable for an early-career engineer with
hands-on experience in **Docker, FastAPI, model serving, and ML deployment**.

---
