<div align="center">

# Owais Ahmad

**Computer Vision Researcher · AI Systems Engineer · 2× Stanford Code in Place Section Leader**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-owais--ahmad--ai-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/owais-ahmad-ai)
[![GitHub](https://img.shields.io/badge/GitHub-codeWithOwaisAhmad-181717?style=flat&logo=github&logoColor=white)](https://github.com/codeWithOwaisAhmad)
[![Email](https://img.shields.io/badge/Email-chaudharyowais971@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:chaudharyowais971@gmail.com)

</div>

---

## About

I'm a final-year CS student at Islamia University of Bahawalpur building research at the intersection of **RGB-D computer vision** and **foundation model evaluation**. My work focuses on what happens when you take perception tasks seriously — rigorous evaluation, real sensor data, and honest benchmarks instead of cherry-picked results.

Alongside research, I build production-grade AI systems: RAG pipelines, agentic workflows, and MLOps infrastructure. I've shipped these for clients on Upwork and as a freelance AI engineer.

Selected twice by Stanford University to teach programming to international students as a Code in Place Section Leader.

---

## Research

### Broiler Chicken Weight Estimation via RGB-D Sensing
*Target: WACV 2027 / CVPR 2027 Workshop · Status: Late draft, professor review*

Three-stage pipeline using Intel RealSense D435i: Mask R-CNN instance segmentation → 2,073-dimensional fused feature vector (16 geometric 2D + 9 depth 3D + 2,048 ResNet50) → LightGBM/XGBoost ensemble trained on 133 chickens.

**Key finding:** 9 hand-crafted depth features outperform 2,048 ResNet50 features for physical weight regression — geometric signal matters more than learned visual representation here. Evaluation uses animal-level GroupShuffleSplit to prevent data leakage, exposing a flaw in prior work that used frame-level splits.

---

### Motion Blindness in Video-Language Models (Idea 9)
*Target: arXiv 2026 · Status: All 7 pipeline stages complete on synthetic data*

Benchmark pipeline to test whether video-language models can perceive **depth-axis motion** — objects moving toward or away from the camera — as opposed to lateral motion. Full pipeline and Kaggle notebook complete. Awaiting real RealSense D435i footage for the final evaluation split.

---

## Experience

**Research Assistant — Deep Embed Lab** *(Oct 2025 – Present)*
Building RGB-D preprocessing pipelines with Open3D and OpenCV. Evaluating spatial reasoning in multimodal foundation models under controlled structural noise. Cloud GPU orchestration on Kaggle/Colab for zero-shot inference.

**AI Automation Engineer — DataMinds** *(Aug – Oct 2025)*
Engineered backend automation pipelines for international clients using Python, FastAPI, n8n, and Make.com. Managed async document processing and JSON schema optimization.

**Section Leader — Stanford Code in Place** *(2025 & 2026)*
Consecutively selected to teach weekly Python programming sections to international cohorts. Supported students from 15+ countries across debugging sessions, logic walkthroughs, and course forums.

**Freelance AI Engineer — Upwork** *(Ongoing)*
Delivered AI automation, RAG pipelines, and ML engineering for clients. Specialties: LangChain, VAPI voice agents, agentic workflows, Selenium automation.

**Python Automation Engineer — Bahawalpur Startup** *(Prior)*
Built Selenium-based automation bots and backend scripts for local business clients.

---

## Projects

| Project | Stack | What it does |
|---------|-------|-------------|
| [Flipkart Product Recommender](https://github.com/codeWithOwaisAhmad/flipkart_product_recommender) | LangChain · AstraDB · Kubernetes · Prometheus/Grafana | Production-grade e-commerce recommendation engine with full observability |
| [Medical Chatbot RAG Pipeline](https://github.com/codeWithOwaisAhmad/medical-chatbot) | FastAPI · Docker · AWS ECR · Jenkins CI/CD · Trivy | End-to-end MLOps pipeline with security scanning and container deployment |
| [Anime RAG Recommender](https://github.com/codeWithOwaisAhmad/anime-rag-recommender) | ChromaDB · Groq · LangChain | Semantic recommendation over a large anime corpus |
| [FastBite POS](https://github.com/codeWithOwaisAhmad) | C# .NET 10 · WinForms · SQL Server | Full restaurant point-of-sale system — dashboard, orders, menu, async loading. Scored 55/50 |
| [Multi-Agent AI System](https://github.com/codeWithOwaisAhmad/multi-ai-agent) | LangChain · Python | Orchestrated multi-agent pipeline with tool use and memory |

---

## Stack

```
Research      Python · PyTorch · OpenCV · Open3D · Intel RealSense SDK
              Mask R-CNN · LightGBM · XGBoost · Scikit-learn

LLM/Agents    LangChain · LlamaIndex · RAG · VAPI · n8n · Make.com

MLOps         FastAPI · Docker · AWS ECR · Jenkins · Kubernetes
              Prometheus · Grafana · Trivy

Data          Pandas · NumPy · Matplotlib · Streamlit · SQL · ChromaDB · AstraDB

Systems       Linux · Git · C# .NET · SQL Server · LaTeX
```

---

## GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=codeWithOwaisAhmad&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=codeWithOwaisAhmad&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

<div align="center">

*BS Computer Science · Islamia University of Bahawalpur · 2023 – 2027*

</div>
