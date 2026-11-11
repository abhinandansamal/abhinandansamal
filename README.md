
# Hi there, I'm Abhinandan Samal! 👋

### 🚀 AI Engineer | Agentic AI | Generative AI | Data Engineering
📍 Berlin, Germany 🇩🇪

I am an **AI and Data Engineering professional with 6+ years of IT experience across IBM and TCS**, combining a strong foundation in distributed data systems with hands-on experience in Machine Learning, Large Language Models, Generative AI, and Agentic AI.

I hold an **M.Sc. in Data Science from IU International University of Applied Sciences, Germany**, where my research focused on enhancing contextual understanding in low-resource languages using multilingual transformers.

My interests lie in engineering reliable, scalable, and explainable AI applications — from multi-agent systems and enterprise RAG architectures to parameter-efficient fine-tuning of multilingual LLMs.

Currently exploring and building solutions around **Agentic AI, Multi-Agent Systems, LLM Applications, RAG, and Enterprise AI Engineering.**

---

## 🛠️ Technical Skills & Technology Stack

| Domain | Technologies & Frameworks |
|---|---|
| **Programming** | Python, SQL, JavaScript |
| **Generative AI & LLMs** | OpenAI API, Gemini API, Claude API, NVIDIA Nemotron, Hugging Face Transformers |
| **Agentic AI** | LangGraph, LangChain, CrewAI, Multi-Agent Systems, Agent Orchestration, Tool Calling, Function Calling |
| **RAG & Knowledge Systems** | Retrieval-Augmented Generation (RAG), ChromaDB, Pinecone, Vector Search, Embeddings, Semantic Search |
| **LLM Fine-Tuning** | PyTorch, PEFT, LoRA, QLoRA, Full Fine-Tuning, NLLB-200, Optuna |
| **Machine Learning** | Scikit-learn, XGBoost, LightGBM, Classification, Regression, Ensemble Learning |
| **Data Engineering** | Azure Databricks, Apache Kafka, KSQL, KStream, Confluent Cloud, PySpark, Hadoop, HDFS, Hive, HBase |
| **Databases** | PostgreSQL, MySQL, SQLite, SQL/NoSQL, Redshift |
| **Cloud & Infrastructure** | Microsoft Azure, AWS, Azure DevOps, Terraform, Docker, Kubernetes |
| **Backend Development** | FastAPI, Flask, REST APIs, SQLAlchemy |
| **MLOps & Development Tools** | MLflow, Git, GitHub Actions, pytest, Ruff, mypy |
| **Data Analytics & Visualization** | Tableau, Pandas, NumPy |

---

## 🌟 Featured Projects

### 🧠 1. Supplier Risk Investigator – Explainable Multi-Agent AI System

