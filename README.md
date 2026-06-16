# 📊 Finance & Risk Analytics System

A collection of finance analytics projects that showcase both historical portfolio analysis and modern API-driven market monitoring workflows.

---

# 🚀 Project Evolution

## Version 1 — Static Portfolio Analysis
Analyzes historical stock market data to evaluate portfolio performance, compare risk-return characteristics across sectors, forecast long-term growth trends, and recommend investment strategies based on different investor risk profiles.

### Key Highlights
- Portfolio risk-return analysis
- Sharpe ratio & ROI evaluation
- Sector-wise stock comparison
- Identification of top-performing stocks across sectors
- Forecasted future stock trends using historical 5-year return data
- Investor-focused portfolio recommendations
- Interactive Tableau dashboard development

### Tools Used
Python • Pandas • NumPy • Matplotlib • Seaborn • Plotly • Tableau • Jupyter Notebook

---

## Version 2 — Live Market Analytics Pipeline
Integrates real-time market data using APIs, applies data validation and transformation workflows, calculates portfolio performance metrics, validates results across Python and Power BI, and generates interactive dashboards and automated reports for portfolio monitoring.

### Project Outcomes

- Processed 2,480+ market data records across 10 stocks and 4 sectors
- Built and compared Conservative and Growth investor portfolios
- Calculated portfolio Return, Risk, and Sharpe Ratio metrics
- Developed interactive Power BI dashboards for portfolio monitoring
- Generated automated PDF portfolio performance reports
- Cross-validated metrics between Python and Power BI to ensure reporting accuracy

### Key Highlights

- Connected Python to Yahoo Finance API using yfinance
- Implemented data quality validation checks and error handling
- Reshaped MultiIndex API data into analysis-ready tabular structures
- Applied portfolio allocation and business-rule validation checks
- Developed Power BI measures and dashboard interactions
- Built automated PDF reporting workflows
- Structured the pipeline for future scheduling and automated refresh processes

### Tools & Technologies
Python • Pandas • NumPy • yfinance • Power BI • ReportLab • Git • GitHub • Jupyter Notebook

---

# 🔄 Key Improvements From V1 → V2

| Feature | V1 Static Analysis | V2 Live Analytics Pipeline |
|---|---|---|
| Data Source | Historical datasets | Live market API data |
| Workflow | Manual notebook analysis | API-integrated workflow |
| Market Updates | Static data snapshots | Dynamic live market data |
| Data Prep & Validation | Basic data preparation & Structuring | Data & business-rule Validation & Structuring |
| Portfolio Tracking | One-time analysis | Automated monitoring workflow |
| Reporting & Visualization | Exploratory analysis & Tableau Dashboard| Power BI & PDF report generation |
| Scalability | Limited | Designed for automation |

---

# 📂 Repository Structure

```text
Finance-and-Risk-Analytics-System/
│
├── README.md
│
├── v1_static_analysis/
|   ├── Finance and Risk Analytics-notebook.ipynb
│   └── dashboard/
│           └── Finance and Risk Analytics-Dashboard.twbx
|
|
├── v2_live_market_pipeline/
|   ├── portfolio_tracker.ipynb
│   ├── historical_stock_data.csv
│   ├── portfolio_daily_returns.csv
│   ├── portfolio_summary.csv
│   └── reports/
│       └── portfolio_report_YYYY-MM-DD.pdf
│
├── dashboard/
│   └── portfolio_tracker_dashboard.pbix
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

```bash
v2_live_market_pipeline/portfolio_tracker.ipynb
```

Run the notebook cells sequentially to:

- Fetch market data
- Validate and transform datasets
- Calculate portfolio KPIs
- Generate CSV outputs
- Create PDF reports
- Refresh Power BI data sources
