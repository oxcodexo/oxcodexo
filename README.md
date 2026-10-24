<div align="center">

# ⚡ Hicham Kraou (`oxcodexo`)
### **Full Stack & AI Developer | AI Agent Architect**
📍 *Rabat, Morocco* 🇲🇦

[![LinkedIn](https://img.shields.io/badge/LinkedIn-oxcodexo-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/oxcodexo)
[![GitHub](https://img.shields.io/badge/GitHub-oxcodexo-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/oxcodexo)
[![Email](https://img.shields.io/badge/Email-hichamkraou1%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hichamkraou1@gmail.com)
[![Live Demo](https://img.shields.io/badge/Live_Demo-Qrox_AI-00F2FE?style=for-the-badge&logo=vercel&logoColor=black)](https://qrox.vercel.app)

---

</div>

## 🚀 About Me

I am a **Full Stack & AI Developer** specializing in **AI Agent Architecture**, **Multi-Agent Autonomous Systems**, and **Production-Grade SaaS Platforms**. With a strong background in Mathematical Sciences and Software Engineering, I bridge the gap between frontier LLM research and robust, enterprise-ready software.

My core expertise centers around architecting self-hosted AI agent frameworks (**OpenClaw**), novel protocol patterns (such as **Semantic Tool Contracts** via **Model Context Protocol / MCP**), multi-model chat applications handling 500+ frontier models, and secure offline enterprise RAG pipelines.

---

## 🛠️ Core Expertise & Architectural Innovations

- 🤖 **AI Agent Systems & Multi-Agent Swarms**: Architecting multi-agent orchestration engines on OpenClaw, intent routing, tool-using autonomous agents, and zero-selector web scraping pipelines (Firecrawl API).
- 🧩 **Semantic Tool Contracts (MCP)**: Pioneered tool architecture patterns where MCP microservices return explicit semantic execution states (`NO_DATA_FOUND`, `SUCCESS_WITH_DATA`, `ERROR`) and active dialogue guidance.
- 🏗️ **Full-Stack SaaS Architecture**: Building high-throughput, multi-tenant applications with Next.js 16, React, Node.js, NestJS, TypeScript, PostgreSQL, and Prisma ORM.
- 📐 **Hybrid Text-to-SQL (LEGO Assembly)**: Engineered modular Text-to-SQL pipelines combining pre-verified schema joins with flexible LLM filter clauses to solve the reliability-flexibility paradox.
- 🛡️ **Enterprise Offline AI & Fine-Tuning**: Designing zero-external-dependency intranet RAG engines using Ollama, Qdrant VectorDB, and fine-tuned domain models (CamemBERT, Detectron2 OCR).

---

## ⚡ Featured Projects Showcase

### 1. 🔧 GPU Inference Deployment — H200 Air-Gapped Server
> **Status:** In Progress (Sep 2026–Present) | **Tech:** Ubuntu, Docker, NVIDIA H200, vLLM, n8n, PostgreSQL, Qdrant, Prometheus, Grafana
- **Air-Gapped Inference Stack**: Preparing a fresh Ubuntu server with dual H200 GPUs for offline operation with staged packages and container images.
- **Integrated Services**: Running Docker services for vLLM inference, n8n workflows, PostgreSQL persistence, Qdrant vector storage, and comprehensive monitoring (Prometheus + Grafana).
- **Domain Fine-Tuning Support**: Configured Unsloth Studio and Jupyter Notebook for domain-specific model fine-tuning alongside inference workloads.
- **Zero-External Dependency**: Fully air-gapped design for secure enterprise deployments with no external API calls required.

---

### 2. 🌐 [Qrox — Multi-Model AI Chat Platform](https://qrox.vercel.app)
> **Live Demo:** [`qrox.vercel.app`](https://qrox.vercel.app) | **Tech:** Next.js 16, Puter.js AI API, PostgreSQL, Prisma, TailwindCSS, Shadcn UI
- **Perplexity-inspired chat UI** enabling interaction with 500+ frontier AI models (OpenAI, Claude, Gemini, Mistral, xAI) with zero API key management via innovative user-pays architecture.
- **Dual-Authentication Engine**: JWT + Puter SDK guest mode with automatic fallback and race-condition guards for fast session initialization.
- **Real-Time Streaming & Vision**: Markdown rendering, syntax highlighting, multi-image vision support (10 concurrent uploads), and native AI image generation via function calling.
- **Atomic Persistence**: Conversation persistence with balance guards and PostgreSQL on Vercel.

---

### 3. 🤖 OpenClaw AI Agent Platform — Multi-Agent Scraping Swarm
> **Stack:** OpenClaw, Docker, Firecrawl API, MySQL, OpenRouter (owl-alpha), Python/uv, Linux
- **Self-Hosted AI Gateway**: Deployed a 2-tier agent architecture on OpenClaw proxied to OpenRouter LLMs, Firecrawl web intelligence, and MySQL persistence.
- **Autonomous RE-Scraper Subagent**: Built zero-selector scraping autonomy that analyzes page structures, handles hidden APIs/PDFs/pagination, extracts 33 normalized fields per real-estate unit, and executes delta scraping with UPSERT deduplication.
- **Production Performance**: Extracted 262 rental units across 20 floors with 100% data integrity, automated unit conversion ($\text{sq ft} \rightarrow \text{m}^2$), and integrated OpenTelemetry diagnostics.

---

### 4. 💼 HRAI — AI-Powered HR Conversational Assistant
> **Confidential Client, Rabat** | **Stack:** Python 3.11+, TypeScript, FastMCP, FastAPI, Ollama, Sentence Transformers, React, SQL Server, Docker
- **Autonomous Natural-Language-to-SQL**: Transformed personnel database queries into an autonomous French conversational AI interface.
- **Semantic Tool Contract**: Designed novel MCP tool states providing explicit dialogue guidance and next-action recommendations.
- **Sentence Transformers & Self-Healing Validator**: 3-tier entity matching (`paraphrase-multilingual-MiniLM-L12-v2`), Rust-compiler-inspired SQL auto-correction, and Differential Diagnosis menus for query ambiguity.

---

### 5. 🛍️ OmniPilot-CX — AI Sales Agent for E-Commerce
> **Status:** MVP | **Stack:** Next.js, Node.js, PostgreSQL, Prisma, n8n, Chatwoot, Google Gemini API, FB Graph API, Docker
- **Vertical E-Commerce AI SaaS**: Transforming Moroccan merchants' Facebook Messenger inquiries into 24/7 AI sales agents with category-specific personalities for Fashion, Beauty, and Electronics.
- **Multi-Tenant Architecture**: PostgreSQL-backed product catalog, n8n workflows, and encrypted OAuth Facebook integration.
- **Multi-Lingual Automation**: Darija/French/English auto-detection, CSV/XLSX product import with auto-column mapping.

---

### 6. 🏥 Medical Appointment System — Full-Stack Healthcare SaaS
> **Stack:** React, Express.js, Node.js, MySQL, Sequelize ORM, JWT, Tailwind CSS, Shadcn UI, Turborepo
- Scalable healthcare monorepo connecting patients with healthcare providers through real-time booking, doctor availability calendars, and role-based access control (RBAC).

---

### 7. 📊 AI Evaluation Scoring System — HR Performance Analytics
> **Stack:** Python, CamemBERT, FastAPI, Docker
- Internal ML pipeline fine-tuning CamemBERT for French-language sentiment analysis on employee performance evaluations.

---

### 8. ⛽ Fuel Station Management System — MERN Stack + Computer Vision
> **Stack:** Node.js, Express.js, MongoDB, React.js, FastAPI, Docker, Detectron2, JWT
- Fuel station operations system with MERN backend and Moroccan license plate recognition using a custom-trained Detectron2 OCR model.

---

## 💻 Technical Stack Matrix

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Languages** | TypeScript, JavaScript (ES6+), Python, SQL, C#, HTML5, CSS3 |
| **Frontend & UI** | React.js, Next.js 16, Tailwind CSS, Shadcn UI, Redux Toolkit, React Query, Vite |
| **Backend & APIs** | Node.js, Express.js, NestJS, FastAPI, FastMCP, REST APIs, GraphQL, Webhooks |
| **AI / ML & Agents** | OpenClaw, Ollama, Puter.js, n8n, Google Gemini, Claude, LangChain, LangGraph, Qdrant VectorDB, Firecrawl, CamemBERT, Detectron2, PyTorch |
| **Databases & ORMs**| PostgreSQL, MySQL, MongoDB, SQL Server, Prisma ORM, Sequelize |
| **DevOps & Cloud** | Docker, Docker Compose, Git, GitHub Actions, Vercel, NGINX, OpenTelemetry, Linux |

---

## 📊 GitHub Analytics

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=oxcodexo&show_icons=true&theme=dark&bg_color=0d1117&title_color=00f2fe&text_color=c9d1d9&icon_color=4facfe&border_color=30363d&hide_border=false" />
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=oxcodexo&layout=compact&theme=dark&bg_color=0d1117&title_color=00f2fe&text_color=c9d1d9&border_color=30363d&hide_border=false" />

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=oxcodexo&theme=dark&background=0d1117&ring=00f2fe&fire=4facfe&currStreakLabel=00f2fe&border=30363d" alt="oxcodexo streak" />

</div>

---

<div align="center">

### 🤝 Connect with Me

Whether you want to discuss **AI Agent Architecture**, collaborate on open-source projects, or explore enterprise software solutions, feel free to reach out!

[📫 Email Me](mailto:hichamkraou1@gmail.com) • [💼 LinkedIn Profile](https://linkedin.com/in/oxcodexo) • [🌐 Qrox AI Chat](https://qrox.vercel.app)

***

*Designed with ⚡ by Hicham Kraou (`oxcodexo`)*

</div>
