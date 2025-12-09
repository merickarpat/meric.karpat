<!-- HEADER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b27,100:3b82f6&height=200&section=header&text=Meriç%20Karpat&fontSize=48&fontColor=ffffff" />

<!-- INTRO -->
<p align="center">
  <a href="https://github.com/merickarpat">
    <img src="https://readme-typing-svg.herokuapp.com?size=24&duration=4000&pause=800&color=3B82F6&center=true&vCenter=true&width=650&lines=Full+Stack+JavaScript+Developer;SaaS+Founder;AI-powered+Platforms;DashPilot+%7C+Incident+Cortex" />
  </a>
</p>

---

## 🚀 What I'm Building

### 🌐 DashPilot — AI-powered Amazon Analytics (SaaS)
<p>
  <img src="https://img.shields.io/badge/DashPilot-AI%20Amazon%20Analytics-0F172A?style=for-the-badge&logo=amazon&logoColor=F59E0B" />
</p>

A full commercial analytics platform for Amazon sellers:

- Keepa CSV/Excel ingestion & transformation  
- Token-based AI analysis (OpenAI / Abacus)  
- Insight engine, predictive scoring & dashboards  
- PostgreSQL · Prisma · Redis · Workers  
- Designed for high-volume global use

#### DashPilot Architecture
```mermaid
flowchart TB
  A[Keepa CSV / Excel Upload] --> B[Ingestion & Parsing]
  B --> C[(PostgreSQL)]
  C --> D[Job Queue / Workers]
  D --> E[AI Engines - OpenAI and Ollama]
  E --> F[Product Insights & Scores]
  F --> G[Next.js Dashboard]
  C --> H[Analytics and Reports]
```

### ⚡ Incident Cortex — AI-driven Incident & Runbook Automation
<p> 
  <img src="https://img.shields.io/badge/Incident%20Cortex-AI%20Runbook%20Search-020617?style=for-the-badge&logo=slack&logoColor=36C5F0" /> 
</p>

- An AI-first backend built to reduce MTTR by giving engineers instant answers:
- Semantic search over runbooks (pgvector)
- Automatic embedding pipeline
- Slack slash commands & interactive workflows
- Express + TypeScript + Neon + Drizzle ORM
  
#### Incident Cortex Architecture
```mermaid
flowchart TB
  A[Slack Events and Commands] --> B[Express API and Slack Controller]
  B --> C[Runbook Service]
  C --> D[(NeonDB with pgvector)]
  C --> G[Background Workers]
  G --> H[OpenAI Embeddings]
  H --> X[ ]
  X --> D
  D --> E[Semantic Search Service]
  E --> F[Slack Response Message]
```
---

## 🧠 Tech Arsenal
<p align="left"> 
  <img src="https://skillicons.dev/icons?i=ts,nextjs,nodejs,react,postgres,redis,docker,prisma,git,vercel" /> 
</p>

### Strong Focus Areas
- **End-to-end TypeScript systems**
- **Scalable backend architecture (queues, caching, workers)**
- **AI & LLM integration (RAG, embeddings, semantic search)**
- **SaaS platform design (auth, billing, usage metering)**
- **PostgreSQL performance, schema design & migrations**

---

## 📊 Real Impact

<div align="center">

| Metric | Value |
|--------|-------|
| 🚀 **SaaS Products Built** | 2 (in production) |
| 🤖 **AI Models Integrated** | OpenAI GPT-4, Embeddings, Custom ML |
| ⚡ **API Response Time** | <200ms (p95) |
| 💾 **Data Processed** | 10M+ product records |
| 👥 **Active Users** | 50+ (and growing) |

</div>

---

## 🏗️ Architecture Philosophy

> **"Build for scale from day one, optimize for developer experience always."**

- **Type-safe everything** — TypeScript end-to-end, Zod validation, Prisma types
- **AI-first thinking** — RAG > fine-tuning, semantic search > keyword matching
- **Observability built-in** — OpenTelemetry, structured logging, error tracking
- **Zero-downtime deploys** — CI/CD with automated testing, gradual rollouts
- **Cost-conscious scaling** — Redis for hot data, PostgreSQL for everything else

---

## 💡 Side Interests

- **Self-hosted LLMs** → Experimenting with Ollama for cost optimization
- **Vector databases** → Building custom pgvector indexes for sub-second search
- **Developer tools** → VSCode extensions, CLI tools, automation scripts
- **SaaS pricing models** → Usage-based vs. subscription vs. hybrid strategies

---

## 📫 Let's Build Something

<div align="center">

[![Email](https://img.shields.io/badge/Email-meric.karpat%40icloud.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:meric.karpat@icloud.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/meric-karpat)
[![Location](https://img.shields.io/badge/Location-Izmir%2C%20Turkey-00ADD8?style=for-the-badge&logo=google-maps&logoColor=white)](https://www.google.com/maps/place/Izmir)

### Open to:
🤝 Technical co-founders for AI/SaaS projects  
💼 Contract work or colloquia on complex backend systems  
🎙️ Speaking about SaaS architecture & AI integration  
☕ Coffee chats about startup ideas

</div>

---

<div align="center">

##"Ship fast, iterate faster, never stop learning."##

⭐ If you find my work interesting, feel free to contact me or star my public repos!

</div> <!-- FOOTER --> <img src="https://capsule-render.vercel.app/api?type=waving&color=0:3b82f6,100:1a1b27&height=120&section=footer" /> ```
