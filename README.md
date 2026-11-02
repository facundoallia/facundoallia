<div align="center">

# Facundo Allia Fernandez

**Data Scientist. AI and Data Engineer. Quant background.**

I build AI systems, data pipelines and quantitative models that run in production: LLM pipelines with human review and evaluation, ETL workflows, forecasting and machine learning models, and derivatives pricing. My work sits where data engineering, AI and finance meet. Based in Madrid.

[![Portfolio](https://img.shields.io/badge/Portfolio-facundoallia.github.io-0E1621?style=for-the-badge&logo=googlechrome&logoColor=white)](https://facundoallia.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge)](https://www.linkedin.com/in/facundoalliafernandez/)
[![Medium](https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@facujallia)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/facundoallia)
[![Schedule a meeting](https://img.shields.io/badge/Schedule%20a%20meeting-006BFF?style=for-the-badge&logo=calendly&logoColor=white)](https://calendly.com/facujallia/reunion)

</div>

## Selected projects

<table>
<tr>
<td width="50%" valign="top">
<a href="https://www.linkedin.com/feed/update/urn:li:activity:7234669321493377024/"><img src="https://facundoallia.github.io/assets/img/work/screener-demo.webp" alt="Screener scanning markets and sending signals with charts to Telegram"></a>
<br><b>Multi-market signal engine with automated Telegram alerts</b>
<br>Desktop application built for a client. It scans European and US indices on moving averages and ADX, then sends each signal with its chart to Telegram.
<br><a href="https://www.linkedin.com/feed/update/urn:li:activity:7234669321493377024/">Watch the demo</a>
</td>
<td width="50%" valign="top">
<a href="https://github.com/facundoallia/calendar-spread-time-series-forecasting"><img src="https://facundoallia.github.io/assets/img/work/calendar-spread.webp" alt="Forecast of a corn futures calendar spread with confidence band"></a>
<br><b>Time series forecasting of futures calendar spreads with Prophet</b>
<br>Reusable analyzer for corn, soybean and wheat spreads on Matba Rofex: builds contract pairs from price history since 2010 and forecasts the differential.
<br><a href="https://github.com/facundoallia/calendar-spread-time-series-forecasting">Code</a> · <a href="https://medium.com/@facujallia/unleashing-the-power-of-time-series-forecasting-in-calendar-spread-strategies-an-application-in-2">Article</a>
</td>
</tr>
</table>

| Project | What it does | Links |
|---|---|---|
| **Production LLM pipeline for financial research** | Runs on a daily schedule: ingests broker research from WhatsApp, turns it into structured notes with Claude, adds market charts, requests approval on Telegram and publishes to WhatsApp, Telegram and Instagram. | Private code |
| **Market-implied inflation and FX engine** | Fisher decomposition across fixed, inflation-linked and dollar-linked Treasury curves, with forward rates and a monthly path. Tested analytics core and live market data. | [App](https://logos-breakeven.vercel.app) · [Code](https://github.com/facundoallia/logos-breakeven) |
| **ETL pipeline and public REST API for central bank forecasts** | Downloads the BCRA market expectations survey every month, parses it and serves it from Cloudflare Workers. | [API](https://bcra-rem-api.facujallia.workers.dev) · [Code](https://github.com/facundoallia/rem-bcra-api) |
| **Multi-indicator trading signal screener** | Aggregates buy and sell readings from TradingView indicators across a universe of instruments, then filters them to surface trade candidates. My most starred open-source project. | [Code](https://github.com/facundoallia/Trading-Screener-with-Python-and-Tradingview) · [Article](https://medium.com/@facujallia/building-an-effective-trading-screener-with-python-and-tradingview-9329db9afaa9) |
| **Unsupervised clustering of S&P 500 stocks** | Groups the index by risk and return, then by valuation and dividends, to support portfolio diversification. Published as a UCEMA paper. | [Code](https://github.com/facundoallia/Stock-classification-using-k-means-clustering) · [Article](https://medium.com/@facujallia/stock-classification-using-k-means-clustering-8441f75363de) |
| **Social media impact on crypto volatility** | Crosses hourly DOGE/USDT data with Elon Musk's tweets, using sentiment polarity and OLS with ANOVA to test the effect on returns and volatility. | [Code](https://github.com/facundoallia/Exploring-the-Relationship-between-Elon-Musk-s-Tweets-and-Dogecoin-Volatility-with-NLP-and-Econometr) |

More projects, with previews, on the [portfolio](https://facundoallia.github.io/#projects).

## Stack

**AI**
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white)
![LLMs](https://img.shields.io/badge/LLMs-412991?style=flat-square)
![Agents](https://img.shields.io/badge/Agents-412991?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-412991?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white)
![LLM evaluation](https://img.shields.io/badge/LLM%20evaluation-412991?style=flat-square)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)

**Data engineering**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare%20Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white)

**Data science**
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat-square)
![Prophet](https://img.shields.io/badge/Prophet-0467DF?style=flat-square&logo=meta&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square)

**Applications**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

**Quant and markets**
![Monte Carlo](https://img.shields.io/badge/Monte%20Carlo-1F4E79?style=flat-square)
![Stochastic models](https://img.shields.io/badge/Stochastic%20models-1F4E79?style=flat-square)
![XVA](https://img.shields.io/badge/XVA-1F4E79?style=flat-square)
![Backtesting](https://img.shields.io/badge/Backtesting-1F4E79?style=flat-square)
![Bloomberg](https://img.shields.io/badge/Bloomberg-000000?style=flat-square)
![Reuters](https://img.shields.io/badge/Reuters-FF8000?style=flat-square)
![Murex](https://img.shields.io/badge/Murex-1F4E79?style=flat-square)
![TradingView](https://img.shields.io/badge/TradingView-131722?style=flat-square&logo=tradingview&logoColor=white)

## Experience

| Years | Role | Company |
|---|---|---|
| 2025 to now | Senior Data Scientist & Automation Engineer, AI Ambassador | Banco Santander CIB |
| 2024 to 2025 | Quantitative Analyst | PwC |
| 2022 to 2023 | Financial Data Transition Specialist | Accenture |
| 2022 | Data Scientist | Nixtla |
| 2021 to 2023 | Institutional Derivatives Trader, Market Making | Matba Rofex |
| 2020 to now | Financial Advisor & Founder | [Logos Servicios Financieros](https://logos-serviciosfinancieros.com.ar) |

## Publications

- [Construction of risk-neutral probability density functions through butterfly spreads](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4280119). BCR, 2022.
- [Stock classification using k-means clustering](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4403662). UCEMA, 2022.

## Education

- Postgraduate in Quantitative Systems and Models for Algorithmic Trading, Universidad Politécnica de Madrid (2027)
- Master's in Finance, EAE Business School Madrid (2024)
- Postgraduate Degree in Quantitative Finance, UCEMA (2022)
- Data Science Bootcamp (700+ hours), Henry (2022)
- Bachelor of Business Administration, Finance, Universidad Nacional de Córdoba (2020)

<div align="center">

[facujallia@gmail.com](mailto:facujallia@gmail.com) · [Portfolio](https://facundoallia.github.io) · [Download CV](https://facundoallia.github.io/assets/docs/Facundo_Allia_CV.pdf)

</div>
