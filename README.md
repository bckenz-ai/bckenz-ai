<h1 align="center">Bryant Kenzo P. Carolino</h1>
<p align="center">
  <em>B.S. Data Science and Analytics &nbsp;|&nbsp; University of Santo Tomas, Manila</em>
</p>
<p align="center">
  <a href="https://linkedin.com/in/kenzo-carolino">
    <img src="https://img.shields.io/badge/LinkedIn-kenzo--carolino-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:bc.kenz@gmail.com">
    <img src="https://img.shields.io/badge/Email-bc.kenz%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" />
  </a>
  <img src="https://img.shields.io/badge/Location-Manila%2C%20Philippines-0F172A?style=flat-square&logo=googlemaps&logoColor=white" />
</p>

---

## About

Data-driven professional pursuing a B.S. in Data Science and Analytics at the University of Santo Tomas (Dean's Lister, GWA 1.469). My background sits at the intersection of data, finance, and operations, with hands-on experience ranging from building SQL/PHP databases and Google Apps Script automations in a corporate internship to developing an automated forex data pipeline and visualization dashboard. I approach every problem with a bias toward analytical rigor, clear communication, and practical execution.

---

## Projects

### [Algorithmic Strategy Backtester](https://github.com/bckenz-ai/algorithmic-strategy-backtester)
> A from-scratch backtesting engine for quantitative trading strategies, built to evaluate signal quality with institutional-grade rigor and honest, unsparing performance analysis.

- Implements a 50/200-day SMA crossover strategy on EUR/USD (2020–2026); long-only signal generated on golden cross, flat on death cross
- Uses log returns throughout and applies `.shift(1)` to all position columns to eliminate look-ahead bias; transaction costs of 0.1% per trade deducted at entry/exit
- Computes a full performance tearsheet: Total Return, annualized Sharpe Ratio (vs. ECB Euro Short-Term Rate), Maximum Drawdown, Win Rate, and trade count — with written interpretation of each metric
- Concludes that the strategy underperforms buy-and-hold on choppy, range-bound EUR/USD due to whipsaw conditions; contextualizes results against institutional thresholds (e.g., 10–20% MDD limits, 30-trade statistical minimums)
- Stack: `Python` `yfinance` `Pandas` `NumPy` `Matplotlib` `Backtrader`

---

### [Machine Learning Projects](https://github.com/bckenz-ai/machine-learning-projects)
> A collection of applied machine learning notebooks covering supervised learning, unsupervised learning, NLP, and model diagnostics — with real-world Philippine and international datasets.

- Covers ensemble methods (Random Forest, AdaBoost, Gradient Boosting), regularization, dimensionality reduction (PCA, t-SNE, UMAP), class imbalance handling, and NLP (sentiment analysis, text clustering, topic modeling)
- Applied to datasets including Telco Churn, IMDB reviews, 2022 Philippine election results, and U.S. Census income data
- Gradient Boosting achieves 88% accuracy on income classification; boosting ensembles outperform logistic regression baselines at 86%+
- Stack: `Python` `Scikit-learn` `NLTK` `spaCy` `Pandas` `Matplotlib` `Seaborn`

---

### [Stock Portfolio Risk Dashboard](https://github.com/bckenz-ai/stock-portfolio-risk-dashboard) &nbsp;·&nbsp; [Live App](https://stock-portfolio-risk-dashboard-2amfedsadxghp7h3ht2ejb.streamlit.app/)
> An interactive Streamlit dashboard that computes institutional-grade risk metrics for any user-defined stock portfolio using live market data.

- Computes Sharpe Ratio (annualized, BSP risk-free rate), Maximum Drawdown, and historical Value at Risk at 95% and 99% confidence for any set of tickers and date range
- Uses log returns throughout for mathematically consistent annualization, consistent with practitioner convention
- Sidebar-driven inputs (tickers, date range, risk-free rate) with `@st.cache_data` to prevent redundant API calls on re-renders
- Stack: `Python` `yfinance` `Pandas` `NumPy` `Streamlit`

---

### [Forex Dashboard](https://github.com/Forex-DataViz/forex-dashboard) &nbsp;·&nbsp; [Live App](https://forex-dashboard-carolino-favorada-lavado-punzalan-yutuc.streamlit.app)
> An automated, multi-source foreign exchange data pipeline and interactive visualization dashboard built for the Philippine market.

- Aggregates daily USD-PHP exchange rates, macroeconomic indicators (GDP, FDI, inflation), oil prices, and central bank policy rates from five APIs and data sources (Frankfurter, World Bank, EIA, FRED, BSP)
- Automated via GitHub Actions on a weekday schedule (6:00 PM Manila time), committing updated datasets directly to the repository
- Stack: `Python` `Pandas` `Streamlit` `GitHub Actions` `Google Sheets API`

---

### [Internship Operations Toolkit](https://github.com/bckenz-ai/internship-ops-toolkit)
> A suite of Google Apps Script automations built during a finance internship at Parallel Dimensions Inc. to support event operations and financial workflows.

- **AUTOCOMPUTE** — Batch payroll/commission calculator; iterates through a host roster, feeds each name into a formula-driven calculator cell, captures the computed output, and writes all results back in a single pass. Triggered via a checkbox acting as a run button
- **INVITE COUNT** — Baseline-and-delta reporting tool for nightlife event hosts; saves a snapshot of live invite counts, then generates a formatted 3PM/9PM report split by eligibility threshold (5+ invites), with per-host deltas and a copyable modal output
- **GUESTLIST** — Guest registration pipeline; ingests raw Google Form submissions, reorganizes entries by ticket tier, auto-generates a clean formatted report sheet with per-tier counts, and syncs payment verification edits back to the source database in real time
- Stack: `Google Apps Script` `Google Sheets API` `JavaScript`

---

## Skills

**Data & Analytics**
`Python` `SQL` `Pandas` `Scikit-learn` `NLTK` `spaCy` `Data Visualization` `Technical & Fundamental Analysis` `Consumer Analytics`

**Finance & Operations**
`Budgeting & Forecasting` `Financial Recordkeeping` `Expense Tracking` `Cash Flow Management` `Quantitative Strategy Development` `Backtesting`

**Development**
`PHP` `Google Apps Script` `JavaScript` `GitHub Actions` `Streamlit` `REST APIs` `Google Sheets API` `Backtrader`

**Leadership & Management**
`Team Management` `Task Delegation` `Performance Monitoring` `Strategic Planning`

---

## Experience

**Finance Intern** — Parallel Dimensions Inc., Makati *(Dec 2025 – May 2026)*
Built a full-featured staff database using SQL and PHP; developed internal Google Apps Script automations for payroll computation, event invite tracking, and guest registration management; supported budgeting, expense tracking, and real-time financial operations for large-scale nightlife events.

**Foreign Exchange Trader** — Independent *(Jun 2024 – Aug 2025)*
Executed live currency trades using technical and fundamental analysis; maintained a 52% win ratio with detailed trade logging and strategy refinement.

**Executive Director for Finance** — UST College of Science Student Council *(Sep 2025 – May 2026)*
Led financial planning and execution for major college events; mentored a team of student coordinators and supervised all financial reporting and accountability processes.

**Virtual Assistant** *(Jun 2024 – Sep 2024)*
Managed professional calendars, coordinated logistics for webinars, and streamlined team workflows to improve overall productivity.

---

## Education

**B.S. Data Science and Analytics** — University of Santo Tomas, Manila *(2024–2028, expected)*
GWA: 1.469 | Dean's Lister, A.Y. 2024–2026

**High School Diploma (STEM)** — Assumption Iloilo *(Graduated 2024)*
GWA: 95.00 | High Honours | Award for Research and Innovation

---

## Certifications

- Virtual Assistant Course: Level Up Your Career in Just One Week — Talk2Emm / NYC University *(2024)*
- Introduction to Data Science — Great Learning Academy *(2024)*

---

<p align="center">
  <a href="https://linkedin.com/in/kenzo-carolino">LinkedIn</a> &nbsp;&middot;&nbsp;
  <a href="mailto:bc.kenz@gmail.com">Email</a>
</p>
