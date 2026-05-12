<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/profile/hero-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/profile/hero-light.svg">
  <img alt="G. Karthik Koundinya - AI and backend engineer" src="./assets/profile/hero-light.svg" width="100%">
</picture>

<p align="center">
  <a href="https://g26karthik.github.io/Portfolio/"><img src="https://img.shields.io/badge/Portfolio-111111?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"></a>
  <a href="https://linkedin.com/in/g-karthik26"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:karthikofficialmain@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://drive.google.com/file/d/1WvDCHCJNnAgBldLk-3jFeYOPITHGz-qS/view"><img src="https://img.shields.io/badge/Resume-2563EB?style=for-the-badge&logo=googledrive&logoColor=white" alt="Resume"></a>
</p>

## About

I build applied AI software where the hard part is not only calling a model, but making the system useful: retrieval, routing, evaluation, latency, observability, API design, and failure handling.

My strongest lane is **AI engineering with backend depth**: Python services, LLM/RAG pipelines, agent workflows, data-backed APIs, and production-facing systems. I am targeting **AI Engineer**, **Applied AI Engineer**, **AI Software Engineer**, and **Backend Engineer** roles.

## Depth Areas

| Focus | Evidence |
|---|---|
| LLM systems | LangGraph agents, grounded support triage, multi-agent monitoring, LLM routing, citation checks |
| Retrieval | BM25 + dense embeddings, reranking, FAISS, score transparency, caching, source-grounded answers |
| Backend engineering | API design, async workers, request-path optimization, PostgreSQL/Supabase, MongoDB, deployment workflows |
| ML implementation | PyTorch, Transformers, Whisper, EfficientNet, Grad-CAM, quantization experiments, OpenCV pipelines |
| Reliability | deterministic fallbacks, rate limiting, CI/CD, trace logs, eval harnesses, memory/performance fixes |

## Competitive Programming

