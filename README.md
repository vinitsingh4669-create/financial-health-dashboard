# Financial Health Dashboard

### Banking Portfolio Risk Visualisation | Power BI | DAX | Banking Analytics

---

## Project Overview

This project visualises the **Financial Health Scoring System** built in [Project 2](https://github.com/vinitsingh4669-create/banking-financial-health-analysis) as a 3-page interactive Power BI dashboard. Using the same 495-customer dataset, the dashboard translates MySQL scoring outputs into executive, analytical, and operational views — enabling a risk team to monitor portfolio health, identify at-risk segments, and prioritise customer interventions.

**Dataset:** [IBM Bank Transaction Dataset for Fraud Detection](https://www.kaggle.com/datasets/valakhorasani/bank-transaction-dataset-for-fraud-detection)
| 2,512 transactions | 495 unique customers | 12 months (Jan 2023 – Jan 2024)

**Built on top of:** [Banking Transaction & Financial Health Analysis — MySQL](https://github.com/vinitsingh4669-create/banking-financial-health-analysis)

---

## Business Objective

The MySQL project answered *which customers are financially stressed*. This dashboard answers the next question every risk team asks:

> *How do I monitor portfolio health, understand where risk is concentrated, and act on it — all in one place?*

---

## Methodology

| Page | Audience | Purpose |
| --- | --- | --- |
| 1 — Portfolio Overview | Risk Head / CFO | Headline KPIs and full portfolio segment breakdown |
| 2 — Risk Deep-Dive | Credit Risk Analyst | Risk concentration by age, occupation, and score distribution |
| 3 — Action List | Relationship Manager / Collections | Filtered intervention list of At-Risk and Critical customers |

---

## Key Findings

- **39% of the portfolio (193 customers) shows measurable stress signals** before any default — the early warning system is detecting real deterioration
- **High Volatility is the dominant stress signal** at 315 customers — not Low Balance (26 customers). This is an income stability problem, not a poverty problem
- **Balance drops monotonically across all four segments** — ₹5.8K → ₹4.3K → ₹3.5K → ₹1.8K — validating that the health score captures genuine financial deterioration, not noise
- **The Watch segment (159 customers, 32%) is the highest-priority intervention opportunity** — densely clustered just above the At-Risk threshold, recoverable if caught early
- **Students and Under-25 customers are the highest-risk demographic** — the only group with a visible Critical segment across both occupation and age dimensions
- **Doctors show unexpected risk concentration** — 42% fall in Watch despite the highest average balance (₹6,255). Irregular income, not low balance, is the driver

---

## Concepts Applied

`Portfolio Risk Monitoring` · `Customer Segmentation` · `Early Warning Dashboards` ·
`Data Modelling` · `DAX Measures` · `Conditional Formatting` ·
`Wide-to-Long Data Reshaping` · `Executive Dashboarding` · `Operational Action Lists` ·
`Retail Banking Analytics`

---

## Tech Stack

- **Power BI Desktop** — Data modelling, DAX measures, report canvas, conditional formatting
- **Power Query (M)** — Table reshaping, column cleanup, unpivot transformation
- **DAX** — CALCULATE, COUNTROWS, AVERAGE, DIVIDE
- **MySQL 8.0** — Source system (see [Project 2](https://github.com/vinitsingh4669-create/banking-financial-health-analysis) for full SQL pipeline)

---

## How to Run

1. Clone this repository
2. Open `financial_health_dashboard.pbix` in Power BI Desktop (free download at powerbi.microsoft.com/desktop)
3. If prompted to refresh data, point the three CSV sources to the `/data` folder in this repository
4. All relationships, measures, and formatting are pre-built — dashboard loads immediately

---

*Built by Vinit Singh | [LinkedIn](https://www.linkedin.com/in/vinit-singh-7b616a175)*
