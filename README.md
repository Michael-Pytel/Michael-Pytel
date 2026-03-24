# Michał Pytel — Data Science & ML Engineer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-michael--g--pytel-blue)](https://www.linkedin.com/in/michael-g-pytel)
[![Kaggle](https://img.shields.io/badge/Kaggle-michalpytel-20beff)](https://www.kaggle.com/michalpytel)

M.Sc. Data Science student at the Faculty of Mathematics and Information Science, Warsaw
University of Technology (MiNI PW). 2 x Hackathon winner. AI expert featured on TVP3 Warszawa.

My work spans ML pipelines, computer vision, LLMs, and full-stack data applications.

I build end-to-end data solutions — combining rigorous mathematical foundations with modern AI to turn complex, messy problems into something that actually works.

---

## Highlights

- 🥇 **HackNation 2025** — 1st place (JSW IT Systems challenge: conveyor belt defect
  detection with SAM/MobileSAM; codebase transferred to the company)
- 🥇 **HackCarpatia 2025** — 1st place (LOT Airlines challenge: day prior email layout
  optimization with custom-loss neural networks & XGBoost)
- 📺 Featured as an **AI expert on TVP3** national television

---

## Featured Projects

### 🏋️ [PosePro Coach](https://github.com/Michael-Pytel/PosePro-Coach)
*B.Sc. Thesis — Django web app for automated push-up technique assessment*

MediaPipe pose estimation → 77 biomechanical features → Random Forest / XGBoost / SVM
classifiers with GroupKFold cross-validation. Assesses hip position, head alignment, and
range of motion in real time.

`Django` `MediaPipe` `scikit-learn` `Python` 

---

### 📈 [Stock Exchange App](https://github.com/Michael-Pytel/Stock-Exchange)
*Full-stack trading simulator with ML forecasting and RL agent*

Real market data, AutoGluon TimeSeriesPredictor for forecasting, and a PPO reinforcement
learning trading bot (Stable-Baselines3) trained on 9 US stocks. Features RSI charts,
equity curves, and a redesigned dashboard.

`Django` `AutoGluon` `Stable-Baselines3` `AI Agents` `Python` `Stock Forecasting`

---

### 🔍 [arXiv RAG](https://github.com/Michael-Pytel/arxiv-rag)
*Semantic search & RAG over ~288k AI/ML papers*

Qdrant vector database + OpenAI embeddings + Claude as LLM. FastAPI backend with a
single-page HTML frontend for natural-language paper discovery.

`FastAPI` `Qdrant` `OpenAI` `Claude` `RAG` `Python`

---

### 📡 [Big Data ETF–Crypto Arbitrage Detection](https://github.com/Michael-Pytel/Arbitrage-Detector)
*Lambda Architecture for real-time arbitrage signal detection*

Apache NiFi → Kafka → Spark Streaming → HDFS / Hive / HBase pipeline. WebSocket
feeds from Alpaca Markets and Binance.

`Apache Kafka` `Spark` `NiFi` `HBase` `Hive` `Avro`

---

### ⚡ [Energy & Weather Data Warehouse](https://github.com/Michael-Pytel/Data-Warehouse-Energy-Weather)
*End-to-end data warehouse integrating EU energy and climate data*

Python ETL pipeline ingesting data from ENTSO-E, Open-Meteo, and Eurostat across all
27 EU countries into a SQL Server star schema. Power BI dashboards surface energy
consumption trends, renewable generation, and weather correlations.

`Python` `SQL Server` `ETL` `Star Schema` `Power BI` `ENTSO-E API` `Open-Meteo API`

---

### 🏦 [AuctionApp](https://github.com/Michael-Pytel/AuctionApp)
*Production-ready Django auction platform on GCP*

Full infrastructure: Nginx + Gunicorn + Cloud SQL PostgreSQL + Secret Manager +
SendGrid. Automated daily backups and systemd process management.

`Django` `GCP` `PostgreSQL` `Nginx` `Python`

---

### 🧠 [Theory of Mind LLM](https://github.com/Michael-Pytel/Theory-Of-Mind-LLM)
*Benchmarking false-belief reasoning in Claude, DeepSeek, and Llama*

Cross-lingual evaluation (EN / PL / DE) of ToM capabilities across simple and
second-order belief scenarios.

`Anthropic API` `LLM Evaluation` `Python`

---



## 🧠 Technical Skills

### Mathematics & Statistics
- **Linear Algebra**: SVD, eigendecomposition, matrix factorizations (QR, LU), orthogonal projections
- **Probability & Statistics**: MLE, hypothesis testing, confidence intervals, bootstrap/jackknife, Bayesian estimation
- **Statistical Modelling**: OLS/WLS, Ridge, Lasso, PCR, logistic/probit regression, GLMs
- **Time Series**: AR, MA, ARMA, spectral analysis, non-stationary process decomposition
- **Optimisation**: Gradient descent, Newton/quasi-Newton methods, KKT conditions, convex optimisation, LP/SQP
- **Stochastic Processes**: Markov chains, Poisson processes, Gaussian processes, Metropolis-Hastings

### Machine Learning & AI
- **Classical ML**: k-NN, Naive Bayes, LDA/QDA, SVM, Decision Trees, Random Forest, XGBoost
- **Unsupervised**: k-means, hierarchical clustering, PCA, multidimensional scaling
- **Deep Learning**: Neural networks, SGD, backpropagation, overfitting detection
- **Reinforcement Learning**: PPO (Stable-Baselines3), reward shaping
- **LLMs & RAG**: Prompt engineering, Anthropic API, OpenAI API, vector search (Qdrant), RAG pipelines
- **Computer Vision**: MediaPipe, OpenCV, SAM/MobileSAM, pose estimation

### Data Engineering & Databases
- **SQL**: Advanced queries, stored procedures, query optimisation, indexing — PostgreSQL, SQL Server, Oracle, BigQuery
- **Big Data**: Apache Kafka, Spark (batch & streaming), Hadoop, NiFi, HDFS, Hive, HBase
- **Cloud**: GCP (BigQuery, Compute Engine, Cloud SQL, Secret Manager)
- **Architectures**: Lambda, Kappa, ETL/ELT, star schema, dimensional modelling, OLAP
- **BI Tools**: Power BI, Qlik Sense, Looker Studio

### Programming Languages
- **Python** — primary (numpy, pandas, scikit-learn, PyTorch, FastAPI, Django)
- **R** — data wrangling, ggplot2, Shiny, statistical modelling
- **SQL** — PostgreSQL, SQL Server, BigQuery, Oracle
- **Java** — OOP, concurrency, design patterns
- **Bash** — scripting, automation

### MLOps & Tools
- **Experiment tracking & pipelines**: AutoGluon, GroupKFold CV, threshold optimisation
- **Web frameworks**: Django, FastAPI, Eleventy
- **DevOps**: Docker, Nginx, Gunicorn, Linux/Unix, Git
- **Visualisation**: matplotlib, seaborn, Plotly, Chart.js, ggplot2, Shiny, Power BI

---

*Open to DS/ML internship and junior roles. Feel free to reach out!*
