<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/profile/hero-dark.svg">
  <img alt="G. Karthik Koundinya, Applied AI Engineer at RamanIQ. I build AI that holds up in production: agents, retrieval systems, risk models, evals." src="./assets/profile/hero-light.svg" width="100%">
</picture>

<p align="center">
  <a href="https://github.com/G26karthik/whatsapp-notification-router"><img src="https://img.shields.io/badge/HackerRank_Orchestrate_Aug_'26-20th_of_1%2C983-2a78d6?style=for-the-badge&logo=hackerrank&logoColor=white" alt="HackerRank Orchestrate Aug 2026: 20th of 1,983"></a>
  <a href="https://github.com/G26karthik/grounded-support-triage"><img src="https://img.shields.io/badge/HackerRank_Orchestrate_May_'26-12th_of_12%2C885-2a78d6?style=for-the-badge&logo=hackerrank&logoColor=white" alt="HackerRank Orchestrate May 2026: 12th of 12,885"></a>
  <br>
  <a href="https://langfuse.com/security/responsible-disclosure#hall-of-fame"><img src="https://img.shields.io/badge/Langfuse-Security_Hall_of_Fame-eb6834?style=for-the-badge" alt="Langfuse Security Hall of Fame"></a>
  <img src="https://img.shields.io/badge/Microsoft_Certified-AI--103_%C2%B7_DP--800-0078D4?style=for-the-badge&logo=microsoft&logoColor=white" alt="Microsoft Certified AI-103 and DP-800">
  <br>
<a href="https://www.codechef.com/users/g26karthikk">
  <img src="https://img.shields.io/badge/CodeChef-6%E2%98%85_%C2%B7_2483_%C2%B7_%234_India-5B4638?style=for-the-badge&logo=codechef&logoColor=white" alt="CodeChef 6 star, rating 2483, rank 4 in India">
</a>
  <a href="https://leetcode.com/u/G26KarthikK/"><img src="https://img.shields.io/badge/LeetCode-2665_Guardian-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode 2665 Guardian"></a>
</p>

<p align="center"><samp>
  <a href="https://g26karthik.github.io/Portfolio/">portfolio</a> ·
  <a href="https://linkedin.com/in/g-karthik26">linkedin</a> ·
  <a href="mailto:karthikofficialmain@gmail.com">email</a> ·
  <a href="https://github.com/search?q=author%3AG26karthik+is%3Apr&type=pullrequests&s=created&o=desc">all my PRs</a>
</samp></p>

**Applied AI Engineer at RamanIQ.** I build AI systems that have to be right: agents, retrieval, and the evals that keep them honest. Before this, I shipped production ML at Hecta Proptech and was the sole full-stack engineer at chkchk, a stealth startup. B.Tech CSE '27, Hyderabad.

<table align="center">
  <tr>
    <td align="center"><sub>SERVING</sub><h3>5K+ users/day</h3><sub>production ML at Hecta Proptech</sub></td>
    <td align="center"><sub>LANDED UPSTREAM</sub><h3>13 contributions</h3><sub>12 merged PRs + a Langfuse fix</sub></td>
    <td align="center"><sub>MERGED INTO</sub><h3>165K★ projects</h3><sub>pandas · mem0 · matplotlib · more</sub></td>
  </tr>
</table>

## 💼 Experience

| Role | Where | What I did |
|---|---|---|
| **Applied AI Engineer** | RamanIQ · Sep 2026 – now | Just joined; building applied AI systems |
| **Tech Engineer, AI & Backend** | Hecta Proptech · Jun – Jul 2026 | CatBoost + GPU embeddings over **175K+ auction notices**: **84.3% ROC-AUC**, **80% less manual review**. A Cox survival model (**0.79 C-index**) behind a validated Flask API, and the first hybrid RAG platform |
| **Full Stack Engineer (sole)** | chkchk (stealth startup) · Jan – Apr 2026 | Built a creative-talent marketplace end to end on Next.js and Supabase: **−50% DB calls, −30% latency**, realtime, EC2 + CI/CD, and the Android app. **66 of 74 commits** |
| **AI & Frontend Intern** | Edunet Foundation · 2025 | A Whisper + T5 lecture-to-notes pipeline, **~80% faster** with GPU inference and caching |

