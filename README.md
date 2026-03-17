<h1 align="center">hi, I'm Gaurav ^.^</h1>
<p align="center">third year at NIT Delhi, studying AI & Data Science</p>

---

I like building things that actually run — not just things that work in a notebook at 2am and break the moment someone else touches them.

my interests sit somewhere in the overlap of backend engineering, ML systems, and quantitative finance. that overlap is a weird place to be, but it means I get to think about low-latency APIs *and* Sharpe ratios *and* whether my training pipeline will still be reproducible six months from now. I find all three genuinely interesting, which probably says something about me.

---

![](https://img.shields.io/badge/-lately%20I've%20been%20spending%20time%20on-EF4565?style=for-the-badge)

**streaming data** — built a Kafka + Spark pipeline that processes 50K+ events/min and serves analytical queries over 6M+ records in under 400ms. the interesting part wasn't the throughput — it was figuring out why ClickHouse's columnar storage makes that kind of latency possible in the first place.

**quant stuff** — [Nifty-Quant](https://github.com/raogaurav17/Nifty-Quant) is my most recent project. cross-sectional momentum strategies on NIFTY 50, with realistic transaction costs and volatility-based sizing. backtesting is easy to do badly (lookahead bias, survivorship bias, ignoring slippage) — I spent more time getting that right than on the strategy itself.

**LLM agents that aren't toys** — [CiteRAG](https://github.com/raogaurav17/CiteRAG) exists because I got annoyed at RAG demos that skip reranking and citation grounding. [Financial-ai-agent](https://github.com/raogaurav17/Financial-ai-agent) combines LangGraph with actual statistical forecasting (ARIMA + Monte Carlo) instead of just asking an LLM to guess about markets.

**MLOps** — built [RetainStack](https://github.com/raogaurav17/RetainStack) partly to understand what "production ML" actually means beyond saving a `.pkl` file. DVC, GitHub Actions, Azure — the boring stuff that makes the difference between a model that ships once and a model that keeps working.

**Rust** — slowly. built [PyRustKV](https://github.com/raogaurav17/PyRustKV) as an in-memory KV store after getting frustrated with Python's GIL in a hot path. I don't fully understand the borrow checker yet but I'm getting there.

---

![](https://img.shields.io/badge/-tools%20that%20show%20up%20a%20lot-2CB67D?style=for-the-badge)

### Languages
<div style="display: flex; flex-wrap: wrap; gap: 10px;">
<img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue" />
<img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
<img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" />
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
</div>

### ML & Deep Learning
<div style="display: flex; flex-wrap: wrap; gap: 10px;">
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
<img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
</div>

### LLM & Agents
<div style="display: flex; flex-wrap: wrap; gap: 10px;">
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/Google%20Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" />
</div>

### MLOps & DevOps
<div style="display: flex; flex-wrap: wrap; gap: 10px;">
<img src="https://img.shields.io/badge/Docker-0db7ed?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/DVC-945DD6?style=for-the-badge&logo=dvc&logoColor=white" />
<img src="https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub%20Actions-000000?style=for-the-badge&logo=githubactions&logoColor=white" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
</div>

### Data Engineering
<div style="display: flex; flex-wrap: wrap; gap: 10px;">
<img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" />
<img src="https://img.shields.io/badge/Apache%20Spark-FDEE21?style=for-the-badge&logo=apachespark&logoColor=E25A1C" />
<img src="https://img.shields.io/badge/ClickHouse-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=black" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
</div>

### Cloud & Infra
<div style="display: flex; flex-wrap: wrap; gap: 10px;">
<img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" />
<img src="https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
</div>

these change depending on the project, but these are the ones I reach for most often.

---

![](https://img.shields.io/badge/-things%20I've%20been%20building-3A86FF?style=for-the-badge)

### [Nifty-Quant](https://github.com/raogaurav17/Nifty-Quant)
Quantitative backtesting platform for Indian equity markets. Cross-sectional momentum on NIFTY 50, volatility-based position sizing, realistic transaction costs. I spent more time getting the backtesting methodology right (no lookahead bias, proper slippage) than on the strategy itself.

### [WebStream-Analytics](https://github.com/raogaurav17/WebStream-Analytics)
Kafka → Spark Structured Streaming → ClickHouse → React dashboard. 50K+ events/min, sub-400ms queries over 6M+ records. Built this to understand what "real-time" actually costs at the infrastructure level.

### [Financial-ai-agent](https://github.com/raogaurav17/Financial-ai-agent)
LLM agent (LangGraph + Gemini) for financial analysis. ARIMA 30-day forecasting at 12.6% MAPE, Monte Carlo simulations (10K runs) for portfolio risk, Sharpe-optimized allocation that beat equal-weight baselines by 18–24%. The interesting constraint was making the LLM use actual statistical outputs instead of vibes.

### [CiteRAG](https://github.com/raogaurav17/CiteRAG)
Production-grade RAG with vector search, reranking, and inline citations. Built because I kept seeing RAG demos that skip the parts that actually matter — grounding and attribution.

### [RetainStack](https://github.com/raogaurav17/RetainStack)
An experiment in turning ML workflows into something closer to production engineering. Reproducible training, automated checks, versioned data, deployment pipelines that don't fall apart. 89% F1, 40% faster deployment cycles than a notebook-based baseline.

### [PyRustKV](https://github.com/raogaurav17/PyRustKV)
In-memory key-value store via FastAPI. Started as a Redis-lite experiment after hitting Python's GIL in a hot path. Ended up being useful for ML inference caching.

### [DiabeticRetinopathyClassifier](https://github.com/raogaurav17/DiabeticRetinopathyClassifier)
Swin Transformer trained on EyePACS retinal images. The fun part wasn't the model — it was wiring everything into a full-stack app: Flask inference server paired with a React interface.

### [anime_face_generator_wgangp](https://github.com/raogaurav17/anime_face_generator_wgangp)
A generative model trained for 256×256 image synthesis. This project taught me more about debugging model instability than about generating anime faces — which is probably the real lesson.

---

![](https://img.shields.io/badge/-other%20stuff-FFB627?style=for-the-badge)

I've solved 500+ DSA problems, usually late at night when I should be doing something else. Ranked 9th in AlgoUniversity's graph competition.

I built a 3-node Spark cluster inside Docker with custom bridge networking just to see how the scheduling actually works. it was slower than I expected and I learned a lot.

CGPA 8.04 at NIT Delhi.

---

![](https://img.shields.io/badge/-find%20me-E53170?style=for-the-badge)

**Email:** gauravrao177@gmail.com &nbsp;·&nbsp; **LinkedIn:** [ydv17gaurav](https://www.linkedin.com/in/ydv17gaurav)

if you stumble across something interesting in my repos, feel free to open an issue or drop a message.
