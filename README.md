# Cardiovascular Medical Device Market Analysis

## Overview
Market analysis of U.S. cardiovascular medical device trends using publicly available FDA 510(k) clearance data and CMS Medicare utilization reports (2015–2023).

This repository provides a comprehensive analysis of the cardiovascular medical device market, examining regulatory approval patterns, manufacturer competitiveness, and healthcare utilization trends in the United States.

## Objectives
- Map market entry trends across cardiovascular device categories
- Identify top manufacturers by clearance volume and regulatory strategy
- Forecast procedure volume growth using time-series analysis
- Build a competitive landscape from regulatory filing patterns
- Analyze market consolidation and innovation cycles

## Data Sources
- **FDA 510(k) Premarket Notification Database** - Regulatory clearances and market entry data
- **CMS Medicare Physician & Supplier Procedure Summary** - Healthcare utilization and procedure volumes
- Additional source documentation available in `/data/sources.md`

## Repository Structure

## Tools & Technologies
- **Python**: Pandas, Matplotlib, Seaborn, Statsmodels
- **Data Visualization**: Tableau, Power BI
- **Spreadsheets**: Excel (pivot tables, advanced formulas)
- **Statistical Analysis**: Time-series forecasting, trend analysis

## Key Findings

## How to Use This Repository

### Prerequisites
```bash
pip install pandas matplotlib seaborn statsmodels jupyter scikit-learn
```

### Running the Analysis
1. Download data files from sources listed in `/data/sources.md`
2. Place CSV files in the `/data` directory
3. Open and run notebooks in `/analysis` folder sequentially:
   - Start with `exploratory_analysis.ipynb`
   - Follow with market trend and forecasting notebooks
4. View visualizations in `/visualizations` directory

### Accessing Dashboards
- Tableau/Power BI dashboards are exported in `/visualizations/dashboards/`
- Open with respective desktop applications or view published versions via links in dashboard README

## Key Metrics & Definitions

| Metric | Definition |
|--------|-----------|
| 510(k) Clearance | FDA regulatory approval pathway for predicate devices |
| CAGR | Compound Annual Growth Rate |
| Market Penetration | % of eligible Medicare population receiving procedures |
| Device Category | Classification by intended use and anatomical site |
| Manufacturer Market Share | % of total 510(k) clearances within analysis period |



## Contributing
This repository documents completed analysis. For questions, suggestions, or corrections:
1. Open an Issue describing your feedback
2. Provide supporting data or references where applicable

## License
This project uses publicly available government data (FDA, CMS). Analysis and code are provided as-is for research and educational purposes.

## References
- [FDA 510(k) Database](https://www.fda.gov/medical-devices/guidance-documents/guidance-summary-510k)
- [CMS Medicare Utilization Reports](https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports)
- Cardiovascular device regulatory framework documentation
