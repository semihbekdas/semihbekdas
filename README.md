<h1 align="center">Hi, I'm Semih Bekdaş 👋</h1>

<p align="center">
  Computer Engineering student at İstanbul Medeniyet University (class of 2027) · Machine Learning · LLMs &amp; Agents · Time Series
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/semihbekda%C5%9F/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://huggingface.co/SemihBekdas"><img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face"></a>
  <a href="https://medium.com/@semihbekdass"><img src="https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white" alt="Medium"></a>
  <a href="mailto:semihbekdass@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

## 🏆 Highlights

- 🥇 **1st place (individual), Türk Telekom AI Camp 2026** — selected among 30 finalists from 4,464 applicants. Won with **BundleKom**, a telecom customer-analytics and RAG / tool-calling copilot built on 200k customers × 36 months of data.
- 🏅 **Top 5, Trendyol–TEKNOFEST E-Commerce Hackathon 2026** — with team **DualCore**: 5th of 377 teams in the Kaggle stage and 5th among the 10 finalists. Search-relevance system with two Gemma-4-12B LoRA adapters fused by a HistGradientBoosting decision model.

## 🔭 What I work on

- **LLMs & agents** — RAG, tool calling, LangGraph agents, LoRA fine-tuning (Llama 3.1, Gemma), knowledge-graph-grounded decision support.
- **Time series & predictive maintenance** — RUL prediction, industrial anomaly detection (Anomalib, MVTec-AD), explainable AI, representation probing.
- **Turkish NLP** — BERTurk / XLM-R classification, safe domain assistants, search relevance and similarity analysis.
- **End-to-end delivery** — FastAPI + PostgreSQL + React/TypeScript backends, MLflow experiment tracking, Docker.

## 💼 Experience

| Where | Role | When | What I built |
| :--- | :--- | :--- | :--- |
| **Ümraniye District Governorship** | Intern | Aug – Sep 2026 | Media-monitoring system (FastAPI, PostgreSQL, React/TS) with duplicate detection, role-based access and explainable Turkish sentiment / risk / category analysis with alerts and daily reports |
| **ROKETSAN STAGE** | Software & Digital Design Intern | Jul – Aug 2026 | Python assembler that parses DMA instructions from hardware documentation and emits binary / hex machine code, with syntax and rule validation and unit tests |
| **BekTech** | Machine Learning & LLM Intern | Mar – May 2026 | Predictive maintenance and RUL on multivariate time series; benchmarked ML, deep learning and foundation models by RMSE and NASA score; LLM-based decision-support prototypes |

## 🚀 Featured projects

| Project | What it does | Stack |
| :--- | :--- | :--- |
| [**Cüzdan Koçu — AI Family Finance Coach**](https://github.com/semihbekdas/btk-hackathon) | Family budgeting with goals and envelopes, receipt OCR and role-based data access; a LangGraph agent with tool calling, user-approved actions, SSE streaming and speech-to-text / text-to-speech. | Next.js · FastAPI · PostgreSQL · MinIO · LangGraph |
| [**Sina — Turkish Health Assistant**](https://github.com/semihbekdas/yapay-zeka-saglik-asistani-sina) | Routes patient questions to one of 16 medical specialties on 48,816 balanced samples (BERTurk, 0.69 macro-F1) and answers with a Llama 3.1 8B model fine-tuned via 4-bit LoRA, with PII cleaning and safety filters. [Model on Hugging Face](https://huggingface.co/SemihBekdas/Llama3.1-8B-TR-PatientQA-LoRA-v1). | PyTorch · Transformers · Unsloth · Ollama · Streamlit |
| [**CopyGuard — Turkish Similarity & Plagiarism Analysis**](https://github.com/semihbekdas/CopyGuard) | Hybrid similarity over PDF / DOCX / PPTX / TXT / Markdown combining MinHash, TF-IDF, embeddings and block overlap; live progress over SSE and CSV / HTML / SVG / PNG reports. | FastAPI · Next.js · SQLAlchemy |
| [**MovieMind — Hybrid Movie Recommender**](https://github.com/semihbekdas/MovieRecommender) | Content-based, item-based collaborative filtering and Apriori association rules behind a full-stack app with profiles, friends and TMDB integration. | React/TS · Node/Express · Flask · scikit-learn |
| [**Appointment No-Show Prediction**](https://github.com/semihbekdas/appointment-no-show-ml) | LightGBM + SMOTETomek + threshold tuning on 110k medical appointments, 83% recall on no-shows. [Live demo](https://appointment-no-show-ml.streamlit.app/). | scikit-learn · LightGBM · Streamlit |
| [**ŞehirPulse AI**](https://github.com/semihbekdas/sehirpulse-ai) | Citizen complaint intake that classifies requests and routes them to the right municipal unit; CI, Docker and a Scrum team workflow. | FastAPI · React · SQLite · Docker |
| [**Emergency Drone Coordination**](https://github.com/semihbekdas/Drone-Simulator) | Multithreaded C client-server simulator: thread-safe lists, free-list memory management, TCP/JSON protocol, heartbeat and an SDL2 real-time viewer. | C · pthreads · SDL2 · json-c |
| [**Multi-User Communicating Shells**](https://github.com/semihbekdas/Shell) | GTK4 terminal where parallel shells exchange messages over POSIX shared memory; pipes, redirection and history. | C · GTK4 · POSIX |

### More work (competition / research, private repos)

- **BundleKom** — telecom customer lifecycle, usage and complaint analytics on DuckDB; churn model validated over time with PR-AUC, Precision@K, Lift@K and calibration; RAG + tool-calling copilot with ChromaDB. *Türk Telekom AI Camp 2026, 1st place.*
- **Trendyol–TEKNOFEST search relevance (DualCore)** — hard-negative mining supervised by an LLM, two Gemma-4-12B LoRA adapters with different error profiles, HistGradientBoosting fusion with explainability. *Top 5 of 377 teams.*
- **Turbofan RUL with foundation models** — zero-shot Chronos / TimesFM, frozen-backbone heads, LoRA and full fine-tuning vs. LSTM / BiLSTM / CNN-1D / Transformer on C-MAPSS FD001–FD004 and PHM08; representation analysis with linear probing, PCA / t-SNE and latent-direction stress tests.
- **LLM + knowledge-graph fault diagnosis** — FAISS RAG, NetworkX symptom–cause–solution graph and a multi-agent flow on 4-bit Mistral-7B-Instruct with retrieval verification and source-controlled answers.

## 🛠️ Tech stack

**ML / AI**
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain">
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square" alt="LangGraph">
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV">
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white" alt="MLflow">
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy">
</p>

**Backend / Data**
<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black" alt="DuckDB">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square" alt="SQL">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit">
</p>

**Frontend / Systems**
<p>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" alt="C">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
</p>

## 🤝 Community

- **Kairu** — Community Relations Manager (Aug 2025 – Mar 2026). Coordinated AI / data-science training partnerships with university clubs; taught a hands-on MLflow experiment-tracking and model-versioning session at AIdea Project Camp.
- **SistersLab** — AI Bootcamp Assistant, volunteer (May – Jul 2025). Reviewed participant assignments and mentored on machine learning, Python and NLP.

## 📊 GitHub activity

<p align="center">
  <img src="https://ghchart.rshah.org/2f81f7/semihbekdas" alt="Contribution graph" width="100%">
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=semihbekdas&theme=tokyonight&hide_border=true&date_format=j%20M%5B%20Y%5D" alt="Contribution streak">
</p>
