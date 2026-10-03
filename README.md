# Alexey Voronko

**Lead Data Analyst · AdTech · Experimentation · Analytics Engineering**

I own analytics problems end to end: framing the business question, designing the methodology, and shipping the result as a production tool instead of a one-off report. At one of the largest tech companies in Eastern Europe I have built six Python libraries, SDKs, and services that analysts and engineers from several teams now run in their own pipelines.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-in%2Fklip--alex-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/klip-alex/)
[![Telegram](https://img.shields.io/badge/Telegram-@klipbn-26A5E4?style=flat-square&logo=telegram)](https://t.me/klipbn)
[![PyPI](https://img.shields.io/badge/PyPI-klipbn-3775A9?style=flat-square&logo=pypi&logoColor=white)](https://pypi.org/user/klipbn/)

## Open source

| Project | What it does | |
|---|---|---|
| [**fast_exp_analytics**](https://github.com/klipbn/fast_exp_analytics) | A/B and A/B/C experiment analytics: significance tests, MDE, power analysis, duration planning, Excel reports, chat-ready summaries | [![PyPI](https://img.shields.io/pypi/v/fast-exp-analytics.svg?style=flat-square)](https://pypi.org/project/fast-exp-analytics/) |
| [**anomaly_impact_alert**](https://github.com/klipbn/anomaly_impact_alert) | Anomaly detection, forecasting, deviation decomposition, Telegram alerts. Z-Score, STL, SESD, LOF, Isolation Forest, Prophet, ETS. Colab demo included | [![PyPI](https://img.shields.io/pypi/v/anomaly_impact_alert.svg?style=flat-square)](https://pypi.org/project/anomaly_impact_alert/) |
| [**ytsaurus_python_client**](https://github.com/klipbn/ytsaurus_python_client) | Python client for YTsaurus, YQL, and CHYT: large results into pandas, async long-running queries, DataFrame uploads | [![PyPI](https://img.shields.io/pypi/v/ytsaurus_python_client.svg?style=flat-square)](https://pypi.org/project/ytsaurus_python_client/) |
| [**ytsaurus_clickhouse_proxy**](https://github.com/klipbn/ytsaurus_clickhouse_proxy) | FastAPI proxy that exposes YTsaurus CHYT as a ClickHouse endpoint, so DBeaver and DataGrip connect over JDBC with a logical table catalog | [![PyPI](https://img.shields.io/pypi/v/ytsaurus-clickhouse-proxy.svg?style=flat-square)](https://pypi.org/project/ytsaurus-clickhouse-proxy/) |
| [**streamlens**](https://github.com/klipbn/streamlens) | Live streams in one auto-updating Telegram message: viewers, trends and a slideshow of frames for YouTube, Twitch and Kick. Bring your own data or let it watch channels; no database, CLI and Docker included | [![PyPI](https://img.shields.io/pypi/v/streamlens.svg?style=flat-square)](https://pypi.org/project/streamlens/) |
| [**KlipRun**](https://github.com/klipbn/kliprun) | Local, read-only Kanban dashboard for active OpenCode TUI sessions, with live status updates and session details | |

Also: [bot_streams_sender](https://github.com/klipbn/bot_streams_sender) (the original Airflow + Postgres live-stream tracker with anomaly detection) · [gym_online_checker](https://github.com/klipbn/gym_online_checker) (gym occupancy heatmaps to Telegram).

## Professional impact

- Built an anomaly monitoring platform for advertising metrics: 7 statistical and ML detectors, expected-value forecasting, deviation decomposition by product and segment, automated alerts to responsible analysts. Scaled it to **264 production scenarios** orchestrated as a generated **530-node workflow** with retries, backfill, and ownership routing.
- Created an internal experimentation library for A/B and A/B/C tests: statistical tests for different metric types, confidence intervals, MDE, power analysis, duration planning, multiple-testing corrections, automated reporting. Moved regular experiment analysis from notebooks to production pipelines.
- Developed a data access SDK for YTsaurus / YQL / ClickHouse, used in **70+ production scripts** and by analysts across several teams; recommended in Data Engineering channels. Set up Data Quality monitoring for analytical tables: freshness, missing partitions, volume deviations.

Estimated new ad product opportunities with scenario models (adoption, budget redistribution, cannibalization); the results defined the MVP segment and validation criteria.

## Team and leadership

- Mentor junior and middle analysts, run onboarding, and hold a weekly technical interview section.
- Run internal meetups and workshops: product analytics, mobile attribution, Git, Python packaging, CLI tools, AI agents.
- Brought AI coding agents and MCP integrations into the team's workflow: data exploration, code review, documentation, corporate systems.

## Core stack

Python · SQL (ClickHouse, YQL, Postgres) · YTsaurus · pandas, SciPy, statsmodels, scikit-learn, Prophet · Airflow · FastAPI · Docker · GitLab CI · pytest · Superset, Jupyter

---

📬 Open to conversations about analytics, experimentation, and data tooling: [Telegram](https://t.me/klipbn) · [LinkedIn](https://www.linkedin.com/in/klip-alex/)
