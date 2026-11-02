<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/profile/hero-dark.svg">
  <img alt="G. Karthik Koundinya, Applied AI Engineer and Researcher. I build and research LLM systems, quantization, quantum ML and evals." src="./assets/profile/hero-light.svg" width="100%">
</picture>


<p align="center">
  <a href="https://g26karthik.dev"><img src="https://img.shields.io/badge/Portfolio-g26karthik.dev-0b6e4f?style=for-the-badge" alt="Portfolio at g26karthik.dev"></a>
  <a href="https://www.linkedin.com/in/g-karthik26"><img src="https://img.shields.io/badge/LinkedIn-g--karthik26-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:karthikofficialmain@gmail.com"><img src="https://img.shields.io/badge/Email-get_in_touch-d7381f?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

Hi, I'm Karthik. I build AI systems and spend a lot of time making sure they still work on data they have never seen. That is most of what I do: agents and retrieval that I test properly, LLM quantization, quantum ML, and evaluation work where I write the hypothesis down before I run the experiment.

I also like fixing things in other people's code. So far that is **28 open-source contributions**, including PyTorch, pandas and mem0, and I am still adding to the list.

I'm in the final year of my B.Tech in CSE (Geethanjali College of Engineering and Technology, Hyderabad) and I'm looking for applied AI and ML roles. If something here looks like a fit, [email me](mailto:karthikofficialmain@gmail.com).

<table align="center">
  <tr>
    <td align="center"><sub>COMPETITION</sub><h3>1st of 4,600</h3><sub>HackerRank Orchestrate, Oct 2026</sub></td>
    <td align="center"><sub>OPEN SOURCE</sub><h3>28 contributions</h3><sub>25 merged PRs in 19 projects + 3 credited fixes, 350K+ combined stars</sub></td>
    <td align="center"><sub>RESEARCH</sub><h3>3 papers</h3><sub>first author: quantum ML, quantization, agent security</sub></td>
    <td align="center"><sub>AMAZON ML CHALLENGE 2026</sub><h3>38th of 32,000+</h3><sub>team lead, invited to the Applied Scientist Intern interview</sub></td>
  </tr>
</table>

<p align="center"><sub>Also: Langfuse Security Hall of Fame · CodeChef 6★ (rating 2483, 4th in India) · LeetCode Guardian 2,720 · Microsoft AI-103 and DP-800 certified</sub></p>

## Featured projects

<table>
<tr>
<td width="50%" valign="top">

