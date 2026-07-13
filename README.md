# Hi, I'm Natalie

Applied ML engineer working on predictive maintenance and reliability — Bayesian state estimation and survival analysis, plus the systems that run them in production.

Founded [Kaful](https://kaful.ai/), building prognostic digital twins for industrial equipment. Open to hands-on engineering roles in industrial AI and manufacturing.

[Portfolio](https://natalie-buchbinder.vercel.app) · [LinkedIn](https://www.linkedin.com/in/natalie-buchbinder/)

## Projects

**[kaful-data-twin](https://github.com/buchbindern/kaful-data-twin)** — Streaming CNC digital twin, deployed as multi-tenant SaaS. Estimates tool wear cut-by-cut from raw cutting-force data with a particle filter and forecasts remaining useful life. Session auth, per-tenant isolation, concurrent ingest (~2× throughput, with the remaining ceilings documented). Postgres + R2 on Render. **[Live demo →](https://kaful-monitor.onrender.com)**

> Main finding: cross-tool RUL transfer fails because of the *observation model* — the wear→force map — not the degradation rate. Isolated with a 2×2 study, reproducible from the repo.

**[Kaful agentic pipeline](https://buchbindern.github.io/kaful-showcase/)** — Compiles OEM manuals into executable physics-based digital twins (RAG + LLM extraction → simulation → Monte Carlo RUL) with no historical failure data. Validated across four machines. Presented at IWSM 2026.

**[Battery_RUL_CNN](https://github.com/buchbindern/Battery_Rul_CNN)** — PyTorch CNN predicting lithium-ion battery RUL from single-cycle discharge data. R² ≈ 0.76 on held-out cells.

**[SurvivalSimulation](https://github.com/buchbindern/SurvivalSimulation)** — Out-of-sample comparison of survival models (Cox PH, DeepSurv, RSF, GBSA) under varying censoring.

## Tech

`Python` · `PyTorch` · `PostgreSQL` · `TypeScript` · `Next.js`

Particle filtering · survival analysis · agentic LLM/RAG pipelines · streaming ingest & concurrency · multi-tenant services
