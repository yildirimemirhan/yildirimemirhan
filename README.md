### Hi, I'm Emirhan 👋

**Applied ML Engineer | Computer Vision · LLM Systems · Production ML**

I specialize in bridging the gap between AI prototypes and production. Whether it's training robust Computer Vision models, designing Retrieval-Augmented Generation (RAG) pipelines, or building high-throughput streaming architectures, my focus is on engineering scalable, real-world ML systems.

---

#### 🚀 What I Do

- **Applied AI & ML:** Training deep learning (CV) and generative AI (LLM/RAG) models, deploying them as production-ready microservices with a focus on out-of-distribution (OOD) generalization and explainability.
- **MLOps & Data Pipelines:** Building automated training pipelines, CI/CD for model deployment (GitHub Actions, Docker), and out-of-core streaming architectures (Dask, drift detection).
- **Backend & Systems Engineering:** Architecting fault-tolerant backend workflows, high-concurrency data ingestion pipelines, and resilient multi-threaded systems.

#### 🛠 Core Stack

- **ML & Deep Learning:** `PyTorch` `TensorFlow` `Scikit-Learn` `Transformers` `Sentence Transformers`
- **Computer Vision & NLP:** `OpenCV` `Image Processing` `RAG` `ChromaDB` `Spotify Annoy`
- **Data & Backend:** `Python` `FastAPI` `Flask` `PostgreSQL` `Dask (ETL)` `Pandas` `SQL`
- **DevOps & Infrastructure:** `Docker` `GitHub Actions (CI/CD)` `Git` `Linux`
- **Systems & Automation:** `Multithreading` `Appium` `Selenium` `UiAutomator2`

---

#### 🔬 Featured Projects

| Project | Description |
| :--- | :--- |
| [**wbc-analyzer**](https://github.com/frissonitte/wbc-analyzer) | End-to-end WBC classification system deployed as a Flask REST API. Features a custom architecture (DenseNet121 + WBCAttention + MedSwish). Incorporates inference-time domain adaptation achieving an 89.05% out-of-distribution (OOD) accuracy (+32.09 pp boost). Includes a multi-modal LLM agent (GPT-4o & Gemini) for clinical XAI insights. Preprint published on ResearchGate. |
| [**rag-project-assistant**](https://github.com/frissonitte/rag-project-assistant) | Hybrid-source RAG system answering questions about my portfolio projects. Combines AST-extracted code structure with curated documentation, using similarity-threshold gating (ChromaDB, L2 < 1.40) to prevent hallucination on out-of-scope queries. Deployed on Hugging Face Spaces (Docker, FastAPI, Groq Llama 3.3 70B) with rate-limited public API and a live chat widget. |
| [**kinematic-action-recognition**](https://github.com/frissonitte/kinematic-action-recognition) | Full end-to-end ML pipeline on 10 GB motion-capture sensor data. Features out-of-core ingestion with **Dask**, real-time streaming with drift detection (81 windows/sec), and a LightGBM/RandomForest ensemble achieving 0.94169 accuracy on Kaggle. |
| [**popcorn-wagon**](https://github.com/frissonitte/popcorn-wagon) | Hybrid movie recommender engine built with **Dask/Pandas** for scalable ETL and Spotify Annoy for sub-millisecond similarity search. Integrates collaborative filtering (SVD) and content-based filtering. |
| [**listing-pilot**](https://github.com/frissonitte/listing-pilot) | Config-driven mobile automation suite managing ~1,000 active listings across C2C marketplaces. Built with Appium and Python, featuring overlap detection, multi-ID fallbacks, and real-time Telegram alerting. Reduced daily manual workload by over 90%. |
| [**portal-cleaner-ultimate**](https://github.com/frissonitte/portal-cleaner-ultimate) | Modular backend automation suite featuring a custom local test harness for offline ERP simulation. Engineered with fault-tolerant retry logic, slashing manual operational workloads by over 90% (saving 4-6 hours daily). |
