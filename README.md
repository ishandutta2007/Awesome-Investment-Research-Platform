# Awesome-Investment-Research-Platform

## Top Investment Research Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Market Intelligence, SEC Filings Analysis, Expert Transcripts, Financial Data, Equity Research & AI-Powered Search*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Investment Research**. These tools help analysts, portfolio managers, and investors search filings, transcripts, broker research, news, and financial data to generate insights and support investment decisions.

**Examples** include AlphaSense, Sentieo, Visible Alpha, Koyfin, Tegus, BamSEC, Capital IQ Pro, PitchBook, Mosaic Smart Data, and Yewno (the category leaders).

**Open-source emphasis**: While premium content (broker research, expert calls, proprietary datasets) remains largely commercial, excellent open-source tools exist for SEC EDGAR access, filing analysis, RAG-based research assistants, 13F tracking, and financial data pipelines. This section is expanded with every major active project.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform | Description | Starting Tier Pricing | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- |
| **[AlphaSense](https://www.alpha-sense.com/)** | AI-powered market intelligence & search covering SEC filings, transcripts, broker research, expert calls, and news. | Starts at ~$10,000 – $20,000/seat/yr (Core enterprise tier; quotes scale with expert call & broker add-ons) | **14-day free trial** upon demo/sales request; full document search & AI summaries (export/download caps apply, no permanent free tier) |
| **[Sentieo](https://www.sentieo.com/)** | Financial search engine, filing analysis, and research notebook workspace (integrated into AlphaSense platform). | Starts at ~$10,000/seat/yr (Sold via AlphaSense enterprise subscriptions) | **14-day free trial** upon sales request; access to document search and notebook features (no permanent free tier) |
| **[Visible Alpha](https://visiblealpha.com/)** | Consensus forecasts, detailed financial estimates, and standardized operating metrics/KPI models. | Starts at ~$10,000 – $15,000/yr (Contract-based via S&P Global; scales by coverage universe & seat count) | **14-day pilot/trial** arranged via sales demo; limited to sample coverage universe (no permanent free tier) |
| **[Koyfin](https://www.koyfin.com/)** | Market data, financial charting, equity screening, macroeconomic dashboards, and portfolio analytics. | **$39/mo** (Plus tier, billed annually) / $79/mo (Premium tier) | **Free forever plan**: Max 2 watchlists, 2 screens, 2 custom dashboards, 2 years financial statements, 1 year estimates, 1 portfolio |
| **[Tegus](https://www.tegus.com/)** | Primary research platform featuring a vast library of expert interview transcripts and financial models (now part of AlphaSense). | Starts at ~$20,000 – $25,000/seat/yr (Annual platform license) | **7-day trial / sample call bundle** arranged via sales consultation; access to sample transcript database (no permanent free tier) |
| **[BamSEC](https://www.bamsec.com/)** | Specialist tool for fast SEC EDGAR filing search, table extraction to Excel, and earnings call transcript navigation. | **$69/mo** (Pro tier, billed annually) | **7-day free trial** for Pro; limited transcript access during trial per S&P licensing agreements. Free tier offers basic search & SEC viewing only |
| **[S&P Capital IQ Pro](https://www.spglobal.com/marketintelligence/)** | Comprehensive institutional fundamental data, screening, financial modeling, and Excel plug-in analytics. | Starts at ~$12,000/seat/yr (Core desktop license; scales upwards based on data feeds/modules) | **7-day to 14-day trial** upon qualified sales request; limited dataset export/screening queries (no permanent free tier) |
| **[PitchBook](https://pitchbook.com/)** | Global private capital market database covering VC, PE, M&A transactions, fund performance, and valuations. | Starts at ~$20,000/seat/yr (3-user starter bundle typically ~$20,000 – $24,000/yr) | **7-day trial** via sales qualification / demo; capped search results and restricted raw data exports (no permanent free tier) |
| **[Mosaic Smart Data](https://www.mosaicsmartdata.com/)** | Real-time FICC data analytics and transaction intelligence platform for banks and buy-side trading desks. | Starts at ~$25,000/yr (Enterprise institutional subscription via Behavox sales) | **30-day free trial** for Smart Markets data intelligence service (requires corporate email verification; no permanent free tier) |
| **[Yewno](https://www.yewno.com/)** | AI-powered knowledge graph and thematic investment research engine mapping company concepts and market themes. | **$59/mo** (Basic tier) / $149/mo (Premium tier with Strategy Builder) | **14-day free trial** on Yewno Edge with full access to thematic screening and graphs (no permanent free tier) |

## Open-Source GitHub Projects

- **[EdgarTools](https://github.com/dgunning/edgartools)**  
  High-quality Python library for reading and analyzing SEC EDGAR filings (10-K, 10-Q, 8-K, 13F, Forms 3/4/5, XBRL financials, and more) with clean, typed APIs.

- **[FinSight & similar RAG research platforms](https://github.com/tejasbhargava/FinSight)**  
  AI-powered financial research assistants that combine SEC filings, market data, news, and retrieval-augmented generation to answer questions and generate investment theses.

- **[wallstreetlocal](https://github.com/leftmove/wallstreetlocal)**  
  Free and open-source platform for exploring 13F holdings of major institutional investors, making SEC ownership data more accessible.

- **[EDGAR Filing Analyser & research toolkits](https://github.com/search?q=EDGAR+SEC+filings+analysis)**  
  Open-source toolkits for downloading, filtering, summarizing, and analyzing SEC filings, often with LLM integration and fair-access compliance.

- **[FinanceLake & financial data platforms](https://github.com/FinanceLake/financelake)**  
  Open-source platforms for ingesting, processing, and analyzing financial and market data using scalable open technologies.

- **[AI stock analysis & research workbenches](https://github.com/SiinXu/stock-pulse-ai)**  
  Local-first, multi-market AI stock analysis and investment research systems that generate structured reports under user control.

- **[Finance agents & question-answering systems](https://github.com/kamathhrishi/finance-agent)**  
  Open-source agents that answer questions over earnings calls, SEC filings, and news using modern LLM and retrieval techniques.

### Additional Strong Open-Source Options

- **SEC EDGAR downloaders & parsers**: Multiple mature libraries for bulk and incremental filing retrieval and XBRL extraction.
- **13F / ownership trackers**: Tools that parse and visualize institutional holdings over time.
- **Financial statement & ratio engines**: Open libraries for calculating standard fundamental metrics from filings or data feeds.
- **News & transcript pipelines**: Scrapers and processors for earnings call transcripts and financial news (where legally permissible).
- **Vector search & RAG stacks**: Combinations of embedding models, vector databases, and LLMs tailored to financial documents.
- Academic and quant research repositories focused on **filing-based alpha**, **sentiment analysis**, and **event studies**.

**Frameworks for building custom systems**:  
Use **EdgarTools** or similar libraries as the foundation for SEC data access.  
Build a document store and RAG layer over filings, transcripts, and news.  
Add market data from open or low-cost providers and fundamental calculation engines.  
Present results through notebooks, Streamlit/Dash apps, or internal research portals.  
Premium content (sell-side research, expert networks, real-time news) will still typically require commercial licenses.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Investment research tools deal with financial data and can influence investment decisions. Users are solely responsible for the accuracy of their analysis and for compliance with securities laws, data-licensing terms, and fair-use policies (especially regarding SEC EDGAR access rates).
- Open-source tools do not constitute investment advice. Always verify data and consult qualified professionals where appropriate.

---

**Made for equity analysts, portfolio managers, quant researchers, and independent investors who value transparent, programmable research infrastructure.**  
Let's make high-quality investment research more accessible through open data and open tools.
