## Hi, I'm Chris

Senior software and data engineer based in Gdańsk, 5+ years building things in Python that run in production.

My work sits at the intersection of data engineering and AI systems — production data platforms on GCP, autonomous LLM-agent pipelines, and the backend infrastructure that ties them together. I care about correctness, testability, and shipping things that don't need babysitting.

Recent highlights:
- Built an autonomous agent platform at Morele.net handling 5,000+ weekly customer cases, automating 70%+ of complaint resolution end-to-end
- Drove dbt test coverage from ~22% to ~97% across a production catalogue serving financial reporting for a 260M+ booking marketplace
- Designed and shipped invoicing automation saving ~4 h/day of manual work; PySpark demand forecasting pipelines across ~500k SKUs per client

**Data & infra:** Python · SQL · dbt · Airflow · PySpark · BigQuery · GCP · Terraform · Docker · Postgres  
**AI & automation:** Claude/OpenAI APIs · autonomous agents · LangGraph · LangChain · structured outputs & validators · eval harnesses · Selenium  
**Engineering:** CI/CD · TDD · Git · FastAPI · REST APIs · scikit-learn

---

**Projects**

**ai-trading-signals** *(private)* — LLM equity-research pipeline over US-listed companies. Point-in-time ingestion of SEC filings and earnings calls, LangGraph dossier and debate graphs, and falsifiable theses graded against a forecast ledger when they resolve. Every claim is span-cited, and a model-backed validator makes the system incapable of emitting a buy, sell or price target.  
**quant-llm-fund** *(private)* — the numeric half of the same system, kept deliberately separate: LightGBM cross-sectional ranker, Black–Litterman allocation via skfolio, point-in-time S&P 500 membership reconstructed back to 1996, walk-forward backtest with ablation gating. Serves the research pipeline over HTTP behind shared Pydantic contracts.  
[AirQualityDataHandler](https://github.com/kbrudnowski/AirQualityDataHandler) — air quality data pipeline on GCP (OpenAQ API → Cloud Function → Cloud Storage)  
[WedApp](https://github.com/kbrudnowski/WedApp) — wedding guest media uploader on Cloudflare Pages + D1 + Google Drive, offline-resilient upload queue  
[ebitda-scrapper](https://github.com/kbrudnowski/ebitda-scrapper) — financial data scraper

The private repos and most of my production work are proprietary — happy to walk through any of it.

---

krzysztof.brudnowski@gmail.com
