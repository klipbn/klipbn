# Alexey Voronko

**Lead Data Analyst — AdTech · Product Analytics · Analytics Engineering**

I turn recurring analytical problems into reusable products: Python libraries, SDKs, and production pipelines — with tests, monitoring, documentation, and adoption across teams.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-in%2Fklip--alex-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/klip-alex/)
[![Telegram](https://img.shields.io/badge/Telegram-@klipbn-26A5E4?style=flat-square&logo=telegram)](https://t.me/klipbn)
[![PyPI](https://img.shields.io/badge/PyPI-klipbn-3775A9?style=flat-square&logo=pypi&logoColor=white)](https://pypi.org/user/klipbn/)

---

## About

Lead Data Analyst at one of the largest tech companies in Eastern Europe, working on advertising technology. I own tasks end-to-end: framing the business problem, designing the methodology, running the research, and shipping the solution to production.

I've built **six Python libraries, SDKs, and internal services** for data access, experiment analysis, anomaly monitoring, and automation — used daily by analysts and engineers across multiple teams, including Data Engineering. I also grow people around me: onboarding, mentoring junior/middle analysts, running internal tech meetups, and bringing AI agents into everyday analytics work.

## Impact highlights

- **Anomaly monitoring platform** for advertising metrics: 7 statistical & ML detection methods, expected-value forecasting, deviation decomposition by product/segment, automated alerting. Scaled to **264 production scenarios** orchestrated as a generated **530-node workflow** with retries, backfill, and ownership routing.
- **A/B & A/B/C experimentation library**: statistical tests for different metric types, confidence intervals, MDE, power analysis, sample-size & duration planning, multiple-testing corrections, Excel reports and chat-ready summaries.
- **Python SDK for YTsaurus / YQL / ClickHouse** that became the team's standard way of working with data from Python and Jupyter — removes the 10K-row export limit, supports long-running queries, DataFrame writes, CLI mode, and access management. Used in **70+ scripts** in the team production repo; adopted and recommended by Data Engineering.
- **FastAPI/JDBC proxy** that makes YTsaurus CHYT look like a native ClickHouse endpoint — DBeaver, DataGrip and any standard SQL client just work, with a logical catalog over hundreds of tables.
- **Business sizing & incident analysis**: estimated a new ad product opportunity on a base of ~140K advertisers and ₽3.3B historical spend (≈ **₽29.5M incremental annual revenue** in the base scenario); built a methodology for monetary assessment of ad incidents, localizing residual losses of ₽0.9M in one case.
- **AI in analytics**: integrated AI coding agents and MCP-based tooling into the analytics team's workflows — data exploration, code review, documentation, and corporate systems.

## Open source

| Project | What it does | |
|---|---|---|
| [**anomaly_impact_alert**](https://github.com/klipbn/anomaly_impact_alert) | Anomaly detection, forecasting, deviation decomposition & Telegram alerts — Z-Score, STL, SESD, LOF, Isolation Forest, Prophet, ETS | [![PyPI](https://img.shields.io/pypi/v/anomaly_impact_alert.svg?style=flat-square)](https://pypi.org/project/anomaly_impact_alert/) |
| [**fast_exp_analytics**](https://github.com/klipbn/fast_exp_analytics) | Fast A/B and A/B/C experiment analytics: MDE, power, duration planning, reporting | [![PyPI](https://img.shields.io/pypi/v/fast-exp-analytics.svg?style=flat-square)](https://pypi.org/project/fast-exp-analytics/) |
| [**ytsaurus_python_client**](https://github.com/klipbn/ytsaurus_python_client) | Python client for YTsaurus, YQL and CHYT — large result sets to pandas, async queries, DataFrame uploads | [![PyPI](https://img.shields.io/pypi/v/ytsaurus_python_client.svg?style=flat-square)](https://pypi.org/project/ytsaurus_python_client/) |
| [**ytsaurus_clickhouse_proxy**](https://github.com/klipbn/ytsaurus_clickhouse_proxy) | FastAPI proxy that makes YTsaurus CHYT a native ClickHouse endpoint for DBeaver / DataGrip / JDBC | [![PyPI](https://img.shields.io/pypi/v/ytsaurus-clickhouse-proxy.svg?style=flat-square)](https://pypi.org/project/ytsaurus-clickhouse-proxy/) |
| [**bot_streams_sender**](https://github.com/klipbn/bot_streams_sender) | Stream Pulse — live-stream tracker across YouTube, Twitch, Kick & VK Video with anomaly detection and Telegram alerts every 2 minutes | Airflow · PostgreSQL |
| [**gym_online_checker**](https://github.com/klipbn/gym_online_checker) | Gym occupancy tracker — Selenium scraping, historical storage, interactive heatmaps to Telegram | Airflow · PostgreSQL |

## Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)
![YTsaurus](https://img.shields.io/badge/YTsaurus-4A90D9?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![scikit--learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![statsmodels](https://img.shields.io/badge/statsmodels-4B8BBE?style=flat-square)
![Prophet](https://img.shields.io/badge/Prophet-3B5998?style=flat-square)
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

## Currently into

AI agents & MCP integrations for analytics · experiment design at scale · data quality & observability · mentoring and building analytics engineering culture.

---

📬 Open to conversations about analytics, experimentation, and data tooling — **[Telegram](https://t.me/klipbn)** · **[LinkedIn](https://www.linkedin.com/in/klip-alex/)**
