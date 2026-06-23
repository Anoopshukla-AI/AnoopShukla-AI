<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=2563EB&center=true&vCenter=true&width=600&lines=AI+Automation+Engineer;LangChain+·+LangGraph+·+n8n+·+RAG;Multi-Agent+Systems+·+MCP+Protocol;2+Years+Production+AI+|+Gurugram" alt="Typing SVG" />
</div>

<br/>

<div align="center">
  <b>AI Automation Engineer with 2 years of production experience in financial services — shipped 6 end‑to‑end systems including RAG pipelines, multi‑agent orchestration, and loan processing automation. Reduced manual effort by 30–50% across departments. Backed by 7 years in enterprise IT infrastructure, ensuring my AI solutions are robust, secure, and enterprise‑ready. Available immediately for full‑time, on‑roll opportunities in Gurugram / Delhi NCR.</b>
</div>

---

## ⚙️ What I Actually Work With

<div align="center">

### AI & Agents
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![CrewAI](https://img.shields.io/badge/CrewAI-FF4B4B?style=for-the-badge&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97706?style=for-the-badge&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)

### RAG & Vector
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=for-the-badge&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC143C?style=for-the-badge&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white)

### Automation
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Power Automate](https://img.shields.io/badge/Power%20Automate-0066FF?style=for-the-badge&logo=microsoft&logoColor=white)
![Make](https://img.shields.io/badge/Make-6D00CC?style=for-the-badge&logo=make&logoColor=white)

### Infrastructure
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### Cloud AI
![AWS Bedrock](https://img.shields.io/badge/AWS%20Bedrock-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Azure OpenAI](https://img.shields.io/badge/Azure%20OpenAI-0089D6?style=for-the-badge&logo=microsoftazure&logoColor=white)

</div>

---

## 📂 Projects

| Repo | What it does | Impact |
|------|--------------|--------|
| **[mcp-copilot-a2a](https://github.com/Anoopshukla-AI/mcp-copilot-a2a)** | Multi-agent pipeline using MCP + A2A Protocol. Researcher → Analyst → Writer. LangGraph stateful agents, Datadog observability, circuit-breakers, Docker. | Automated research + writing, reduced analyst workload by **35%** |
| **[enterprise-ai-control-plane](https://github.com/Anoopshukla-AI/enterprise-ai-control-plane)** | LLM gateway with JWT auth, RBAC, policy engine, audit logging, and cost tracking. | Enabled secure AI adoption in finance, cut cloud spend by **20%** |
| **[AI-Loan-Processing-Automation](https://github.com/Anoopshukla-AI/AI-Loan-Processing-Automation-)** | Document AI extraction, GPT-4o risk scoring, confidence-based human routing, full audit trail with reasoning chain. GuardRails AI on output layer. | Reduced manual loan review effort by **40%**, processed **10k+ docs/month** |
| **[n8n-automation-portfolio](https://github.com/Anoopshukla-AI/n8n-automation-portfolio)** | 8 production n8n workflows: ticket classification, lead enrichment, AI email responder, RAG pipeline, CRM sync, ETL, error handler. | Automated **70% of repetitive tasks**, cut ticket triage time by **40%** |
| **[rag-knowledge-bot](https://github.com/Anoopshukla-AI/rag-knowledge-bot)** | LangChain + ChromaDB RAG pipeline. MMR re-ranking, GuardRails AI, source citations. Served 100+ employees in production. | Reduced policy lookup time by **50%**, served **100+ employees daily** |

---

## 🏗 Architecture Diagrams

### mcp-copilot-a2a
```mermaid
flowchart LR
    A[Researcher Agent] --> B[Analyst Agent]
    B --> C[Writer Agent]
    C --> D[Final Output]
    subgraph Observability
        E[Datadog Logs]
        F[Circuit Breakers]
    end
    B --> E
    C --> F
