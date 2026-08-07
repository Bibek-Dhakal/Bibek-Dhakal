# Hi, I'm Bibek Dhakal 👋

### AI / Machine Learning Systems Engineer

*Kathmandu, Nepal • imbibek8366@gmail.com*

I am a software-minded Machine Learning Engineer bridging the gap between mathematical theory and production-grade
software systems. Currently working as an **AI / ML Intern at FlyRank AI**, engineering ML pipelines across 70M+ row
data warehouses, building custom LLM components, and deploying asynchronous backends.

---

### 👨‍💻 About Me & Immediate Availability

- **Current Status:** Coursework fully completed. Final BCA degree examinations begin on **August 11, 2026** (lasting
  approx. 1–2 weeks). **Available for immediate recruitment & full-time deployment starting mid-August 2026** upon exam
  completion (seeking Associate / Entry-Level Machine Learning Engineer, AI Engineer, or MLOps Engineer roles).
- **Flexibility:** My current internship is self-paced, and all coursework/training programs are complete, allowing 100%
  dedicated focus to full-time engineering commitments once exams conclude.
- **Career Journey:** Spent my university years balancing degree requirements alongside targeted contract software
  engineering roles, academic internships, and production ML pipelines.
- **Tech Stack Focus:** The tools listed below are strictly technologies I have actively shipped in production
  environments, deployed in microservices, or used to build open-source ML architecture. *(Secondary exposure to
  languages like PHP, C#, Java, and C is intentionally omitted to highlight primary engineering depth).*

---

### 🚀 Technical Focus & Strengths

- 🧠 **LLMs & Core Mechanics:** Tokenization engines from scratch (Published `lexibyte` on PyPI), custom PyTorch
  Transformer architectures, and FlashAttention optimizations.
- ⚡ **Asynchronous ML Systems & Backend:** High-throughput REST APIs, WebSockets, multi-stage Docker environments, and
  job queues built with **FastAPI, Celery, Redis, and Next.js**.
- 📊 **Applied Machine Learning & Data Pipelines:** Feature engineering, DuckDB/BigQuery SQL queries over multi-million
  row datasets, probability calibration, and multi-modal architectures.

---

### 🛠 Tech Stack

| Category                     | Technologies & Frameworks                                              |
|:-----------------------------|:-----------------------------------------------------------------------|
| **Languages**                | Python, TypeScript, SQL, C#, Dart                                      |
| **Machine Learning & AI**    | PyTorch, TensorFlow, Scikit-Learn, NumPy, Pandas, OpenCV, Hugging Face |
| **Data & Query Engineering** | DuckDB, Google BigQuery, PostgreSQL, Redis                             |
| **Backend & MLOps**          | FastAPI, Celery, Docker, Streamlit, REST APIs, WebSockets, Flower      |
| **Frontend & Mobile**        | React, Next.js, TailwindCSS, Flutter                                   |

---

### 📌 Featured Open Source & Systems Architecture

#### 1. 🛡️ [Aegis Omnisearch Agent](https://github.com/bibek-dhakal/aegis-api)

*Zero-framework RAG Agent & MLOps architecture built from scratch for low-resource cloud deployments.*

- Engineered a custom **ReAct (Reason + Act)** loop paired with Google's **Gemini API** for autonomous tool selection
  and grounded answers.
- Bypassed PyTorch bloat using quantized `INT8` **ONNX Runtime** and **FAISS** for local, low-latency CPU vector
  embeddings.
- Optimized for strict sub-512MB RAM constraints via page-by-page PDF streaming, micro-batched indexing ($N=2$), and
  arena memory management (`enable_cpu_mem_arena = False`).
- Designed a **Zero-Downtime MLOps pipeline** using GitHub Webhooks for atomic memory-pointer swapping during live model
  hot-updates.

#### 2. 📦 [LexiByte (PyPI Package)](https://github.com/bibek-dhakal/lexibyte)

*Production-grade, algorithmically optimized Byte-Pair Encoding (BPE) tokenizer published on PyPI.*

- Engineered **GPT-4 style regex pre-splitting** (`\p{L}`, `\p{N}`) to isolate words, numbers, and punctuation.
- Built a **Sennrich Frequency Dictionary** during training to reduce merge checks and integrated an O(1) memoization
  cache during inference.
- Features base UTF-8 fallbacks to prevent Out-Of-Vocabulary (OOV) errors.
- `pip install lexibyte`

#### 3. ⚡ [Forge-LM](https://github.com/bibek-dhakal/forge-lm) & [NanoTransformer](https://github.com/bibek-dhakal/nanotransformer)

*An end-to-end, hardware-optimized Generative AI ecosystem. Evolved from raw PyTorch math into a fully deployed
Full-Stack LLM application.*

- 🧠 **[NanoTransformer](https://github.com/bibek-dhakal/nanotransformer) (The Foundation)**
    - Engineered a GPT-2 style Transformer decoder from scratch using native PyTorch primitives.
    - Integrated **FlashAttention**, **bfloat16 Mixed-Precision**, and a custom **LexiByte BPE** tokenizer to achieve
      massive training throughput on consumer GPUs.

- 🚀 **[Forge-LM](https://github.com/bibek-dhakal/forge-lm) (The Production Evolution)**
    - Scaled the NanoTransformer architecture to ~28M parameters and trained on the *TinyStories* dataset, utilizing *
      *Gradient Accumulation** to bypass 6GB VRAM hardware limits.
    - Decoupled PyTorch from inference by exporting to **ONNX** with **INT8 dynamic quantization**.
    - Engineered a lightweight **FastAPI** + **NumPy** backend and stateless **Docker** deployment to successfully serve
      the AI on strict <512MB RAM cloud environments.

#### 4. 🛡️ [Multimodal Phishing Detection Platform](https://github.com/bibek-dhakal/multimodal-phishing-detection-platform)

*Automated URL threat evaluation system built on a layered multi-modal architecture.*

- Combines structured URL features (ISCX) and linguistic signals (PhiUSIIL) via a **Soft-Voting Fusion** aggregator.
- Wrapped XGBoost with **Platt Scaling (CalibratedClassifierCV)** for accurate probability output.
- Deployed with **FastAPI**, **Streamlit**, and orchestrated via **Docker Compose**.

#### 5. 🌐 [ZeroProp Engine & Live WebSocket Dashboard](https://github.com/Bibek-Dhakal/zero-prop-api/)

*Custom zero-dependency Neural Network Engine with real-time web visualization.*

- Built Dense layers, ReLU, and SoftmaxCrossEntropy loss purely in raw **NumPy** matrix calculus.
- Integrated **FastAPI WebSockets** to stream real-time training metrics (Epoch/Loss/Accuracy) directly to an
  interactive **React + HTML5 Canvas** client interface.

---

### 💼 Experience Highlights

- **AI / ML Intern @ FlyRank AI** *(Jul 2026 – Present)*: Building CTR Opportunity Scoring decision-support ML models
  across 70M+ row production datasets using DuckDB and BigQuery (Self-paced role). Earned Anthropic Academy
  certifications for Claude/Claude Code.
- **Data Science & ML Apprentice @ Skill Shikshya** *(Apr 2026 – Jul 2026)*: Completed rigorous hands-on engineering
  track spanning scratch-pad ML math, deep learning architectures, vector computation, and production MLOps.
  Successfully defended final project in July 2026 (certification pending).
- **Fullstack Engineer Intern (Academic Requirement) @ Walkers Hive IT Professionals** *(Oct 2025 – Dec 2025)*:
  Completed mandatory degree internship by leading the independent architecture of *AcademiaOS* MVP (FastAPI, Next.js,
  Celery, Docker, HTTP-only cookie auth, RBAC).
- **Software Engineer (Contract) @ Nextwave Technology** *(Apr 2025 – Jul 2025)*: Led Play Store launch for the "
  Academia" mobile app, fixed legacy Flutter codebases, and migrated corporate sites to dynamic Next.js platforms.
- **Software Engineer (Contract) @ Walkers Hive IT Professionals** *(Nov 2024 – Apr 2025)*: Built e-commerce admin panel
  with React/MUI/Redux-Saga and deployed full-stack Next.js frontends over legacy PHP backends.
- **Android Development Intern @ CodSoft** *(Dec 2023 – Jan 2024)*: Developed Flutter applications with Firebase
  authentication, local persistence, and BLoC state management.

---

### 🎓 Education

- **Bachelor of Computer Application (BCA)** *(2021 – 2026)*  
  **Niharika College of Management and Information Technology** *(Tribhuvan University, Nepal)*  
  *Status: Coursework completed; final examinations starting August 11, 2026 (degree completion mid-August 2026).*

---

📫 **Let's Connect:**

- **Email:** imbibek8366@gmail.com
- **LinkedIn:**
  [https://www.linkedin.com/in/bibek-dhakal-771ba5334/](https://www.linkedin.com/in/bibek-dhakal-771ba5334/)
