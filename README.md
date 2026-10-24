<div align="center">

# ⚡ Hicham Kraou (`oxcodexo`)
### **Full-Stack & AI Developer — RAG, LLM Agents & Private Deployments**
📍 *Rabat, Morocco* 🇲🇦

[![LinkedIn](https://img.shields.io/badge/LinkedIn-oxcodexo-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/oxcodexo)
[![GitHub](https://img.shields.io/badge/GitHub-oxcodexo-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/oxcodexo)
[![Email](https://img.shields.io/badge/Email-hichamkraou1%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hichamkraou1@gmail.com)
[![Live Demo](https://img.shields.io/badge/Live_Demo-Qrox_AI-00F2FE?style=for-the-badge&logo=vercel&logoColor=black)](https://qrox.vercel.app)

---

</div>

## 🚀 About Me

I am a **Full-Stack & AI Developer** specializing in **RAG systems**, **LLM Agents**, **private model deployment**, and **production SaaS architecture**. I build end-to-end applications combining Next.js/TypeScript frontends, Node.js backends, and secure offline AI systems with local model inference.

I architect autonomous agent systems for document intelligence, multilingual conversational interfaces, and enterprise workflow automation — always with a focus on data privacy and offline-first deployments.

---

## 🛠️ Core Expertise & Architectural Innovations

- 🤖 **Autonomous AI Agents & Workflows**: Building multi-agent systems for document intelligence, data extraction, and workflow automation; implementing semantic tool contracts and dialogue guidance patterns.
- 🧩 **Semantic Tool Design (MCP)**: Architecting tool microservices with explicit execution states and next-action guidance for robust agent reasoning.
- 🏗️ **Full-Stack SaaS Architecture**: Designing and shipping production applications: Next.js 16, React, Node.js, NestJS, TypeScript, PostgreSQL, Prisma, multi-tenant isolation.
- 📐 **Text-to-SQL at Scale**: Engineering modular Text-to-SQL pipelines combining schema verification with flexible LLM-generated filters.
- 🛡️ **Private & Offline AI**: Building zero-external-dependency intranet RAG systems using Ollama, Qdrant, and domain-fine-tuned models.

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

### 5. 🛍️ OmniPilot-CX — E-Commerce Sales Assistant for Messenger
> **Status:** MVP | **Tech:** Next.js, Node.js, PostgreSQL, Prisma, n8n, Chatwoot, Google Gemini API, FB Graph API, Docker
- **Vertical E-Commerce AI SaaS**: Multilingual product-management and Messenger sales-assistant workflows for e-commerce merchants, built on a PostgreSQL-backed product catalog with n8n automation and API integrations.
- **Conversation Handling**: Handling Darija/French/English customer conversations through the Facebook Graph API.
- **Order Capture**: Workflow orchestration around product catalog with language-aware responses.

---

### 6. 🌐 MCP Launch — Self-Hosted MCP Gateway
> **Tech:** Docker, Caddy, ngrok, MCP
- **Gateway Architecture**: Docker-based gateway exposing isolated MCP servers to AI agents through Caddy reverse proxy and HTTPS tunnel.
- **Path-Based Routing**: Route-based isolation to each server with bearer-token validation on every request.
- **Isolated Services**: Each MCP server runs in its own container, isolated from others while exposed behind a single endpoint.

---

### 7. 🛍️ [Fleetora — Multilingual Car-Rental Marketplace](https://fleetora.vercel.app)
> **Live:** [`fleetora.vercel.app`](https://fleetora.vercel.app) | **Tech:** Next.js, TypeScript, PostgreSQL, Prisma, Docker | **Date:** May 23–Aug 11, 2026
- **B2B Agency & B2C Renter Marketplace**: Full-featured rental platform for the Moroccan market with dual workflows for fleet operators and end consumers.
- **Multilingual & Regional**: French, Arabic, and English support with North African payment and availability patterns.
- **Production-Ready**: Fully hosted on Vercel with PostgreSQL backend; documented agency/renter feature sets.

---

### 8. 🏥 Medical Appointment System — Full-Stack Healthcare SaaS
> **Stack:** React, Express.js, Node.js, MySQL, Sequelize ORM, JWT, Tailwind CSS, Shadcn UI, Turborepo
- Scalable healthcare monorepo connecting patients with healthcare providers through real-time booking, doctor availability calendars, and role-based access control (RBAC).

---

### 9. 📊 French-Language Evaluation Scoring — HR Performance Analytics
> **Stack:** Python, CamemBERT, FastAPI, Docker
- CamemBERT fine-tuned on French narrative employee evaluations, serving an internal scoring workflow through FastAPI and a React interface.

---

### 10. ⛽ Retail Operations & Plate Recognition — MERN Stack + Computer Vision
> **Stack:** Node.js, Express.js, MongoDB, React.js, Flutter, FastAPI, Docker, Detectron2
- Fuel-station operations software with Node.js and React backend, Flutter employee application, and Detectron2-based Moroccan license-plate recognition served through FastAPI.

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
