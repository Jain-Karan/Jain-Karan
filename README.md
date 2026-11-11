
<!--
## Hi there 👋

**Jain-Karan/Jain-Karan** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# 👋 Hey there, I’m **Karan Jain**  
### AI Data Engineer • ML Practitioner • Backend Dev • Cloud & DevOps Explorer  
Sunnyvale, CA · [Mail](mailto:karan.jain@sjsu.edu) · [LinkedIn](https://www.linkedin.com/in/Ja1nKaran) · [GitHub](https://github.com/Jain-Karan) · [Resume](https://github.com/Jain-Karan/Jain-Karan/releases/latest/download/resume.pdf)

---

##  About Me

I’m a **AI Data Engineer and Machine Learning enthusiast** currently pursuing my **MS in Computer Science at San José State University**. Before grad school, I worked as a Senior Consultant at Ernst & Young LLP - building large‑scale data systems, automating enterprise workflows, and helping teams make better decisions with real‑time analytics.

I love working at the intersection of **big data, ML systems, backend engineering, and cloud infrastructure** — basically anywhere I can build something scalable, intelligent, and a little bit fun.

When I’m not coding, you’ll probably find me rock climbing, hiking or travelling.

---

##  Experience Highlights

### **Senior Technology Consultant — Ernst & Young (2018–2024)**
- Built **scalable ETL pipelines** with Airflow, Spark, and Kafka → cut manual processing by **80%**  
- Automated data quality monitoring with Prometheus & Kibana → reduced discrepancies by **35%**  
- Optimized big‑data workflows → **40% faster queries**, **20% lower infra cost**, **99.9% accuracy**  
- Created ML‑ready datasets → **50% faster training**, **15% better predictive accuracy**  
- Automated enterprise processes across multiple industries using C#, .NET, UiPath and Azure DevOps→ saved **4000+ hours**  
- Built real‑time analytics dashboards → improved decision‑making speed by **40%**

### **Instructional Student Assistant — SJSU (2025–present)**
Supporting the [redacted] course under Prof. [redacted].

##  Technical Toolkit

### **Data Engineering**
Hadoop · Spark · Kafka · Hive · HBase · Cassandra · MongoDB

### **Machine Learning**
PyTorch · sklearn · MLflow · RL · RecSys · Fine‑tuning · LoRA‑PEFT

### **Backend Engineering**
C# · .NET · Python · Rust · Node.js · Postgres · Redis · VB/VBA

### **Frontend**
React · Svelte · Razor · HTML/CSS · JavaScript · TypeScript · jQuery

### **DevOps & Cloud**
Azure · AWS · Kubernetes · Docker · Airflow · Prometheus

---

##  Projects

Each repo below has a seeded benchmark you can rerun, CI that gates on it, and a "how it got
here" log: the problems the benchmark surfaced, each fixed in its own pull request with a
regression test. The data is synthetic, and each README says what the numbers do and don't show.

###  [**EnterpriseRAGPlatform**](https://github.com/Jain-Karan/enterprise-rag-platform): multi-tenant retrieval
RAG service over **SharePoint, Confluence and S3**, with layout-aware chunking, hybrid **BM25 + vector** retrieval, reranking, per-tenant isolation, and generation through **LangChain** (Claude, Azure AI Foundry). Adding a source to a tenant is a YAML change, and `ragp onboard` benchmarks the tenant on day one.
- Layout-aware chunks kept the document's identity with **98.7%** of retrieved answers, versus **49.4%** for fixed windows
- Five ranking bugs found through benchmark misses ([issues](https://github.com/Jain-Karan/enterprise-rag-platform/issues?q=is%3Aissue)) took recall@5 from **88.4% to 98.7%** and MRR from **0.866 to 0.946**

###  [**AgenticWorkflowEngine**](https://github.com/Jain-Karan/agentic-workflow-engine): claims intake with a human in the loop
**LangGraph** agent that classifies, enriches and routes insurance claims through **MCP** tool servers for ERP and ticketing systems. It uses backoff, idempotency keys on every write, and an `interrupt()` approval gate on payouts over $1,000.
- 2,000-ticket backlog under injected API faults (429s, 503s, timeouts after commit): **0 duplicate payments**, **0 failed tickets**, **76.9%** handled with no human touch
- Found that retries were writing audit notes twice (**46 → 0**), made the fault benchmark reproducible, and calibrated classifier confidence so correct tickets stop bouncing to humans (**21.1% → 15.3%**), with confident-but-wrong held at 0

###  **Optimizing Recommender Systems with Reinforcement Learning**
A real‑time RL‑powered recommender system built with **Recogym, TensorFlow, Kafka, Airflow, Cassandra, Redis, and Postgres**.  
Achieved a **30% boost in click‑through rate**.

###  **Domain Transfer of Styles using CycleGAN**
Used **CycleGAN + composite CNNs** to transfer styles across domains, achieving **up to 95% accuracy**.  
Built with **PyTorch, NumPy, Matplotlib**.


---

## Education

**San José State University** — MS Computer Science (2024–2026)  
**Vellore Institute of Technology** — B.Tech Computer Science (2014–2018)

---

## What I’m Exploring Now
- Reinforcement learning for large‑scale personalization  
- Distributed ML systems  
- Rust for backend and systems programming  
- Smarter, more resilient data pipelines

---

## Let’s Connect

If you’re into data engineering, ML systems, distributed computing - feel free to reach out. Always happy to collaborate, learn, and build cool things.

