# Michał Pytel — Data Scientist

[![LinkedIn](https://img.shields.io/badge/LinkedIn-michael--g--pytel-blue)](https://www.linkedin.com/in/michael-g-pytel)
[![Kaggle](https://img.shields.io/badge/Kaggle-michalpytel-20beff)](https://www.kaggle.com/michalpytel)

M.Sc. Business Analytics student at the Technical University of Denmark (DTU), Copenhagen. Three-time national hackathon winner (HackNation 2025; HackCarpatia 2025 & 2026)

I'm a data scientist — I build models that assess, predict, and make sense of messy real-world data, from biomechanics to financial signals. I care about framing the right problem, engineering features that mean something, and validating that a model holds up beyond the data it was trained on.

More recently I've moved into **optimization and analytics for logistics, supply chains, and marketing** — turning those models into decisions about routes, allocations, and operations.

---

## What I Do

- **Build models that assess and predict.** From subjective judgements to time-series signals, I turn raw, messy data into something that classifies, scores, or forecasts — and that I can trust on examples it has never seen.
- **Frame the problem before reaching for tools.** I start from the question that needs answering and work backwards to the method, rather than fitting a model to data and hoping it's useful.
- **Validate against reality.** Distribution-shift diagnostics, principled cross-validation, and honest stress-testing — because a model that looks good on paper but fails on new data is worse than none.
- **Lately: optimization & operations analytics.** Translating models into decisions for logistics, supply chains, and marketing — objective design, constraint modelling, and routing.

---

## Featured Projects

### 🏋️ [PosePro Coach](https://github.com/Michael-Pytel/PosePro) — B.Sc. Thesis
An end-to-end pipeline that turns raw movement into a graded technique assessment: framing a subjective judgement ("is this push-up good form?") as a supervised problem, engineering ~77 biomechanical features from pose data, and validating with subject-grouped cross-validation so the model generalizes to *people it has never seen* — not just unseen frames.

`Problem framing` `Feature engineering` `Robust validation` `Python`

### 🧠 [Theory of Mind LLM](https://github.com/Michael-Pytel/Theory-Of-Mind-LLM)
A cross-lingual benchmark probing false-belief reasoning in modern LLMs across English, Polish, and German. Designed to expose where models are *confidently wrong* on second-order reasoning — the failure mode that matters most when systems are trusted with judgement.

`Evaluation design` `LLM benchmarking` `Cross-lingual analysis`

### 📡 [ETF–Crypto Arbitrage Detection](https://github.com/Michael-Pytel/Arbitrage-Detector)
Real-time detection of fleeting arbitrage signals across equity and crypto markets. The hard part isn't the pipeline — it's reasoning about latency, windowing, and what counts as a genuine, actionable signal versus noise in a streaming setting.

`Streaming analytics` `Signal detection` `Real-time systems`

### ⚡ [Energy & Weather Data Warehouse](https://github.com/Michael-Pytel/Data-Warehouse-Energy-Weather)
Integrating energy, climate, and economic data across all 27 EU countries into one analytical model, then surfacing the correlations that explain consumption and renewable-generation patterns. A study in making heterogeneous public data answer questions it was never structured to answer.

`Data modelling` `Integration` `Analytical reporting`

---

## Technical Foundation

**Optimization** — convex optimization, gradient & quasi-Newton methods (L-BFGS), trust-region and subgradient methods, KKT/duality, LP/SQP, objective design with cost penalties.

**Modelling & Statistics** — regression and GLMs, time-series (AR/ARMA, regime-switching), MLE and Bayesian estimation, distribution-shift diagnostics, principled cross-validation.

**Machine Learning** — gradient boosting, SVMs, ensembles, clustering, reinforcement learning (PPO), and LLM evaluation & RAG.

**Engineering** — Python (numpy, pandas, scikit-learn, PyTorch, FastAPI), R, SQL, and Rust; streaming and batch data pipelines; cloud deployment on GCP.

---

*Open to roles in data science, optimization, and operations analytics. Previously featured as an AI guest on TVP3 Warszawa. Always happy to talk through a hard problem — reach out.*
