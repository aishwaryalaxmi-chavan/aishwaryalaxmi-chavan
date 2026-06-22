# 👋 Hi, I'm Aishwaryalaxmi Chavan
## About

I am currently pursuing a Master of Science in Data Science, Analytics, and Engineering at Arizona State University, with a 3.81/4.00 GPA. My interests lie in **machine learning, retrieval and ranking, LLM applications, and scalable data systems**. I like building practical AI solutions that balance **performance, efficiency, and reliability.**

Previously, I worked as a Data Scientist at Bharat Soft Solutions, where I worked on healthcare machine learning pipelines by preparing clinical data, building preprocessing and modeling workflows, and improving model generalization through feature selection and cross-validation.

My projects reflect my interest in combining ML with engineering. I have built **hybrid retrieval pipelines with BM25, embeddings, and cross-encoders, semantic recommendation systems**, and **real-time graph data pipelines** using tools like **Python, Kafka, Docker, Kubernetes, and Neo4j**. Recently, I built a retrieval and ranking system that achieved a **56% latency reduction** while maintaining **99% recall**.

📍 **Location:** Tempe, Arizona, USA  
📧 **Email:** [ahchava1@asu.edu](mailto:ahchava1@asu.edu)  
🔗 **LinkedIn:** [linkedin.com/in/aishwaryalaxmi-chavan](https://www.linkedin.com/in/aishwaryalaxmi-chavan)  
💻 **GitHub:** [github.com/aishwaryalaxmi-chavan](https://github.com/aishwaryalaxmi-chavan)

---
## Education

### Arizona State University  
**M.S. in Data Science, Analytics, and Engineering**  
**August 2024 – May 2026** | GPA: **3.83/4.00**

### University of Pune  
**Bachelor’s in Engineering**  
Graduated **May 2022** | **8.14/10.00**

---

## Featured Projects

### 1. LLM-Assisted OFAC Sanctions Screening (SentinelRAG)

**Tech Stack:** Python, Sentence-Transformers, ChromaDB, Cross-Encoder

Built an OFAC SDN sanctions screening pipeline using **BM25 + embeddings + cross-encoder** retrieval, with **0 PII sent to external APIs**. The system supports fuzzy matching across names, aliases, and IDs. I also designed a deterministic decision layer for auditable **MATCH / NO MATCH** outcomes after identifying hallucination risk in LLM-driven decisions. Latency was reduced by **56%** while maintaining **99% recall** and **1.00 precision** on the evaluation set.

**Links:** [GitHub Repo](https://github.com/aishwaryalaxmi-chavan/sanctions-rag-screening)

---

### 2. AI Semantic Book Recommendation System

**Tech Stack:** Python, Hugging Face Transformers, LangChain, ChromaDB, Gradio, Pandas

Built a semantic recommendation system that matches user intent using transformer embeddings, sentiment, category signals, and vector similarity search in ChromaDB. Implemented a retrieval and ranking pipeline and exposed it through a Gradio dashboard for real-time recommendations. Benchmarked semantic retrieval against keyword search on **7k+ book descriptions** and showed improved recommendation relevance.

**Links:** [GitHub Repo](https://github.com/aishwaryalaxmi-chavan/semantic-book-recommender)

---

### 3. Real-Time Graph Data Processing Pipeline

**Tech Stack:** Python, Kafka, Neo4j GDS, Kubernetes, Docker, Helm

Built a near real-time graph data pipeline using Kafka and the Neo4j Sink Connector, deployed on Kubernetes with Helm. Ran graph analytics using PageRank and BFS for large-scale graph analysis. Also built containerized microservices and deployment workflows to demonstrate scalable, fault-tolerant distributed systems.

**Links:** [GitHub Repo](https://github.com/aishwaryalaxmi-chavan/Scalable-Graph-Based-Data-Processing-Pipeline)

---
## Skills

### Programming
Python, SQL, Bash/Shell, Java

### ML / AI
scikit-learn, PyTorch, TensorFlow, NLP, embeddings, feature engineering, model evaluation, cross-validation

### LLM / RAG
Hugging Face Transformers, LangChain, ChromaDB, vector search, retrieval and ranking

### Data / Infrastructure
Spark, Kafka, Docker, Kubernetes, AWS, Linux, Git, Tableau

---

## Experience

### Bharat Soft Solutions — Data Scientist  
**Pune, India | March 2023 – May 2024**

- Built reusable ML training pipelines in Python, pandas, scikit-learn, and SQL for healthcare prediction and classification use cases, covering preprocessing, feature engineering, model training, validation, and evaluation.
- Engineered patient-level features from demographics, diagnosis history, lab results, prior admissions, and healthcare utilization patterns to improve model input quality for risk prediction and cohort segmentation.
- Trained and evaluated multiple classification models, including tree-based and gradient boosting models, for healthcare risk prediction, improving generalization through cross-validation, feature selection, and hyperparameter tuning.
- Built Tableau dashboards to present model outputs, chronic disease trends, patient risk groups, and preventive care KPIs, helping stakeholders track healthcare outcomes and data-driven insights.

---

## 💬 Let's Connect

I’m interested in machine learning engineering roles and projects involving retrieval systems, ranking, LLM applications, and data infrastructure.

Feel free to reach out if you'd like to collaborate, discuss opportunities, or connect.