🔗 [GitHub Repository](https://github.com/abhinandansamal/supplier-risk) | 🎬 [Project Demo](https://youtu.be/zaI_SsUVR88)

An explainable multi-agent AI application developed during **Open Agent Hackathon 2026**, organized by GenAI.Works.

The system helps enterprise procurement teams investigate supplier risks through collaborative AI agents, enterprise data integration, evidence-grounded reasoning, and human-in-the-loop decision-making.

**Key Highlights:**
- Designed a multi-agent architecture using LangGraph for planning, research, evaluation, recommendations, and report generation.
- Integrated NVIDIA Nemotron models through Meterless Nightshift.
- Connected enterprise data sources using Zetaris Data Harness.
- Implemented deterministic Python-based supplier risk scoring.
- Developed evidence-grounded AI responses with independent Python-based numerical verification.
- Implemented RBAC, prompt-injection handling, and human-in-the-loop approval workflows.
- Built a FastAPI backend with real-time agent execution monitoring using Server-Sent Events.

**Tech:** Python, LangGraph, NVIDIA Nemotron, Zetaris Data Harness, FastAPI, SQLite, Docker, JavaScript, Claude Code.

🏅 Earned the **Zetaris × SpaceXSI AI Data Harness Solution Developer** verified credential.

---

### 🌍 2. Odia–German Bidirectional Neural Machine Translation

🔗 [GitHub Repository](https://github.com/abhinandansamal/odia-german-bidirectional-neural-machine-translation)

My Master's research project focused on enabling digital documentation of the low-resource Odia language through efficient bidirectional Odia–German Neural Machine Translation.

Extended my Master's thesis into **two peer-reviewed conference papers**, accepted at **AI4CHIEF 2026** and **ICICoS 2026**, in collaboration with Prof. Tianxiang Lu.

**Research Contributions & Key Highlights:**

- Developed a bidirectional Odia–German Neural Machine Translation system using Facebook's NLLB-200 Distilled 600M multilingual Transformer.
- Investigated Parameter-Efficient Fine-Tuning (PEFT/QLoRA) against conventional Full Fine-Tuning (FFT), demonstrating improved translation quality with significantly fewer trainable parameters.
- Built a parallel corpus using 298 authentic Odia newspaper articles from Dharitri and Sambad, comprising 3,676 unique parallel sentence pairs.
- Conducted systematic QLoRA ablation experiments across learning rate, LoRA rank, and dropout using Bayesian Hyperparameter Optimization (Optuna/TPE).
- Enhanced the experimental methodology with COMET-based semantic evaluation, paired bootstrap significance testing (10,000 resampling iterations), and a reproducible four-metric evaluation framework (BLEU, chrF++, TER, COMET).
- Benchmarked the fine-tuned multilingual NLLB model against GPT-5, Gemini 2.5 Pro, and Claude Sonnet 4.5 under zero-shot prompting, demonstrating superior lexical translation quality for low-resource German → Odia translation.
- Reduced trainable parameters to **10.11%** and model checkpoint storage requirements by **87.43%** compared with Full Fine-Tuning, while achieving only **2.8% training variance** across experimental runs.

**Translation Results (BLEU):**

| Translation Direction | Baseline | LoRA |
|---|---:|---:|
| Odia → German | 22.04 | 29.69 |
| German → Odia | 9.35 | 17.30 |

**Research Publications:**

📄 **AI4CHIEF 2026 – AI for Language Preservation**

*Enabling Digital Documentation of Odia through Efficient Bidirectional Odia–German Machine Translation.*

📄 **ICICoS 2026**

*Parameter-Efficient Adaptation for Low-Resource Machine Translation: An Ablation Study and Benchmark Against Large Language Models.*

**Tech:** Python, PyTorch, Hugging Face Transformers, NLLB-200, PEFT, QLoRA, Optuna, Bayesian Optimization, COMET, BLEU, chrF++, TER, Statistical Significance Testing.

---


### 🌐 3. Multi-Agent Supply Chain Resilience System – Sentinell.ai

🔗 [GitHub Repository](https://github.com/abhinandansamal/Multi-Agent-Supply-Chain-Resilience-System)

An autonomous multi-agent AI system designed to improve supply chain resilience by detecting global disruptions, analysing their impact on internal inventory, and coordinating potential recovery strategies.

The system explores how collaborative AI agents can automate the supply chain OODA loop (Observe, Orient, Decide, Act), helping procurement teams respond to disruptions more efficiently.

**Key Highlights:**

- Designed a microservices-based multi-agent architecture using Google Agent Development Kit (ADK) and Google Vertex AI.
- Implemented a Supervisor Agent coordinating specialized Watchtower and Procurement agents.
- Developed iterative ReAct-based investigation workflows for monitoring and analysing supply chain disruptions.
- Integrated the Model Context Protocol (MCP) for controlled access to internal inventory data.
- Implemented Agent-to-Agent (A2A) communication for interaction and negotiation with external supplier agents.
- Incorporated long-term supplier reliability memory to support future procurement decisions.
- Designed human-in-the-loop approval gates for high-value transactions exceeding predefined financial thresholds.
- Integrated OpenTelemetry for agent execution observability and Terraform-based infrastructure provisioning.
- Developed a cloud-oriented deployment architecture using Google Cloud Run and GitHub Actions CI/CD.

**Tech:** Python, Google ADK, Google Vertex AI, Gemini 2.5 Flash-Lite, FastAPI, Next.js, TypeScript, Tailwind CSS, CopilotKit, MCP, A2A Protocol, SQLite, Docker, Terraform, Google Cloud Run, OpenTelemetry.

---

### 🏙️ 4. Montgomery City Planner – AI-Powered Geospatial Urban Intelligence

🔗 [GitHub Repository](https://github.com/abhinandansamal/montgomery-city-planner)

An AI-powered geospatial intelligence platform designed for urban planning and municipal decision-making in Montgomery, Alabama.

The application combines Agentic AI, geospatial analytics, Retrieval-Augmented Generation (RAG), and real-time web intelligence to help city planners explore urban development opportunities, identify potential business gaps, and analyse zoning policies through natural-language interactions.

**Key Highlights:**

- Developed stateful AI agent workflows using LangGraph with sequential LLM fallback across Groq (Llama 3), OpenAI (GPT-4o), and Anthropic (Claude 3.5 Sonnet).
- Integrated Montgomery's ArcGIS Open Data REST API for geospatial analysis of property parcels, valuations, and zoning information.
- Implemented a Ghost Business Detection workflow to identify registered businesses with limited or missing online presence.
- Developed retail gap and market demand analysis to identify potential commercial opportunities and underserved neighbourhoods.
- Built a policy intelligence RAG pipeline using ChromaDB and Sentence Transformers to retrieve information from zoning ordinances and comprehensive planning documents.
- Integrated Bright Data SERP scraping for external business verification and web intelligence.
- Implemented geospatial visualizations, walkability analysis, isochrone polygons, and neighbourhood-level planning simulations.
- Developed an MCP-based tool server using FastMCP to expose city intelligence capabilities to AI workflows.

**Tech:** Python, LangGraph, Google/Groq/OpenAI/Anthropic LLM APIs, Streamlit, Folium, Streamlit-Folium, ArcGIS REST API, Bright Data, ChromaDB, Sentence Transformers, FastMCP, Geospatial Analytics, RAG.

---

### 📊 5. BigMart Sales Prediction

🔗 [GitHub Repository](https://github.com/abhinandansamal/BigMart_Sales_Prediction)

An end-to-end Machine Learning project focused on predicting retail sales using historical transactional and product information.

**Key Highlights:**
- Data preprocessing and exploratory data analysis.
- Feature engineering and model development.
- Regression and ensemble learning techniques.
- Model evaluation and performance comparison.

**Tech:** Python, Pandas, NumPy, Scikit-learn, SQL, Machine Learning.

---

## 💼 Professional Experience

### IBM – Cloud Data Engineer
**India**

- Worked on cloud-based data engineering solutions and distributed data processing.
- Developed and maintained real-time data pipelines using Apache Kafka and related streaming technologies.
- Worked with KSQL, KStream, Confluent Cloud, PySpark, Terraform, and Azure DevOps.
- Contributed to improving Kafka deserialization error processing, reducing processing time by approximately 30%.

### Tata Consultancy Services (TCS) – Data & Analytics Engineering
**India**

- Worked across Data Engineering, Data Science, Data Analytics, and Business Intelligence initiatives.
- Developed data processing and analytics solutions using Python, SQL, and distributed data technologies.
- Contributed to Machine Learning initiatives, including predictive modelling and recommendation systems.
- Worked with cloud, data integration, and analytics technologies.

**Overall Industry Experience:** 6+ years across IT, Data Engineering, Data Science, and Analytics.

---

## 🎓 Education & Research

**M.Sc. Data Science**  
IU International University of Applied Sciences, Germany  
2023 – 2025

**Master's Thesis:**  
*Enhancing Contextual Understanding in Low-Resource Languages Using Multilingual Transformers.*

Research focus:
- Low-resource Neural Machine Translation.
- Multilingual Transformer architectures.
- Parameter-Efficient Fine-Tuning (PEFT).
- LoRA vs. Full Fine-Tuning.
- Bayesian Hyperparameter Optimization.
- Machine Translation Evaluation.

**Research Interests:**
- Agentic AI and Multi-Agent Systems.
- Low-Resource Language Technologies.
- Large Language Model Adaptation.
- Explainable and Reliable AI.
- Enterprise AI Applications.

---

## 🏆 Hackathons & Credentials

**Open Agent Hackathon 2026 – GenAI.Works**

Participated in the international hackathon and developed Supplier Risk Investigator, an explainable multi-agent AI application.

**Zetaris × SpaceXSI AI Data Harness Solution Developer**

Verified credential awarded by Zetaris following participation in Open Agent Hackathon 2026.

- [Verify GenAI.Works Hackathon Certificate](https://hackathon.genai.works/verify/CERT-2026-ZFNQM)
- [Verify Zetaris Credential](https://www.zetaris.com/credentials/ztr-dhsd-3wy9b9)

---


## 📊 GitHub Statistics

![GitHub Stats](https://github-stats-extended.vercel.app/api?username=abhinandansamal&show_icons=true&theme=tokyonight&hide_border=true)

![Top Languages](https://github-stats-extended.vercel.app/api/top-langs/?username=abhinandansamal&layout=compact&theme=tokyonight&hide_border=true)

---

## 📫 Let's Connect!

I'm always interested in connecting with AI Engineers, Data Engineers, researchers, and technology professionals working on innovative AI solutions.

- 💼 **LinkedIn:** [Abhinandan Samal](https://www.linkedin.com/in/abhinandan-samal/)
- 💻 **GitHub:** [abhinandansamal](https://github.com/abhinandansamal)
- 🤗 **Hugging Face:** [abhinandansamal](https://huggingface.co/abhinandansamal)
- 📊 **Kaggle:** [samalabhinandan](https://www.kaggle.com/samalabhinandan)
- 📧 **Email:** [abhinandan198@gmail.com](mailto:abhinandan198@gmail.com)

---

⭐ *Building intelligent systems at the intersection of Data Engineering, Machine Learning, and Agentic AI.*

