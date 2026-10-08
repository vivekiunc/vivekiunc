## Hi, I'm Vivek

Computer Science and Business student at UNC Chapel Hill, building systems where software meets markets and the physical world. I work across quantitative research, ML infrastructure, and full-stack engineering.

- Quantitative research assistant studying crypto market microstructure, perpetual futures, and nlp methods for low-resource languages
- IBM Watson Scholar, and part of the team that placed 1st of 142 at the Carolina Data Challenge
- Currently focused on low-latency systems, data pipelines, and applied machine learning

### Featured projects

**Farmer Bot: Chatbot designed for farmers in low-resource languages(Marathi & Telugu) contexts in India**
Designed a RAG pipeline that lets farmers ask spoken agricultural questions in Marathi and Telugu and receive answers grounded in trusted agricultural documents and local context such as crop, season, region, and weather. The system uses Whisper for speech recognition, LangChain to orchestrate the pipeline, Azure OpenAI embeddings, and ChromaDB for retrieval. Moreover, the project evaluates how ASR errors and retrieval failures affect answer accuracy, with a fairness focus across dialects, accents, and background noise. Built as part of an independent study with UNC's Society-Centered AI Lab (SAIL).

**[hype](https://github.com/vivekiunc/hype): Oracle Latency and Rate-Limiting Arbitrage Research (HIP-3)**
A simulation framework for studying adversarial interactions between retail liquidity providers and HFT arbitrageurs exploiting oracle latency on Hyperliquid perpetual futures. Streams fills from the Hyperliquid API, aligns them against Binance reference prices, and stores synchronized price traces in PostgreSQL. Python, Binance API, Hyperliquid API, asyncio, psycopg2.

**[Tradfi-Perps-Collecter](https://github.com/vivekiunc/Tradfi-Perps-Collecter): TradFi perpetual-futures universe**
A data-collection pipeline that catalogues every TradFi-underlying perpetual future (single stocks, ETFs, commodities, FX, indices, pre-IPO) listed across crypto exchanges. Cross-checks ten direct exchange APIs against CoinMarketCap, drops venues flagged as unverified, and runs itself daily to produce an underlying-by-exchange volume matrix. Python, pandas.

**[cdc_2025](https://github.com/eshaanraj/cdc_2025): Space Economy Forecasting Dashboard**
Carolina Data Challenge team project (1st of 142 teams). A Streamlit dashboard that forecasts industry time series with Holt exponential smoothing and lets you explore projections by sector. Python, Streamlit, statsmodels.

### Currently building

**Trading Bot**: Building a gradient-boosted tree model for cross-sectional US equity return prediction. The model engineers factor-based features from the asset pricing literature, centered on momentum, liquidity, and volatility signals, then ranks stocks into a long-short portfolio. My focus is on honest validation, using purged and embargoed cross-validation along with realistic transaction costs, so the backtested results reflect a real edge rather than overfit noise.

### What I work on

- Market microstructure and quantitative research: perpetual futures, DeFi, execution
- Data pipelines and backend systems
- ML infrastructure and retrieval systems
- RAG Systems and end-to-end development

### Tech

- **Languages:** Python, Java, SQL
- **Data and ML:** pandas, NumPy, statsmodels, PostgreSQL, ChromaDB
- **Infrastructure:** Azure
- **Web:** React, Next.js, FastAPI

### Currently Learning
- **Languages:** C++
- **Frameworks:** LangChain

### Reach me

- Email: viveki@unc.edu
- LinkedIn: www.linkedin.com/in/vivek-indlamuri



<!--
Optional GitHub stats card. Uncomment to show live stats on your profile.
Uses the github-readme-stats service (anuraghazra/github-readme-stats).

![Vivek's GitHub stats](https://github-readme-stats.vercel.app/api?username=vivekiunc&show_icons=true&hide_border=true)
-->
