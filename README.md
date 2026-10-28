<div align="center">

### Beyzanur Ulu

**AI / ML Engineer** · Istanbul, Türkiye

*Computer Engineering @ MEF University · Building production-grade AI systems*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/beyza-nur-ulu/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:beyzanurulu85@gmail.com)

</div>

---

I build **LLM applications, multi-agent systems and end-to-end ML pipelines**, and I care about the parts that make them trustworthy: guardrails, evaluation, observability and honest limitations. AI/ML Engineer at MindSane; building a multi-agent AI assistant as my graduation project.

---

### Featured

#### 🛩️ [SkyTrace](https://github.com/beyzanurulu/SkyTrace) · drone flight log analysis

[![Live demo](https://img.shields.io/badge/live_demo-skytrace--demo-2ea44f?style=flat-square)](https://skytrace-demo.onrender.com)
[![PyPI](https://img.shields.io/pypi/v/skytrace?style=flat-square)](https://pypi.org/project/skytrace/)
[![Sample reports](https://img.shields.io/badge/sample_reports-GitHub_Pages-24292f?style=flat-square)](https://beyzanurulu.github.io/SkyTrace/)

Analyzes PX4 (`.ulg`) and ArduPilot (`.bin`) logs: rule-based and anomaly detectors, an offline HTML report, a web UI and a **LangGraph Q&A agent whose every number is verified against tool outputs**, with RAG over the PX4/ArduPilot docs.

- Runs fully local (Ollama, local docs index) with an enforced **offline mode**, passing an end-to-end check in a container with `--network none`
- Evaluated on 35 labelled PX4 SITL flights: every injected GPS, battery and motor fault found; limitations documented
- `pip install skytrace` · Docker image on GHCR · CI, release and Pages workflows

`Python` `LangGraph` `LiteLLM` `Ollama` `FastAPI` `Docker` `GitHub Actions`

#### 🛠️ [multi-agent-it-support](https://github.com/beyzanurulu/multi-agent-it-support) · Turkish IT helpdesk agents

A multi-agent system that understands Turkish IT requests (intent + NER), plans, solves them from a knowledge base with sources, opens tickets **only after human approval**, and answers managers' questions with read-only NL→SQL.

- 5 agents in LangGraph: plan-and-execute supervisor, triage, solution, ticket (`interrupt()` approval), analytics
- Tools served over **FastMCP**; PostgreSQL + **pgvector** for tickets, KB, checkpoints and long-term memory
- Guardrails: prompt-injection filter, PII masking (Presidio), SQL guard, role-based tool allowlist, step/token limits
- 120-scenario eval gating CI · Prometheus + Grafana · k3s manifests and arm64 images

`LangGraph` `FastMCP` `FastAPI` `PostgreSQL` `pgvector` `ONNX Runtime` `Chainlit` `Kubernetes` `Grafana`

---

### More projects

| | |
|---|---|
| 💬 [DocuChat](https://github.com/beyzanurulu/DocuChat) | RAG-based document Q&A chatbot · layout-aware PDF ingestion pipeline |
| 🤖 [rag_chatbot](https://github.com/beyzanurulu/rag_chatbot) | Retrieval-Augmented Generation chatbot with vector store |
| 🧠 [Brain-Cancer-MRI-Classification-Clustering](https://github.com/beyzanurulu/Brain-Cancer-MRI-Classification-Clustering) | ML pipeline on 6,056 MRI images · XGBoost 91.67% acc · AUC 0.985 |
| 🎓 [EduLift](https://github.com/RahiqAlhuslan/EduLift) | **1st Place** · Horizon AI Hackathon 2025 · AI education assistant on Azure |
| 🌿 [yz_app_jam](https://github.com/Elcieren/yz_app_jam) | AI plant & mushroom identification app · Google App Jam |

---

**AI / ML** &nbsp;·&nbsp; LangGraph · LangChain · RAG · FastMCP · Vector DBs (pgvector, Pinecone) · Hugging Face · ONNX Runtime · scikit-learn · XGBoost · PyTorch · OpenCV

**Backend & Infra** &nbsp;·&nbsp; FastAPI · PostgreSQL · Docker · Kubernetes (k3s) · GitHub Actions · Prometheus · Grafana

**Cloud** &nbsp;·&nbsp; AWS Lambda · API Gateway · DynamoDB · EC2 · S3

**Languages** &nbsp;·&nbsp; Python · SQL · Java · React · Spring Boot · Flutter

---

<div align="center">
<sub>1st Place · University of Miami Horizon AI Hackathon 2025 &nbsp;·&nbsp; Top 10 · Google Ideathon 3.0 &nbsp;·&nbsp; 2 papers accepted at ASYU (IEEE)</sub>
</div>
