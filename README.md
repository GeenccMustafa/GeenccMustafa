# Hi, I'm Mustafa Genc 👋

### AI Engineer · LLM Agent Systems · RAG & Evaluation

<p align="left">
  <a href="https://geenccmustafa.github.io/"><img src="https://img.shields.io/badge/Portfolio-1C2D3E?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/mustafageencc/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://medium.com/@mustafa.gencc94"><img src="https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white" alt="Medium"></a>
  <a href="https://www.youtube.com/@mustafagenc-2025"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube"></a>
  <a href="mailto:mustafa.gencc94@gmail.com"><img src="https://img.shields.io/badge/Email-2A9DC8?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

I build **production LLM agent systems**: multi-step agents with tool use, memory and reasoning, backed by retrieval pipelines and measured with proper evaluation.

As a **Machine Learning Engineer**, I take agents and **agentic workflows from prototype to production**. I design and ship multi-agent systems, containerise them as scalable services, and run them in production with CI/CD, monitoring and evaluation built in.

A big part of my work is **document intelligence**: end-to-end pipelines that turn unstructured documents into structured, queryable knowledge. These pipelines cover OCR, layout analysis, semantic chunking, LLM-based extraction and retrieval. I work with both open-weight and proprietary LLMs, choosing and tuning models for accuracy, latency and cost.

📍 Augsburg, Germany · 🎓 M.Sc. @ Technical University of Munich (NLP & Data Science)

---

### 🤖 What I work on

- **Agent architecture & orchestration:** multi-step LLM agents, tool calling, memory, query-to-agent routing, stateful agentic workflows
- **Agent-ready retrieval:** production RAG (OCR → layout analysis → semantic chunking → hybrid search → reranking), GraphRAG; **+20% F1** in extraction accuracy through eval-driven optimisation
- **Evaluation first:** Ragas, DeepEval and ChainForge benchmarks, A/B testing, guardrails, and cost/latency trade-offs
- **Prototype → production:** containerised AI services (Docker, FastAPI), CI/CD, MLflow, local and cloud LLM APIs
- **Fine-tuning:** PEFT / QLoRA with TRL for domain-specific document intelligence, benchmarked against proprietary APIs

---

### 🚀 Featured projects

| Project | What it does |
|---|---|
| [**agent-router**](https://github.com/GeenccMustafa/agent-router) | Query-to-agent routing service with an evaluation pipeline |
| [**graph-versus-vector**](https://github.com/GeenccMustafa/graph-versus-vector) | GraphRAG (Neo4j knowledge graph) vs. vector RAG on multi-hop QA |
| [**llm-cache-lab**](https://github.com/GeenccMustafa/llm-cache-lab) | Measures prompt/KV caching: cost, TTFT latency and memory, with cold-vs-warm experiments on local Ollama |
| [**llm-guardrails-benchmark**](https://github.com/GeenccMustafa/llm-guardrails-benchmark) | Benchmarks NeMo Guardrails, Guardrails AI and LlamaGuard on safety, compliance and format adherence |
| [**literary-graphrag-ollama**](https://github.com/GeenccMustafa/literary-graphrag-ollama) | Local GraphRAG with Ollama; no data leaves the host |
| [**bundestag-lakehouse**](https://github.com/GeenccMustafa/bundestag-lakehouse) | Bronze → Silver → Gold lakehouse on the Bundestag DIP API (dbt, DuckDB, Airflow, MinIO) |

---

### 🛠️ Tech stack

**Agents & LLMs**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white)
![Semantic Kernel](https://img.shields.io/badge/Semantic%20Kernel-5C2D91?style=flat-square&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic%20API-191919?style=flat-square&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini%20API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-30A2FF?style=flat-square&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)

**RAG & Vector Search**
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square&logoColor=white)
![Weaviate](https://img.shields.io/badge/Weaviate-00C29A?style=flat-square&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)

**Evaluation**
Ragas · DeepEval · ChainForge · SHAP · LIME

**Fine-Tuning & ML**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
TRL · PEFT / QLoRA · SentenceTransformers · DeepSpeed

**Document AI / OCR**
Mistral OCR · Docling · LayoutLMv3 · PaddleOCR · PyMuPDF · Textract

**MLOps & Infrastructure**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![DVC](https://img.shields.io/badge/DVC-13ADC7?style=flat-square&logo=dvc&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

---

### ✍️ Writing

I write practitioner-focused deep-dives on [Medium](https://medium.com/@mustafa.gencc94):

- **Transformers & LLMs**, a 13-part series on attention, training and internals
- *Ollama vs vLLM: A Comprehensive Guide to Local LLM Serving*
- *The Architecture of Deception: How RAG Systems Lie to You in Production*
- LLM agent architecture deep-dives, a GraphRAG implementation guide, and OCR benchmarks (Mistral OCR vs. Chandra OCR vs. GLM-OCR)

---

<p align="center"><i>Open to conversations about agent systems, RAG and LLM evaluation. Feel free to reach out.</i></p>
