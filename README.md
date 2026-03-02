<h1 align="center">Hey, I'm Faisal 👋</h1>

<p align="center">
  <b>AI/ML Engineer</b> · Production AI/ML Systems · Computer Vision · MLOps<br/>
  I build AI/ML systems that actually run in production — with real latency numbers, cost tracking, and postmortems.
</p>

<p align="center">
  <a href="https://www.faisal-ai.me">🌐 Portfolio</a> &nbsp;·&nbsp;
  <a href="https://linkedin.com/in/faisal-ahmed-bb2028184">💼 LinkedIn</a> &nbsp;·&nbsp;
  <a href="mailto:faisaltitu.work@gmail.com">📧 Email</a>
</p>

---

## 🔧 What I Build

I focus on **end-to-end ML systems** — from model training to production serving, monitoring, and self-healing. Every project below has real infrastructure, real metrics, and real production incidents that I debugged.

---

## 🚀 Flagship Projects

### [Personalized AI Image Search Engine](https://github.com/faisal-titu/ai-api-gateway-mvp) &nbsp; [![Live](https://img.shields.io/badge/Live_Demo-blue?style=flat-square)](https://www.faisal-ai.me/project/ai-image-search-engine)

> Multimodal semantic search across 25K+ personal images using CLIP + OpenSearch on AWS

```
→ p50 = 164 ms, p95 ~500 ms, cost ~$0.001/req (~$31/mo infra)
→ ONNX Runtime: 2.6× faster inference (402 ms → 140 ms), 340 MB less RAM
→ HNSW tuning: 3.3× faster vector search (76 ms → 23 ms)
→ Stack: FastAPI + CLIP ViT-B/32 (ONNX) + OpenSearch k-NN + AWS EC2/S3 + Docker
→ Ops: Prometheus + Grafana, bulk indexing at 1,085 docs/sec
→ Postmortem: 3 production OOM incidents resolved on a 4 GB EC2 instance
```

### [MLOps Drift Detection System](https://github.com/faisal-titu/drift_detection_MLOPs) &nbsp; [![Live](https://img.shields.io/badge/Live_Dashboard-blue?style=flat-square)](https://www.faisal-ai.me/project/drift-detection-mlops)

> Self-healing ML pipeline — detects data drift, auto-retrains, validates, and hot-reloads with zero downtime

```
→ R² = 0.775, RMSE = $54.3K, MAE = $36.5K (California Housing, 20K samples)
→ p95 ~40 ms, p99 ~47 ms, 0 SLO breaches across 520+ requests
→ KS-test + PSI drift detection → 3-gate eval (R² ≥ 0.70, RMSE ≤ $100K) → hot-reload
→ Stack: FastAPI + scikit-learn + MLflow + Streamlit + SQLite + Docker
→ Ops: /metrics endpoint (p50/p95/p99), /rollback, GitHub Actions CI (16 tests in ~6s)
→ Postmortem: Streaming simulator caused 100% CPU lockup → fixed with retrain cap + cooldown
```

---

## 📂 Other Projects

| Project | Description | Stack |
|---|---|---|
| **LabelerSage** | Human-in-the-loop data annotation system for generating high-quality ML training data | Python, PyTorch, One-Shot Learning |
| **Universal Image Segmentation** | Object-level segmentation pipeline using Segment Anything Model (SAM) | Python, PyTorch, SAM, LabelStudio |
| **Diabetes Risk Prediction** | End-to-end ML pipeline with EDA, training, and Gradio web app (71% accuracy) | scikit-learn, FastAPI, Gradio, HF Spaces |
| **3D Image Classification** | Custom CNN for 3D volumetric image classification (78% accuracy) | PyTorch, CNN, Deep Learning |

---

## 🛠️ Tech Stack

**ML / AI** &nbsp; ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![ONNX](https://img.shields.io/badge/ONNX_Runtime-grey?style=flat-square) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![CLIP](https://img.shields.io/badge/OpenAI_CLIP-412991?style=flat-square)

**MLOps** &nbsp; ![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

**Serving** &nbsp; ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)

**Data** &nbsp; ![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=flat-square&logo=opensearch&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

---

## 📊 GitHub Stats

<p align="center">
  <!-- <img src="https://github-readme-stats.vercel.app/api?username=faisal-titu&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true" height="165" /> -->
  <!-- ![Stats](https://github-stats.vercel.app/api?username=faisal-titu&theme=dark) -->
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=faisal-titu&theme=github-dark-blue&hide_border=true" height="165" />
  <!-- ![GitHub Streak](https://github-readme-streak-stats.demolab.com/?user=faisal-titu&theme=github-dark-blue&hide_border=true) -->
</p>

---

<p align="center">
  <i>I care about latency, cost, and things that break in production.</i><br/>
  <a href="https://www.faisal-ai.me">www.faisal-ai.me</a>
</p>
