# 👋 Hi, I'm Nilesh Ganguly

🚀 AI Engineer focused on **Agentic AI Systems, LLM Engineering, and Production AI Infrastructure**.

I design and build **intelligent AI systems that combine large language models, autonomous agents, and scalable backend architectures**. My work focuses on transforming **advanced AI capabilities into reliable real-world systems**.

Currently, I am strengthening my expertise in **deploying and scaling production-level Agentic AI systems**, improving **workflow orchestration, AI pipelines, and agent reliability** in real-world environments.

---

# 🌐 Connect With Me

📧 **Email**
[ng.ai.professional@gmail.com](mailto:ng.ai.professional@gmail.com)

💼 **LinkedIn**
[linkedin.com/in/profile-nilesh-ganguly](https://www.linkedin.com/in/profile-nilesh-ganguly)

💻 **GitHub**
[github.com/BlueGod01](https://github.com/BlueGod01)

---

# 🧠 Core Focus Areas

* 🤖 Agentic AI Systems
* 🔎 Retrieval-Augmented Generation (RAG)
* ⚙️ LLM System Architecture
* 📦 Production AI Pipelines
* 🔄 Workflow Orchestration
* 📊 AI Observability & Evaluation
* ☁️ Cloud-native AI Deployments

---

# 🛠️ Technical Skills

## Programming Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Java](https://img.shields.io/badge/Java-red?style=for-the-badge\&logo=openjdk\&logoColor=white)

---

## Machine Learning Libraries

![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-orange?style=for-the-badge\&logo=scikit-learn)
![XGBoost](https://img.shields.io/badge/XGBoost-darkgreen?style=for-the-badge)

---

## Deep Learning

![TensorFlow](https://img.shields.io/badge/TensorFlow-orange?style=for-the-badge\&logo=tensorflow)
![PyTorch](https://img.shields.io/badge/PyTorch-red?style=for-the-badge\&logo=pytorch)
![Hyperopt](https://img.shields.io/badge/Hyperopt-blue?style=for-the-badge)

---

## Generative AI & Agent Frameworks

![LangChain](https://img.shields.io/badge/LangChain-black?style=for-the-badge)
![LangGraph](https://img.shields.io/badge/LangGraph-blue?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-Architecture-purple?style=for-the-badge)
![Agentic AI](https://img.shields.io/badge/Agentic_AI-Systems-darkblue?style=for-the-badge)
![MCP](https://img.shields.io/badge/MCP-Model_Context_Protocol-gray?style=for-the-badge)

---

## Backend & APIs

![FastAPI](https://img.shields.io/badge/FastAPI-teal?style=for-the-badge\&logo=fastapi)
![Flask](https://img.shields.io/badge/Flask-black?style=for-the-badge\&logo=flask)

---

## Evaluation & Observability

![LangSmith](https://img.shields.io/badge/LangSmith-green?style=for-the-badge)
![Langfuse](https://img.shields.io/badge/Langfuse-purple?style=for-the-badge)
![Opik](https://img.shields.io/badge/Opik-gray?style=for-the-badge)
![RAGAS](https://img.shields.io/badge/RAGAS-RAG_Evaluation-blue?style=for-the-badge)
![MLflow](https://img.shields.io/badge/MLflow-blue?style=for-the-badge\&logo=mlflow)

---

## DevOps & Infrastructure

![Docker](https://img.shields.io/badge/Docker-blue?style=for-the-badge\&logo=docker)
![Git](https://img.shields.io/badge/Git-orange?style=for-the-badge\&logo=git)
![GitHub](https://img.shields.io/badge/GitHub-black?style=for-the-badge\&logo=github)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-blue?style=for-the-badge\&logo=githubactions)
![DVC](https://img.shields.io/badge/DVC-Data_Version_Control-purple?style=for-the-badge)

---

## Monitoring & Visualization

![Grafana](https://img.shields.io/badge/Grafana-orange?style=for-the-badge\&logo=grafana)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-purple?style=for-the-badge)

---

## Cloud Platforms

![AWS](https://img.shields.io/badge/AWS-black?style=for-the-badge\&logo=amazonaws)
![Microsoft Azure](https://img.shields.io/badge/Azure-blue?style=for-the-badge\&logo=microsoftazure)

---

# 🚀 Featured Projects

---

# 🎥 Brand Guardian AI – Video Content Compliance Auditor

### Agentic AI Pipeline for Automated Video Compliance Monitoring

🔗 **Project Repository**
https://github.com/BlueGod01/AI-YT_Video-Content-Compliance-Auditing-Pipeline.git

### Technologies

Python • FastAPI • LangChain • LangGraph • Azure OpenAI • Azure AI Search • PostgreSQL • Redis • Streamlit • Azure Video Indexer • Docker • Azure Cloud • OpenTelemetry • LangSmith

### Overview

Developed an **AI-powered automated video compliance auditing system** that analyzes video content against regulatory guidelines such as **FTC regulations and advertising platform policies**, generating structured compliance reports.

The system uses a **multi-stage ETL and reasoning pipeline orchestrated using LangGraph DAG**, enabling automated:

* Video ingestion
* Speech transcription
* OCR metadata extraction
* Regulatory policy retrieval
* Compliance violation detection

YouTube videos are processed using **Azure Video Indexer** to extract speech-to-text transcripts and visual metadata. Regulatory policies are retrieved from a **vectorized knowledge base in Azure AI Search**.

Using **Azure OpenAI models**, the system performs contextual reasoning on transcripts to detect misleading claims, absolute guarantees, and other compliance violations categorized by severity.

The backend was built using **FastAPI**, while **PostgreSQL and Redis** handle structured data and caching. **LangSmith and Azure Application Insights (OpenTelemetry)** provide workflow tracing and observability. The system is **Dockerized and deployed on Azure cloud infrastructure** for scalable production deployment.

---

# 🔬 Agentic RAG Research Assistant

### Multi-Agent Research Automation System

🔗 **Project Repository**
https://github.com/BlueGod01/Agentic-AI-Research-Assistant.git

### Technologies

Python • FastAPI • LangChain • LangGraph • OpenAI APIs • Pinecone • AWS S3 • Streamlit • Unstructured • ReportLab • Docker

### Overview

Developed an **Agentic Retrieval-Augmented Generation (RAG) research assistant** that allows users to upload documents and interact with them through **intelligent query-driven reasoning**.

The system processes **PDF and TXT documents** using **Unstructured** for parsing and chunking. Embeddings are generated using **OpenAI models** and stored in **Pinecone**, while raw documents are stored in **AWS S3** for scalable storage.

The system implements a **multi-agent architecture orchestrated using LangGraph**:

**Research Agent**

* Uses **ReAct-based reasoning**
* Performs vector search in Pinecone
* Retrieves external information via DuckDuckGo search

**Orchestrator Agent**

* Aggregates reasoning outputs
* Generates final responses

Responses can be delivered as:

* Interactive conversational answers
* Structured **PDF research notes generated using ReportLab**

The backend is implemented using **FastAPI**, while **Streamlit** provides the user interface. The system architecture follows modular design principles for storage integration, tool execution, and logging.

This solution significantly **reduces the manual effort required for research**, enabling users to extract insights from both uploaded documents and external knowledge sources efficiently.

---

# 🎯 Professional Interests

I am particularly interested in working on:

* Agentic AI Systems
* LLM Engineering
* Autonomous AI Workflows
* Retrieval-Augmented Systems
* AI Infrastructure & LLMOps
* Production AI Platforms

I enjoy solving problems that combine **machine learning, system architecture, and scalable backend engineering.**

---

⭐ Open to collaboration on **Agentic AI systems, LLM infrastructure, and intelligent automation platforms.**