**[REFEREE](https://github.com/G26karthik/referee)**: claim verification for research papers<br>
`built at RamanIQ` `multi-agent` `Docker`

- Reads a paper, lists its main claims, runs a test for each in Docker and writes a reviewer page: Verified or Not verified, with the evidence.
- **~87% accuracy** on evals and tests, **185 kernel tests**, and **36K+ papers** screened to curate 380+ reproduction candidates.

</td>
<td width="50%" valign="top">

**[AlgoSentinel](https://github.com/G26karthik/algosentinel)**: autonomous PR auditor<br>
`agents` `Docker sandbox` `Gemini`

- Profiles the old and new version of every changed function in a sandbox and fits growth curves to catch **O(n) to O(n²)** regressions that tests miss.
- **55 tools across 4 namespaces**, subagent orchestration, **26 tests**, and an eval harness at **F1 1.00** on 5 golden cases.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[FounderOS](https://github.com/G26karthik/FounderOS)**: voice-first AI chief of staff<br>
`🥈 2nd prize` `Qdrant` `parallel agents` · [live demo](https://founder-os-pi-lemon.vercel.app/)

- Turns spoken thoughts into decisions, tasks and ideas with **5 Lyzr agents** (three extractors run in parallel) over **4 Qdrant memory collections**.
- Live in production with a privacy-first design: raw conversation stays private.

</td>
<td width="50%" valign="top">

**[Buy or Wait?](https://github.com/G26karthik/Buy-OR-Wait-Agentic-Decision-System)**: cash-flow decision engine<br>
`exact Decimal` `LLM perception` `independent verifier`

- Recommends pay, wait, installments or decline from a 90-day forecast. The LLM reads documents; exact-arithmetic code does the money.
- **318 tests across 18 suites**, with **233 of 250** decisions identical to an independent reference evaluator.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[Closer](https://github.com/G26karthik/Closer)**: deadline agent on Google ADK<br>
`planner` `evaluator loop` `human-in-the-loop`

- Turns a goal and deadline into finished work: draft emails, calendar blocks, research and documents, pausing only for real decisions.
- **58 tests**, a judge that grades each specialist's output with an automatic retry, and a scheduled monitor for closing deadlines.

</td>
<td width="50%" valign="top">

**[BizMatch](https://github.com/G26karthik/bizmatch-amazon-ml-2026)**: Amazon ML Challenge 2026<br>
`🏆 38th of 32,000+` `entity resolution` `team lead`

- Finds every real copy of a business across **~10M noisy records** and rejects look-alike decoys: e5 retrieval, a LightGBM cascade and cross-encoders.
- **0.921 to 0.990 F0.5** on free compute. [Engineering write-up](https://g26karthik.dev/writing/amazon-ml-challenge-2026/).

</td>
</tr>
</table>

<sub>More: [ParallaxOps](https://github.com/G26karthik/parallaxops) (3D reconstruction platform) · [Nishchay](https://github.com/G26karthik/Nishchay) (COD risk engine) · [WhatsApp Notification Router](https://github.com/G26karthik/whatsapp-notification-router) · [Grounded Support Triage](https://github.com/G26karthik/grounded-support-triage) · [Setu](https://github.com/G26karthik/Sethu-AI) (district health network) · [EdgeSentinel](https://github.com/G26karthik/EdgeSentinel) · [Avia](https://github.com/G26karthik/Avia) · [full list on the portfolio](https://g26karthik.dev/projects/)</sub>

## Research

| Paper | Status | Focus |
|---|---|---|
| [**QNC**](https://github.com/G26karthik/QNC): Geometry Conservation in Variational Quantum Classifiers | Springer *Quantum Machine Intelligence*, major revision | Training rotates states exactly (~10⁻¹⁵ relative change), checked on two IBM quantum backends, 52 preregistered predictions |
| Language-Aware Calibration and Bit Allocation for Low-Bit Quantization of Indic Language Models | RAIT 2027, under review | English-calibrated 3-bit GPTQ raises Indic bits per byte 2.05× vs 1.15× on English; balanced calibration cuts it to 1.38 |
| CANARYCODE: Benchmarking and Mitigating Sensitive-Data Leakage in LLM Coding Agents | DAI 2026, under revision | 786 completed runs across three open-weight models, eight output surfaces |

Also: [KVQuant Lab](https://github.com/G26karthik/kvquant-lab) (4.65× KV-cache compression at near-baseline perplexity) and [TraceWarrant](https://github.com/G26karthik/tracewarrant) (do your traces support your performance claims?).

## Experience

| Role | Where | What I did |
|---|---|---|
| **Applied AI Engineer Intern** | RamanIQ (AI startup) · Aug – Oct 2026 | **REFEREE**, an autonomous research-review product: multi-agent orchestration plus deterministic pipelines for paper analysis, experiment execution and evidence-backed verdicts, at **~87% accuracy on evals and tests**. Screened **36K+ papers** to curate 380+ reproduction candidates. **19+ PRs** shipping connectors, UI and backend features |
| **Tech Engineer, AI & Backend** | Hecta Proptech · Jun – Jul 2026 | CatBoost + GPU embeddings over **175K+ auction notices**: **84.3% ROC-AUC**, **80% less manual review**. A Cox survival model (**0.79 C-index**) behind a validated Flask API, and the first hybrid RAG platform. Features serving **5K+ users a day** |
| **Full Stack Engineer (sole)** | chkchk (stealth startup) · Jan – Apr 2026 | A creative-talent marketplace end to end on Next.js and Supabase: **−50% DB calls, −30% latency**, realtime, EC2 + CI/CD, and the Android app. **66 of 74 commits** |

## Open source

I started with small fixes and moved to the bigger libraries I use every day. In total that is **28 contributions: 25 merged pull requests across 19 projects, plus 3 fixes that maintainers landed themselves and credited me for** (Langfuse, PyTensor and PyMC). Langfuse also lists me in its Security Hall of Fame. [See the merged PRs](https://github.com/search?q=author%3AG26karthik+is%3Apr+is%3Amerged+-user%3AG26karthik+-org%3ADreamNation-EngineeringLabs+-user%3Acodexllama+-user%3Avinayrealai&type=pullrequests) <sub>(PyTorch lands PRs through its merge bot, so GitHub's filter shows one fewer.)</sub>

| Project | What I contributed | Status |
|---|---|---|
| [PyTorch](https://github.com/pytorch/pytorch/pull/199953) · 105K★ | `SGD` now rejects NaN `lr`, `momentum` and `weight_decay` instead of silently training on NaN, matching the other optimizers | ✅ Merged |
| [mem0](https://github.com/mem0ai/mem0/pull/3549) · 68K★ | The Azure AI Search vector store for the TypeScript SDK: hybrid search and quantization, **754 lines** | ✅ Merged |
| [Hindsight](https://github.com/vectorize-io/hindsight/pull/5092) · 58K★ | Fixed audit-log rows silently lost to garbage-collected write tasks and at shutdown | ✅ Merged |
| [pandas](https://github.com/pandas-dev/pandas/pulls?q=is%3Apr+author%3AG26karthik) · 50K★ | A PyArrow datetime-merge regression test, Ruff B905 enforcement, and a docstring migration | ✅ 3 Merged |
| [Langfuse](https://github.com/langfuse/langfuse/pull/14789) · 36K★ | Found a prompt-cache key collision (version `3` vs label `"3"` served each other's prompt) | 🚀 Shipped via [#15040](https://github.com/langfuse/langfuse/pull/15040) |
| [matplotlib](https://github.com/matplotlib/matplotlib/pull/30639) · 23K★ | Documented the TwoSlopeNorm linear-colorbar workaround | ✅ Merged |
| [sktime](https://github.com/sktime/sktime/pull/8923) · 10K★ | Fixed broken pytorch-forecasting references in the forecaster adapters | ✅ Merged |
| [SQLFluff](https://github.com/sqlfluff/sqlfluff/pull/7163) · 10K★ | A PostgreSQL `OPERATOR(schema.op)` parser, **649 lines** with fixtures | ✅ Merged |
| [HackerRank hiring-agent](https://github.com/interviewstreet/hiring-agent/pulls?q=is%3Apr+author%3AG26karthik) · 7.3K★ | Fixed a PyMuPDF memory leak and a Windows UTF-8 crash | ✅ 2 Merged |
| [authlib](https://github.com/authlib/authlib/pull/974) · 5.4K★ | OAuth endpoints now answer insecure-transport requests with a proper error response instead of raising | ✅ Merged |
| [PyTorch-Ignite](https://github.com/pytorch/ignite/pull/3876) · 4.8K★ | `ReduceLROnPlateauScheduler` now honours `min_lr` for every param group, not only the first | ✅ Merged |
| [NumPyro](https://github.com/pyro-ppl/numpyro/pulls?q=is%3Apr+author%3AG26karthik+is%3Amerged) · 2.8K★ | Hurdle distributions over positive bases now include zero in their support, and `init_to_mean` falls back to the median when the mean is not finite | ✅ 2 Merged |
| [QuTiP](https://github.com/qutip/qutip/pull/3049) · 2.1K★ | `rand_dm` and `rand_herm` no longer hang forever when all eigenvalues are equal | ✅ Merged |
| [sbi](https://github.com/sbi-dev/sbi/pull/2079) · 882★ | Corrected the mixture-density-network `log_prob` under structured z-scoring, and Sinkhorn now checks convergence on the marginals and warns when it fails | ✅ 2 Merged |
| [PyMC ecosystem](https://github.com/pymc-labs/pymc-marketing/pull/3206) · pymc-marketing, arviz-stats, pymc-extras | Moved pymc-marketing off a deprecated dataset call and fixed its notebook equations, kept the two largest integers in separate arviz-stats histogram bins, and traced a Windows-only Pathfinder test failure in pymc-extras to numba cache numerics | ✅ 4 Merged |
| [PyMC](https://github.com/pymc-devs/pymc/commit/5441c35f7726ce04736d5970dfbe68c167284e75) · [PyTensor](https://github.com/pymc-devs/pytensor/commit/2e1005b7ecb9b619a89829b81037420dbdac8fd5) | Diagnosed the wrong `ExGaussian` and `SkewStudentT` means and a Numba Cholesky compile failure on read-only inputs; the maintainers landed both fixes with me as co-author | ✅ 2 Co-authored |
| [qutip-qip](https://github.com/qutip/qutip-qip/pull/427) · [toqito](https://github.com/vprusso/toqito/pull/1989) | `Processor.run_state` no longer mutates the caller's collapse operators, and `kraus_to_choi` accepts wrapped completely-positive Kraus forms | ✅ 2 Merged |

## Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,ts,go,cpp,pytorch,fastapi,react,nextjs,postgres,docker,kubernetes,aws,git,linux&perline=14" alt="Languages, frameworks and infrastructure">
</p>
<p align="center"><sub>LLMs &amp; ML: OpenAI · Claude · Gemini · LangGraph · Hugging Face · LightGBM · CatBoost · XGBoost · scikit-learn · FAISS · BM25 · GPTQ · PennyLane</sub></p>

## Say hello

The quickest way to reach me is [email](mailto:karthikofficialmain@gmail.com) or [LinkedIn](https://www.linkedin.com/in/g-karthik26). My [portfolio](https://g26karthik.dev) has the longer write-ups, including the Amazon ML Challenge solution and the QNC case study.

<p align="center"><sub>My contribution graph, below, is being eaten by a snake. It is a bit slow, but it keeps going.</sub></p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/G26karthik/G26karthik/output/snake-dark.svg">
  <img alt="Contribution graph being eaten by a snake" src="https://raw.githubusercontent.com/G26karthik/G26karthik/output/snake.svg" width="100%">
</picture>
