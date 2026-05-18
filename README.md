# 📊 Finance & Risk Analytics System

A Python-based finance analytics project that analyzes stock market data and demonstrates the transition from static historical analysis to automated real-time data monitoring and reporting.

---

# 🚀 Project Evolution

## Version 1 — Static Portfolio Analysis
Focused on exploratory financial analysis, sector comparison, portfolio performance evaluation, and investment recommendations using historical stock market data.

### Key Highlights
- Portfolio risk-return analysis
- Sharpe ratio & ROI evaluation
- Sector-wise stock comparison
- Identification of top-performing stocks across sectors
- Forecasted future stock trends using historical 5-year return data
- Investor-focused portfolio recommendations
- Data storytelling through dashboards and presentations

### Tools Used
Python • Pandas • NumPy • Matplotlib • Seaborn • Plotly • Tableau • Jupyter Notebook

---

## Version 2 — Live Market Pipeline *(In Progress)*
Modernizing the project into a live-market tracking workflow using API-based data extraction and automation concepts.

### Current Progress
- Connected Python with Yahoo Finance API using `yfinance`
- Fetching live stock market data dynamically
- Multi-stock ticker tracking workflow
- Git-based project version control setup
- Structured project architecture for future automation

### Planned Improvements
- Error handling using try-except blocks
- Automated report generation
- Power BI dashboard integration
- Scheduled data refresh pipeline
- Reusable Python functions
- Transition from notebook workflow → automation-ready scripts

### Tools & Technologies
Python • Pandas • Jupyter • Git • GitHub • Power BI *(planned)*

---

# 🔄 Key Improvements From V1 → V2

| Feature | V1 Static Analysis | V2 Live Pipeline |
|---|---|---|
| Data Source | Historical datasets | Live market API data |
| Workflow | Manual notebook analysis | API-integrated workflow |
| Market Updates | Static data snapshots | Dynamic live data |
| Portfolio Tracking | Single analysis workflow | Sector-based tracking |
| Project Structure | Exploratory analysis | Automation-oriented architecture |
| Scalability | Limited | Designed for future expansion |

---

# 📂 Repository Structure

```text
Finance-and-Risk-Analytics-System/
│
├── README.md
│
├── v1_static_analysis/
│
├── v2_live_market_pipeline/
│
├── dashboard/
├── images/

```
# ▶️ How To Run

## 1. Clone Repository

```bash
git clone <repository-url>
```

## 2. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn plotly yfinance
```

## 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

## 4. Open Notebook

Navigate to:

```text
v2_live_market_pipeline/portfolio_tracker.ipynb
```
and run the notebook cells.
