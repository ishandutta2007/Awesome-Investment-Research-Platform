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

- **[AlphaSense](https://www.alpha-sense.com/)**  
  Leading AI-powered market intelligence and search platform covering filings, transcripts, broker research, expert calls (including Tegus content), news, and internal documents.

- **[Sentieo](https://www.sentieo.com/)**  
  Research platform (now part of the broader AlphaSense ecosystem) known for powerful document search, filing analysis, and equity research workflows.

- **[Visible Alpha](https://visiblealpha.com/)**  
  Consensus and detailed financial estimates platform widely used by buy-side and sell-side analysts for standardized company models and KPIs.

- **[Koyfin](https://www.koyfin.com/)**  
  Affordable, modern market research and analytics platform offering charting, fundamentals, screening, and portfolio tools popular with independent investors and smaller teams.

- **[Tegus](https://www.tegus.com/)**  
  Expert interview and transcript platform (acquired/integrated into larger research ecosystems) providing primary research from industry specialists.

- **[BamSEC](https://www.bamsec.com/)**  
  Specialist platform focused on fast, efficient access to and analysis of SEC filings, transcripts, and related primary documents.

- **[S&P Capital IQ Pro](https://www.spglobal.com/marketintelligence/)**  
  Comprehensive financial data, analytics, and Excel-oriented modeling platform used extensively for fundamental research and comparable analysis.

- **[PitchBook](https://pitchbook.com/)**  
  Leading private-market data platform covering venture capital, private equity, M&A, fund performance, and company intelligence.

- **[Mosaic Smart Data / related analytics](https://www.mosaicsmartdata.com/)**  
  Specialized data and analytics solutions often used in fixed-income and multi-asset research contexts.

- **[Yewno](https://www.yewno.com/)**  
  AI-driven knowledge and thematic research platform that maps concepts and relationships across large document corpora for investment insight.

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
