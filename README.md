### Hi, I'm Emirhan 👋

**Applied ML Engineer | Computer Vision · LLM & RAG Systems · MLOps**

I specialize in bridging the gap between AI prototypes and production-grade software. Whether it's training robust Computer Vision models that generalize across unseen hardware, designing Retrieval-Augmented Generation (RAG) microservices, or engineering sub-50ms low-level C++/GLSL streaming pipelines, my focus is on building resilient, high-performance ML systems.

---

#### 🚀 What I Do

- **Applied AI & Computer Vision:** Training deep learning architectures (DenseNet121, custom attention blocks) and deploying inference-time domain adaptation to eliminate out-of-distribution (OOD) accuracy drops in medical vision.
- **AI Engineering & RAG:** Building production RAG microservices with ChromaDB similarity threshold gating (L2 < 1.40), sentence-transformers, and LLM agent explainability layers (GPT-4o & Groq Llama 3.3 70B).
- **MLOps & Streaming Pipelines:** Architecting out-of-core data ingestion pipelines (Dask), real-time concept drift detection (ADWIN), containerized deployment (Docker, FastAPI, Hugging Face Spaces), and automated CI/CD workflows (GitHub Actions).
- **Low-Level Systems & Software Engineering:** Developing real-time C++/GLSL wearable video processing engines (OpenDalton) and multi-threaded desktop portal tools.

---

#### 🛠 Core Technical Stack

- **ML & Deep Learning:** `PyTorch` `TensorFlow` `Scikit-Learn` `LightGBM` `XGBoost` `Neural Networks`
- **AI Engineering & LLMs:** `RAG` `ChromaDB` `Sentence Transformers` `AI Agents` `Prompt Engineering` `Spotify Annoy`
- **Computer Vision & Signal AI:** `OpenCV` `Digital Image Processing` `GLSL Shaders` `Edge Computing` `Medical Image Analysis`
- **Languages & Frameworks:** `Python` `C++` `C#` `ASP.NET Core MVC` `Entity Framework Core` `FastAPI` `Flask` `SQL`
- **Infrastructure & MLOps:** `Docker` `GitHub Actions (CI/CD)` `Dask` `Pandas` `NumPy` `Linux` `Git` `Multi-threading`

---

#### 🔬 Featured Portfolio Projects

| Project                                                                                         | Description                                                                                                                                                                                                                                                                                                                              | Tech Stack                                              |
| :---------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------ |
| [**wbc-analyzer**](https://github.com/frissonitte/wbc-analyzer)                                 | End-to-end WBC pathology classification system. Features a custom architecture (DenseNet121 + WBCAttentionBlock + MedSwish). Inference-time domain adaptation boosted OOD accuracy from 56.96% to 89.05% (+32.09 pp) without model retraining. Includes GPT-4o & Gemini Grad-CAM clinical XAI agent. Preprint published on ResearchGate. | `PyTorch` `OpenCV` `Flask` `Docker` `Domain Adaptation` |
| [**OpenDalton**](https://github.com/frissonitte/OpenDalton)                                     | Real-time wearable assistive vision technology targeting sub-50ms latency for color vision deficiency (CVD) correction. Developed custom GLSL fragment shaders and C++ video stream pipelines (Currently under M.Sc. research, private repository).| `C++` `GLSL` `OpenCV` `Edge Computing` `Embedded ML`    |
| [**rag-project-assistant**](https://github.com/frissonitte/rag-project-assistant)               | Production RAG service providing structured QA over portfolio codebases and docs. Uses similarity-threshold gating (ChromaDB, L2 < 1.40) to prevent hallucination on out-of-scope queries. Live on HF Spaces as a FastAPI service with Docker containerization and IP rate limiting (~100 organic users).                                | `FastAPI` `ChromaDB` `Llama 3.3 70B` `Docker` `RAG`     |
| [**kinematic-action-recognition**](https://github.com/frissonitte/kinematic-action-recognition) | Full end-to-end streaming ML pipeline on 10 GB motion-capture sensor data. Features Dask out-of-core ingestion, real-time ADWIN drift detection (81 windows/sec, 59 MB peak RAM), and an ensemble achieving 0.9995 Macro F1 score.                                                                                                       | `Python` `Dask` `Scikit-Learn` `LightGBM` `MLOps`       |
| [**popcorn-wagon**](https://github.com/frissonitte/popcorn-wagon)                               | Scalable hybrid movie recommendation engine combining content-based filtering (TMDB API) and collaborative filtering (MovieLens + SVD) with Spotify Annoy sub-millisecond similarity search.                                                                                                                                             | `Python` `Pandas` `Spotify Annoy` `SQLAlchemy` `Flask`  |
