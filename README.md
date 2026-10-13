# Natalie Buchbinder

ML engineer. Agentic LLM pipelines, Bayesian state estimation, survival analysis, and the backend systems that run them.

Previously founder of [Kaful](https://kaful.ai/): physics-based digital twins for industrial equipment, generated from OEM documentation.

[Portfolio](https://natalie-buchbinder.vercel.app) · [LinkedIn](https://www.linkedin.com/in/natalie-buchbinder/)

## Projects

**[Kaful agentic pipeline](https://buchbindern.github.io/kaful-showcase/)**: Seven-stage pipeline that compiles OEM manuals into executable physics-based digital twins (RAG + LLM extraction → simulation → Monte Carlo RUL). No historical failure data required. Run across four machine types. Presented at IWSM 2026.

**[kaful-data-twin](https://github.com/buchbindern/kaful-data-twin)**: Streaming CNC digital twin, deployed as a multi-tenant service. Particle filter estimates tool wear per cut from raw cutting-force data and forecasts RUL. FastAPI, session auth, per-tenant isolation, ~2× ingest throughput under concurrent load. Postgres + R2 on Render. **[Live demo](https://kaful-monitor.onrender.com)**

> Cross-tool RUL transfer fails in the *observation model* (wear → force), not the degradation rate. Isolated with a 2×2 study, reproducible from the repo.

**[SurvivalSimulation](https://github.com/buchbindern/SurvivalSimulation)**: Out-of-sample comparison of Cox PH, DeepSurv, RSF, and GBSA under varying censoring.

**[battery-rul-cnn](https://github.com/buchbindern/battery-rul-cnn)**: PyTorch CNN for lithium-ion battery RUL from single-cycle discharge data. R² ≈ 0.76 on held-out cells.

## Stack

`Python` · `PyTorch` · `FastAPI` · `PostgreSQL` · `TypeScript` · `Next.js`

Agentic LLM/RAG pipelines · particle filtering · survival analysis · streaming ingest and concurrency · multi-tenant services