| Platform | Rating | Standing |
|---|---:|---|
| [CodeChef](https://www.codechef.com/users/g26karthikk) | 2483, 6-star | **#6 India, #76 Global** |
| [LeetCode](https://leetcode.com/u/G26KarthikK/) | 2665, Guardian | **Top 0.9% globally** |

## Experience

**Full Stack Engineering Intern - Stealth Startup**<br>
*Jan 2026 - Apr 2026, Hyderabad*

Acted as the sole full-stack engineer in a zero-structure startup environment, taking a scalable social platform from concept to deployment-ready system.

- Reduced database calls by about **50%** and improved latency by about **30%** by restructuring backend request paths, optimizing query execution, and reducing payload overhead.
- Built realtime auth and live-update flows with Supabase Realtime, then deployed on AWS EC2 with PM2 and CI/CD automation.
- Led responsive web delivery and a Flutter mobile migration, resolving product and architecture mismatches between web and mobile workflows.

**Open Source Contributor - pandas, matplotlib, SQLFluff, mem0, Google ADK, SymPy, Kubeflow, and others**<br>
*Oct 2025 - Present*

- **21 PRs counted** across merged and active work: **15 merged + 6 open** across AI, data, devtools, infrastructure, and backend-adjacent repositories.
- Merged work includes PyArrow datetime regression coverage in pandas, PostgreSQL `OPERATOR()` parser support in SQLFluff, Azure AI Search vector-store support in mem0, and production reliability fixes in interviewstreet/hiring-agent.
- Active work includes multilingual evaluator support in Google ADK, SymPy assumption handling, Kubeflow SDK log streaming, TheAlgorithms/Python graph algorithms, and Composio skill contribution.

**AI & Frontend Development Intern - Edunet Foundation**<br>
*Aug 2025 - Oct 2025*

- Built a lecture audio-to-notes system using Whisper, T5, DistilBART, keyword extraction, and PDF/DOCX generation for long-form lectures.
- Improved inference efficiency by about **80%** through GPU-accelerated Whisper with caching, measured against the earlier processing path.
- Shipped a responsive React portfolio with optimized rendering and lazy loading.

**Web Development & SEO Intern - Badakarobar**<br>
*Mar 2025 - Jun 2025*

- Built and optimized responsive landing pages, improving Lighthouse performance by about **45%** through frontend and metadata improvements.
- Automated sitemap generation with Python, removing a recurring manual SEO workflow.

## Selected Work

### AI, ML, and Agentic Systems

| Project | What it proves |
|---|---|
| [Grounded Support Triage](https://github.com/G26karthik/grounded-support-triage) | LangGraph support pipeline with triage, hybrid retrieval, deterministic citation criticism, escalation fallback, tracing, and evaluation. |
| [EdgeSentinel](https://github.com/G26karthik/EdgeSentinel) | Cloudflare-native request intelligence using Workers, Durable Objects, KV, D1, Vectorize, Workers AI, and OpenAI fallback. |
| [SupplySentinel](https://github.com/G26karthik/SupplySentinel) | Three-agent supply-chain risk monitor with evidence expansion, confidence loop, deduplication, and Cloud Run deployment. |
| [Lumina Search](https://github.com/G26karthik/Lumina-Search) | Hybrid FAISS + BM25 search engine with SQLite content-hash caching, AsyncIO backend, and transparent score breakdowns. |
| [AI Dermatology Assistant](https://github.com/G26karthik/Skin-Disease) | EfficientNet-B0 skin lesion classifier with 81% validation accuracy, 0.67 macro-F1, AMP, Albumentations, and Grad-CAM. |
| [Lecture Voice-to-Notes](https://github.com/G26karthik/voice) | Whisper + summarization pipeline for notes, flashcards, MCQs, progress tracking, and exportable study material. |
| [AI Network Traffic Shaper](https://github.com/G26karthik/AI-Network-Traffic-Shaper) | Real-time traffic classification and QoS shaping using statistical features, scikit-learn, PyShark, and firewall automation. |
| [TurboQuant KV Cache](https://github.com/G26karthik/turboquant-kvcache) | PyTorch implementation of TurboQuant-style KV-cache compression with reproducible benchmark artifacts and tradeoff reports. |
| [Antim](https://github.com/G26karthik/Antim---AI-Bereavement-Assistance-Agent) | Client-side AI assistant for India-specific bereavement workflows with streaming responses and low-friction UX. |
| [productionize](https://github.com/G26karthik/skill-productionize) | Reusable Claude Code skill for productionization reviews across validation, typing, logging, security, naming, and maintainability. |

### Backend and Product Systems

| Project | What it proves |
|---|---|
| [College Lost & Found](https://github.com/G26karthik/Lost-and-Found) | MERN platform used by 200+ students with JWT auth, Cloudinary media, MongoDB filtering, and responsive reporting workflows. |
| [UML Designer AI](https://github.com/G26karthik/UML-Designer) | Multi-service diagram platform using Flask analysis, Node.js APIs, Next.js UI, and PlantUML generation. |
| [AI Interview Assistant](https://github.com/G26karthik/AI-Interview-Assistant) | Resume parsing, timed interview flow, streaming LLM responses, and structured answer scoring without backend infrastructure. |
| [Fog4Det](https://github.com/G26karthik/Fog-Detection-System-for-Vehicles) | FastAPI + OpenCV real-time fog classifier with driver/developer views and tunable detection parameters. |
| [AgriSure](https://github.com/G26karthik/AgriSure) | Flask agricultural insurance platform with farmer/agent roles, document uploads, claim tracking, and role-based access control. |
| [PinPoint AI](https://github.com/G26karthik/Pin-Point-New-Gen-Logistics-App) | Flutter logistics app with exact pins, saved locations, voice notes, push notifications, agent claiming, and Gemini-assisted guidance. |

## Open Source Highlights

| Repository | Status | Contribution |
|---|---|---|
| [mem0ai/mem0 #3549](https://github.com/mem0ai/mem0/pull/3549) | Merged | Azure AI Search vector store support for the TypeScript SDK. |
| [pandas-dev/pandas #62592](https://github.com/pandas-dev/pandas/pull/62592) | Merged | PyArrow datetime merge regression test. |
| [pandas-dev/pandas #62591](https://github.com/pandas-dev/pandas/pull/62591) | Merged | Ruff B905 cleanup in pandas config code. |
| [sqlfluff/sqlfluff #7163](https://github.com/sqlfluff/sqlfluff/pull/7163) | Merged | PostgreSQL `OPERATOR()` syntax support. |
| [matplotlib/matplotlib #30639](https://github.com/matplotlib/matplotlib/pull/30639) | Merged | `TwoSlopeNorm` colorbar documentation improvement. |
| [interviewstreet/hiring-agent #133](https://github.com/interviewstreet/hiring-agent/pull/133) | Merged | PyMuPDF memory-leak fix using document context management. |
| [google/adk-python #3503](https://github.com/google/adk-python/pull/3503) | Open | Non-English evaluator support for Hindi, Chinese, and Arabic. |
| [kubeflow/sdk #436](https://github.com/kubeflow/sdk/pull/436) | Open | Real-time log streaming behavior without print side effects. |
| [sympy/sympy #29605](https://github.com/sympy/sympy/pull/29605) | Open | `refine_sign()` assumption handling fix. |

## Technical Core

| Area | Core tools |
|---|---|
| Languages | Python, TypeScript, JavaScript, SQL |
| AI engineering | PyTorch, Transformers, Whisper, LangGraph, LangChain, FAISS, BM25, SentenceTransformers, LLM APIs |
| Backend | FastAPI, Flask, Node.js, Express, REST APIs, async processing, PostgreSQL, Supabase, MongoDB |
| Infra | Docker, GitHub Actions, AWS EC2, Google Cloud Run, Cloudflare Workers, PM2 |
| Applied ML | scikit-learn, OpenCV, Grad-CAM, evaluation harnesses, caching, latency profiling |

## GitHub Signal

<p align="center">
  <img src="https://github-readme-stats-fast.vercel.app/api?username=g26karthik&show_icons=true&theme=transparent&hide_rank=true&hide_border=true" alt="GitHub stats" width="48%">
  <img src="https://github-readme-stats-fast.vercel.app/api/top-langs?username=g26karthik&layout=compact&theme=transparent&hide_border=true&hide=html,css" alt="Top languages" width="36%">
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=g26karthik&label=Profile%20views&color=0f172a&style=flat-square" alt="Profile views">
</p>