## 🚀 My Projects

<table>
<tr>
<td width="50%" valign="top">

**[WhatsApp Notification Router](https://github.com/G26karthik/whatsapp-notification-router)**<br>
`LLM consensus` `multimodal` `safety`

- Decides **notify, digest or mute** per user across text, images and voice: a **5-vote LLM majority** over a closed bank of 27 reasons, with code deciding action and confidence.
- **Muted 8 of 8** scam and prompt-injection attacks. Survived **5 mid-run kills** with zero lost calls. Honest [post-mortem](https://github.com/G26karthik/whatsapp-notification-router#post-mortem-why-20th-and-not-1st).

</td>
<td width="50%" valign="top">

**[Nishchay](https://github.com/G26karthik/Nishchay)**: COD risk engine<br>
`Razorpay AI Buildathon` `LightGBM` `conformal`

- **₹72.9L net saved** on **44,288 held-out orders**. PR-AUC **0.677 vs 0.304** baseline at **0.986 recall**, with a decision threshold derived from each merchant's own costs.
- LLM agents kept off the decision path. **18,827 live agent calls** proved it, and I reported the result honestly: no lift.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[Grounded Support Triage](https://github.com/G26karthik/grounded-support-triage)**<br>
`LangGraph` `hybrid RAG` `citation critic`

- Multi-agent triage over a 774-document corpus: **BM25 + dense + cross-encoder rerank**, and a deterministic citation critic that blocks unsupported answers.
- **0–2 LLM calls per ticket** thanks to regex fast paths and structured routing.

</td>
<td width="50%" valign="top">

**[AlgoSentinel](https://github.com/G26karthik/algosentinel)**: autonomous PR auditor<br>
`agents` `Docker sandbox` `Gemini`

- **55 tools across 4 namespaces**. It benchmarks the old and new versions of each function in a sandbox and fits growth curves to catch **O(n) → O(n²)** regressions from real runtimes.
- Compresses its context to sustain **20+ tool calls per audit**, then posts evidence-backed PR reviews.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[KVQuant Lab](https://github.com/G26karthik/kvquant-lab)**: LLM inference research<br>
`PyTorch` `quantization` `TurboQuant (ICLR '26)`

- **4.65× KV-cache compression** (5.6 MB → 957 KB) at near-baseline perplexity (4.68 vs 4.26).
- **+73% recall@1** with Adaptive QJL, and **100% needle-in-a-haystack** recall at 3.2× compression. Reproduced 9 paper claims.

</td>
<td width="50%" valign="top">

**[EdgeSentinel](https://github.com/G26karthik/EdgeSentinel)**: edge bot detection<br>
`Cloudflare Workers` `Vectorize` `Durable Objects`

- A 5-stage classifier at **under 10 ms of overhead per request**, running entirely on Cloudflare's free tier.
- Behavioral vector search, heuristics and LLM inference, with atomic per-IP rate limiting and non-blocking writes.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[Dual AI Assistant Benchmark](https://github.com/G26karthik/Dual-AI-Assistant-s-Benchmark)**: LLM evals<br>
`evals` `Llama Guard 3` `HF Spaces`

- **1,000 runs** across 5 safety suites (hallucination, bias, toxicity, jailbreaks), scored by a **3-judge LLM panel** with NLI consistency checks.
- An OSS assistant with memory, tools and two-stage guardrails, [live on Hugging Face](https://huggingface.co/spaces/LuciferMrng/dual-ai-assistant-benchmark-oss).

</td>
<td width="50%" valign="top">

**[Sandbox Warm Pool Controller](https://github.com/G26karthik/sandbox-warm-pool-controller)**: Kubernetes<br>
`Go` `CRDs` `gVisor / Kata` `Prometheus`

- Pre-warms isolated sandbox pods to remove **1–5 s cold starts**, using a 6-state pod lifecycle.
- A race-free assignment API with auto-replenishment and Prometheus latency metrics.

</td>
</tr>
</table>

<sub>More: [Setu](https://github.com/G26karthik/Sethu-AI) (district health network with a human-approved allocation solver) · [Forensic Evidence Indexer](https://github.com/G26karthik/Forensic-Evidence-Indexer) (C++17 streaming hasher) · [MindSafe](https://github.com/G26karthik/MindSafe) (ZK-proof mental-health dApp) · [Avia](https://github.com/G26karthik/Avia) (fraud-detection SaaS) · [FounderOS](https://github.com/G26karthik/FounderOS) (🥈 2nd prize)</sub>

## 🌍 Open Source

| Project | What I contributed | Status |
|---|---|---|
| [mem0](https://github.com/mem0ai/mem0/pull/3549) · 65K★ | The Azure AI Search vector store for the TypeScript SDK: hybrid search and quantization, **754 lines** | ✅ Merged |
| [pandas](https://github.com/pandas-dev/pandas/pulls?q=is%3Apr+author%3AG26karthik) · 49.7K★ | A PyArrow datetime-merge regression test, Ruff B905 enforcement, and a docstring migration | ✅ 3 Merged |
| [Langfuse](https://github.com/langfuse/langfuse/pull/14789) · 34.5K★ | Found a prompt-cache key collision (version `3` vs label `"3"` served each other's prompt) | 🚀 Shipped via [#15040](https://github.com/langfuse/langfuse/pull/15040) |
| [matplotlib](https://github.com/matplotlib/matplotlib/pull/30639) · 23K★ | Documented the TwoSlopeNorm linear-colorbar workaround | ✅ Merged |
| [sktime](https://github.com/sktime/sktime/pull/8923) · 10K★ | Fixed broken pytorch-forecasting references in the forecaster adapters | ✅ Merged |
| [SQLFluff](https://github.com/sqlfluff/sqlfluff/pull/7163) · 9.9K★ | A PostgreSQL `OPERATOR(schema.op)` parser, **649 lines** with fixtures | ✅ Merged |
| [HackerRank hiring-agent](https://github.com/interviewstreet/hiring-agent/pulls?q=is%3Apr+author%3AG26karthik) · 7.2K★ | Fixed a PyMuPDF memory leak and a Windows UTF-8 crash | ✅ 2 Merged |
| chkchk (startup) | The Android app (Capacitor) and the full rebrand, **+5.6K lines** | ✅ 2 Merged |
| [naija-nutri-hub](https://github.com/mlsanigeria/naija-nutri-hub/pull/52) | OTP email verification on signup | ✅ Merged |

<sub>Also: `/lgtm` from Koordinator maintainers for a webhook-crash fix, "LGTM" at Google ADK, and open PRs to Kubeflow SDK and SymPy.</sub>

## 🛠 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,ts,go,cpp,java,pytorch,fastapi,flask,react,nextjs,nodejs&perline=11" alt="Languages and frameworks"><br>
  <img src="https://skillicons.dev/icons?i=supabase,postgres,mongodb,redis,docker,kubernetes,aws,gcp,cloudflare,git,linux&perline=11" alt="Data and infrastructure">
</p>
<p align="center"><sub>LLMs &amp; ML: OpenAI · Claude · Gemini · LangGraph · Hugging Face · LightGBM · CatBoost · XGBoost · scikit-learn · FAISS · BM25</sub></p>

## 📊 GitHub

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats-fast.vercel.app/api?username=G26karthik&show_icons=true&include_all_commits=true&hide_border=true&hide_rank=true&theme=github_dark">
    <img src="https://github-readme-stats-fast.vercel.app/api?username=G26karthik&show_icons=true&include_all_commits=true&hide_border=true&hide_rank=true" alt="GitHub stats" height="165">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats-fast.vercel.app/api/top-langs?username=G26karthik&layout=compact&hide_border=true&hide=html%2Ccss&langs_count=8&theme=github_dark">
    <img src="https://github-readme-stats-fast.vercel.app/api/top-langs?username=G26karthik&layout=compact&hide_border=true&hide=html%2Ccss&langs_count=8" alt="Top languages" height="165">
  </picture>
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/G26karthik/G26karthik/output/snake-dark.svg">
  <img alt="Contribution graph being eaten by a snake" src="https://raw.githubusercontent.com/G26karthik/G26karthik/output/snake.svg" width="100%">
</picture>
