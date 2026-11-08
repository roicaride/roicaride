# Hi, I'm Roi Caride 👋

**AI Engineer focused on NLP** · MSc student in Computing – AI with NLP at **Dublin City University** · Based in **Dublin, Ireland** 🇮🇪

I build and evaluate LLM systems: retrieval-augmented generation, fine-tuning, and rigorous evaluation. I'm interested in language modelling and machine translation.

---

## 🔭 What I'm doing

- 🎓 **MSc in Computing – AI with NLP** @ Dublin City University (2026–2027)
- 🤖 **AI Engineer Intern** @ Altia Consultores (2026) — built a RAG system over internal documentation using open-source LLMs running locally (Qwen via Ollama)
- 💼 **Open to** part-time roles and internships in AI / NLP during my MSc, and full-time positions from 2027

---

## 📌 Featured projects

### [rag-sweep](https://github.com/roicaride/rag-sweep) — Bachelor's thesis (9.7/10)

A reproducible framework for finding the RAG configuration that actually works on *your* corpus. It runs a sequential ablation over embeddings, chunking, retrieval, query expansion and reranking, and carries each stage's winner forward into the next. New variants are added through YAML, not code.

- **Case study:** EU copyright law (EUR-Lex), 29 full configurations evaluated with 6 RAGAS metrics and an independent judge LLM
- **+59%** precision + recall over a naive baseline
- The empirically found configuration beat a "state-of-the-art" stack assembled from the literature by **~9%**, at a lower cost to run
- **Stack:** Kedro · LangChain · RAGAS · Qdrant · MLflow

### [Viñalert](https://github.com/roicaride/vinalert) — Precision viticulture platform 🍇

🏆 Winner of the *Semente Ribeira Sacra* university hackathon.

A full vertical slice from sensor to screen. Solar-powered ESP32 nodes with RS-485 soil probes report over LoRa (868 MHz) to a master node, which uploads the readings to a FastAPI + PostgreSQL backend. Each reading is enriched with the weather at that exact moment, and a React web app turns the data into irrigation guidance and agronomic analysis.

- Evapotranspiration-based water balance, treatment logs, foliar sensor ingestion and time-series analysis
- Multi-tenant access with per-plot roles, plus revocable IoT device tokens
- The sampling interval is tuned remotely from the web UI, with no reflashing
- **305 backend + 86 frontend tests**
- **Stack:** ESP32 / Arduino · LoRa · FastAPI · PostgreSQL · SQLAlchemy · APScheduler · React · Vite · Tailwind

### Other projects

| Project | What it is | Stack |
| --- | --- | --- |
| [titanic-top-4.7](https://github.com/roicaride/titanic-top-4.7) | Kaggle Titanic — **top 4.7%**. Feature engineering and comparison of five tuned classifiers | scikit-learn · XGBoost |
| [SongRecommender](https://github.com/roicaride/SongRecommender) | Content-based music recommender: K-Means clustering + in-cluster k-NN over Spotify audio features, served by a Flask API | Flask · scikit-learn · pandas |
| [Edge detection with U-Net](https://github.com/roicaride/Image-Dataset-Explorer-and-Preprocessing) | Image preprocessing pipeline and U-Net for edge detection, compared against watershed segmentation | TensorFlow · OpenCV |

---

## 🧠 Focus areas

- **LLMs & RAG** — retrieval, chunking strategies, reranking, local model deployment
- **Evaluation** — ablation studies, gold dataset generation, RAGAS metrics, LLM-as-judge
- **Fine-tuning** — LoRA / parameter-efficient methods
- **NLP** — language modelling, multilingual text, machine translation

---

## ⚡ Tech stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**LLMs & NLP**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white)
![RAGAS](https://img.shields.io/badge/RAGAS-6E40C9?style=flat)

**ML & Data**
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Kedro](https://img.shields.io/badge/Kedro-FFC900?style=flat&logo=kedro&logoColor=black)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)

**Backend, Web & IoT**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino%20%2F%20ESP32-00878F?style=flat&logo=arduino&logoColor=white)

**Tools**
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat&logo=latex&logoColor=white)

---

## 🌍 Languages

Spanish & Galician (native) · English (fluent) · Portuguese (fluent) · Italian & French (reading)

---

## 🎓 Education

- **MSc in Computing – AI with NLP** · Dublin City University · 2026–2027
- **BSc in Business and Technology** · University of Santiago de Compostela · 2026

---

## 📫 Let's connect

- **Portfolio:** [roicaride.github.io](https://roicaride.github.io)
- **Email:** [roicaride4@gmail.com](mailto:roicaride4@gmail.com)
- **LinkedIn:** [Roi Caride Borrajo](https://linkedin.com/in/roi-caride-borrajo-1167a4227)
- **Telegram:** [@roicaride](https://t.me/roicaride)
