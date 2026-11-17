<div align="center">

# Hi 👋, I'm Samir Boraste
### AI/ML Engineer | M.Tech in Artificial Intelligence @ Symbiosis Institute of Technology | Ex-Accenture

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Samir_Boraste-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/samir-boraste-a35431207)
[![Email](https://img.shields.io/badge/Email-sameerboraste84%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sameerboraste84@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-BorasteSamir-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/BorasteSamir)
[![Portfolio](https://img.shields.io/badge/Portfolio-Active_Projects-4CAF50?style=for-the-badge&logo=google-cloud&logoColor=white)](https://github.com/BorasteSamir?tab=repositories)

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=BorasteSamir&label=Profile%20Views&color=0e75b6&style=flat" alt="Visitor Count" />
  <img src="https://img.shields.io/badge/Location-Pune%20%7C%20Bengaluru%20%7C%20Remote-blue.svg" alt="Location" />
  <img src="https://img.shields.io/badge/Status-Open%20to%20AI%2FML%20Roles-success.svg" alt="Status" />
</p>

</div>

---

## 🚀 About Me

Applied **AI/ML Engineer** with **3.5 years** of combined engineering and machine learning experience (Associate Software Engineer at Accenture + M.Tech in Artificial Intelligence at Symbiosis Institute of Technology, CGPA 8.0).

- 🧠 **Machine Learning & Risk Modeling:** Engineered production credit risk pipelines evaluating ~297k loan applications using LightGBM, XGBoost, SMOTE class balancing, and SHAP explainability.
- 💬 **Generative AI & LLMs:** Built production-grade Multimodal RAG systems featuring 5-model parallel async ensembles (Groq LLaMA-3.3), token-aware semantic chunking, and zero-LLM heuristic hallucination filters.
- 👁️ **Computer Vision:** Trained and fine-tuned YOLOv8 architectures on the Indian Driving Dataset (IDD) for dynamic 4-signal corridor traffic optimization.
- ⚡ **Production Systems & MLOps:** Delivered sub-10ms inference REST APIs with FastAPI, real-time monitoring via Streamlit, Docker containerization, and Databricks cloud workflows.

---

## 🛠️ Technical Skills

| Domain | Technologies & Frameworks |
|---|---|
| **Core Languages** | `Python (3.8 - 3.11)`, `SQL (PostgreSQL, MySQL)`, `C++`, `Bash` |
| **Machine Learning & Deep Learning** | `PyTorch`, `TensorFlow`, `Scikit-Learn`, `XGBoost`, `LightGBM`, `OpenCV`, `YOLOv8`, `Keras` |
| **Generative AI & LLMs** | `LangChain`, `Llama-3.3`, `Groq API`, `ChromaDB`, `Hugging Face Transformers`, `BLIP`, `RAG Architectures` |
| **Data Processing & Analytics** | `Pandas`, `NumPy`, `SciPy`, `Matplotlib`, `Seaborn`, `SHAP`, `imbalanced-learn (SMOTE)` |
| **Backend & MLOps** | `FastAPI`, `Streamlit`, `Flask`, `Docker`, `Git`, `GitHub Actions`, `Linux/Unix` |
| **Cloud & Big Data** | `Databricks`, `Apache Spark`, `AWS (S3, EC2)`, `RESTful API Architecture` |

---

## 🌟 Featured Production Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>💳 <a href="https://github.com/BorasteSamir/BNPL-Buy-Now-Pay-Later-Risk-Scoring-System-using-Machine-learning">BNPL Risk Scoring & Default Prediction</a></h3>
      <p><em>Production credit risk assessment pipeline predicting probability of default (PD) for Buy Now Pay Later micro-loans.</em></p>
      <ul>
        <li><b>Dataset & Scale:</b> Evaluated ~297k filtered loan applications across 45+ financial features.</li>
        <li><b>Modeling:</b> <b>LightGBM (ROC-AUC 0.734)</b> vs <b>XGBoost (0.712)</b> with SMOTE addressing 8.6:1 class imbalance.</li>
        <li><b>Dual-Scoring Engine:</b> Blended PD with dynamic Cash-Flow Stability Index for thin-file applicants.</li>
        <li><b>MLOps & Monitoring:</b> Sub-10ms <b>FastAPI REST API</b>, SHAP TreeExplainer, PSI drift detector (threshold > 0.20), and Thompson Sampling Multi-Armed Bandit for dynamic cutoff ROI optimization.</li>
      </ul>
      <p><b>Stack:</b> <code>Python</code> · <code>LightGBM</code> · <code>XGBoost</code> · <code>SHAP</code> · <code>FastAPI</code> · <code>Streamlit</code></p>
    </td>
    <td width="50%" valign="top">
      <h3>🎓 <a href="https://github.com/BorasteSamir/ScholarMind---Smart-academic-assistant-with-Multimodal-RAG-Ensemble-">ScholarMind — Multimodal RAG Assistant</a></h3>
      <p><em>Production-grade Multimodal RAG system for research papers powered by a 5-model async LLM ensemble.</em></p>
      <ul>
        <li><b>Multimodal Ingestion:</b> Layout-aware text extraction (PyMuPDF), markdown tables, and BLIP image captioning for diagrams.</li>
        <li><b>5-Model Async Ensemble:</b> Parallel inference across Groq LLaMA models with dynamic context variations and composite scoring.</li>
        <li><b>Hallucination Guard:</b> Zero-LLM heuristic screening checking token overlap, numerical consistency, and entity integrity.</li>
        <li><b>Formula OCR:</b> Integrated pix2tex LaTeX OCR with symbol-by-symbol breakdown.</li>
      </ul>
      <p><b>Stack:</b> <code>PyTorch</code> · <code>ChromaDB</code> · <code>Groq LLaMA-3.3</code> · <code>BLIP</code> · <code>Streamlit</code> · <code>RAG</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🚦 <a href="https://github.com/BorasteSamir/AI-Powered-Adaptive-Traffic-Signal-Control-using-YOLOv8">Adaptive Traffic Signal Control (YOLOv8)</a></h3>
      <p><em>Real-time computer vision system dynamically adjusting traffic signal timings across 4-phase corridors.</em></p>
      <ul>
        <li><b>Object Detection:</b> Fine-tuned <b>YOLOv8</b> on the <b>Indian Driving Dataset (IDD)</b> to classify buses, trucks, cars, and autorickshaws.</li>
        <li><b>Dynamic Scheduling:</b> Weighted vehicle density dynamically calculates green phases (8s–120s).</li>
        <li><b>Safety & Coordination:</b> Implemented starvation prevention (max 60s wait), green wave progression offsets, and live multi-camera feeds.</li>
      </ul>
      <p><b>Stack:</b> <code>YOLOv8</code> · <code>OpenCV</code> · <code>PyTorch</code> · <code>Streamlit</code> · <code>Python</code></p>
    </td>
    <td width="50%" valign="top">
      <h3>📰 <a href="https://github.com/BorasteSamir/Fake-News-detection-using-NLP-techniques">Fake News Detection NLP Pipeline</a></h3>
      <p><em>End-to-end NLP classification system comparing classical machine learning and deep learning architectures.</em></p>
      <ul>
        <li><b>Feature Engineering:</b> Evaluated BoW, TF-IDF, and Word2Vec vectorization across 40k+ articles.</li>
        <li><b>Benchmark Results:</b> <b>SVM + TF-IDF (99.2% Accuracy, 99.2% F1)</b> outperformed BiLSTM (98.7%) and Random Forest (97.5%).</li>
        <li><b>Deployment:</b> Interactive Streamlit web dashboard providing real-time text credibility scoring and confidence analysis.</li>
      </ul>
      <p><b>Stack:</b> <code>Python</code> · <code>Scikit-Learn</code> · <code>BiLSTM</code> · <code>NLTK</code> · <code>Streamlit</code></p>
    </td>
  </tr>
</table>

---

## ⚡ Engineering & Pipeline Highlights

<div align="center">

| Dimension | Engineering Focus & Verified Impact |
|---|---|
| **Primary Focus** | Applied Artificial Intelligence, Production Machine Learning & MLOps Pipelines |
| **Core Architectures** | Multimodal RAG (5-Model Async Ensemble), Gradient Boosting (LightGBM / XGBoost), YOLOv8 (Computer Vision) |
| **API & Serving** | High-Throughput Sub-10ms REST Services via FastAPI, Asynchronous Ingestion, Interactive Streamlit UIs |
| **Explainability & Drift** | SHAP TreeExplainer, PSI Population Stability Monitoring (>0.20 alert), SMOTE (8.6:1 Class Imbalance) |
| **Decision Science** | Thompson Sampling Multi-Armed Bandit (MAB) for Dynamic Approval Cutoff Optimization |

</div>

---

## 🎓 Education & Certifications

- **M.Tech in Artificial Intelligence & Machine Learning** — Symbiosis Institute of Technology (2024–2026) | *CGPA: 8.0 / 10*
- **Bachelor of Engineering in Computer Science** — Savitribai Phule Pune University (2017–2021) | *First Class Distinction*
- 🏅 **Databricks Certified:** Generative AI Fundamentals
- 🏅 **DeepLearning.AI:** Machine Learning Specialization
- 🏅 **Associate Software Engineer:** Accenture (2022–2024)

---

## 📬 Let's Connect!

I am actively open to **AI/ML Engineer**, **Machine Learning Engineer**, **Generative AI Developer**, and **Data Scientist** roles (Full-time & High-impact Contracts, Remote / Hybrid / On-site in Pune, Bengaluru, Hyderabad, Mumbai).

- 💼 **LinkedIn:** [linkedin.com/in/samir-boraste-a35431207](https://www.linkedin.com/in/samir-boraste-a35431207)
- ✉️ **Email:** [sameerboraste84@gmail.com](mailto:sameerboraste84@gmail.com)
- 📍 **Location:** Pune, Maharashtra, India

---
<div align="center">
  <sub>Designed & Maintained by <a href="https://github.com/BorasteSamir">Samir Boraste</a> · Powered by Python & Open-Source AI</sub>
</div>
