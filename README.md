
# US Music Industry Revenue Dashboard

An analysis of US recorded music revenue from 1980–2023, built from 
primary RIAA annual revenue reports. Tracks the complete format disruption 
cycle: vinyl → CD → digital download → streaming.

## Why this matters
The music industry's revenue model has been completely restructured twice 
in 25 years. Understanding this shift is essential context for any business 
decision in the industry — from artist deals to label strategy to 
tech investment.

## Data source
Compiled directly from RIAA Year-End Revenue Statistics reports (2023, 2024).
Historical figures hand-curated from RIAA annual reports 1980–2023.
Source: riaa.com/u-s-sales-database

## Tools
Python · pandas · plotly · pdfplumber · Jupyter

## Key findings
1. **Streaming now accounts for ~84.5% of total US music revenue** — a format 
   that barely existed in 2010 restructured the entire industry in a decade.

2. **The download era was brief and is over** — digital downloads peaked 
   around 2008 and have declined every year since, now under 3% of revenue. 
   The industry skipped a generation in its transition from physical to digital.

3. **Vinyl is the surprise comeback** — LP/EP revenue grew 10.3% in 2023, 
   now outpacing CDs in dollar value for the first time since the 1980s, 
   suggesting a durable premium physical market will coexist with streaming.
	> *except this does not account for inflation; if that was taken into consideration CD sales are still above LP/EP, which is something people often overlook*

<img width="969" height="488" alt="Screenshot 2026-05-28 at 13 18 43" src="https://github.com/user-attachments/assets/179810b7-c1c0-41bc-adcb-dbc87502978b" />

## Charts
- `charts/chart1_revenue_over_time.html` — Stacked area: revenue by format 1980–2023
- `charts/chart2_2023_breakdown.html` — Bar chart: 2023 revenue by category
- `charts/chart3_yoy_change.html` — % change by format 2022→2023
- `charts/chart4_format_share.html` — Format share of total revenue over time

## How to run
1. Clone this repo
2. In a notebook cell run:
   `import subprocess, sys; subprocess.run([sys.executable, "-m", "pip", "install", "pandas plotly pdfplumber"])`
3. Open `revenue_analysis.ipynb` in Jupyter
4. Run all cells

## About
Built as part of a data analytics portfolio for MSBA graduate school applications.
LMU Recording Arts + Business Administration, Class of 2027.
