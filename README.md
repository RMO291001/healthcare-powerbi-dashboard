# U.S. Healthcare Industry Dynamics

A Power BI analytics solution that delivers end-to-end visibility into U.S. healthcare operations — covering patients, providers, payers, and financial performance — for the 2019–2020 period.

![Tool](https://img.shields.io/badge/Power%20BI-F2C811?logo=powerbi&logoColor=black)
![Language](https://img.shields.io/badge/DAX-purple)
![Status](https://img.shields.io/badge/status-completed-brightgreen)

---

## Overview

This project consolidates healthcare operational and financial data into a single, interactive Power BI report. It is designed to help executives, hospital administrators, and analysts identify performance gaps, monitor revenue cycles, and surface the demographic and lifestyle patterns that drive utilization.

The report is built on a star-schema data model with DAX measures for KPIs, ratios, and time-intelligence calculations, and uses Power Query for upstream data shaping.

## Business Questions Addressed

- How are revenue and expenses trending month over month, and where do they deviate from plan?
- Which hospitals are underperforming relative to peer benchmarks on efficiency ratios?
- What is the demographic and lifestyle profile of the patient population?
- How do payer–provider relationships influence financial outcomes and procedure mix?
- Where are the largest opportunities for cost optimization?

## Tech Stack

| Layer | Tools |
|---|---|
| Visualization | Power BI Desktop |
| Data Modeling | Star schema (fact and dimension tables) |
| Calculations | DAX (measures, KPIs, time intelligence) |
| Data Preparation | Power Query (M) |
| Distribution | `.pbix` file + PDF export |

## Report Pages

### 1. Executive Summary
High-level KPIs for total patients, revenue, and expenses, with monthly trend lines and performance indicators benchmarked against targets.

### 2. Hospital Performance
Facility-level metrics including the ARGE and IPTP ratios, procedure-mix distribution across hospitals, and a flagging view for underperforming locations.

### 3. Patient Analytics
Demographic breakdowns by age, gender, and state, combined with lifestyle factors — diet, alcohol consumption, exercise, and tobacco use — to support population-health analysis.

### 4. Payer–Provider Analysis
Financial relationships between payers and providers, CPT unit distribution by payer type, and provider specialization and performance insights.

### 5. Financial Trends
Monthly expense tracking, revenue split between insurance reimbursements and direct patient payments, and net-revenue benchmarking.

## Key Findings

- **Revenue mix concentration.** Revenue streams show meaningful variance between insurance and direct patient payments, indicating exposure to shifts in payer mix.
- **Volume concentration.** A small set of hospitals contributes a disproportionate share of total procedure volume, suggesting both operational dependency and benchmarking opportunities.
- **Lifestyle correlation.** Patient lifestyle factors correlate with downstream utilization patterns relevant to population-health programs.
- **Cost-optimization signal.** Monthly expense fluctuations point to specific line items where targeted reviews could reduce run-rate costs.

## Repository Structure

```
.
├── dashboards.pbix     # Power BI report (open in Power BI Desktop)
├── report.pdf          # Static PDF export of all report pages
└── README.md           # Project documentation
```

## Getting Started

### Prerequisites
- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) — latest version recommended
- Windows 10 or 11

### Steps
1. Clone or download this repository.
   ```bash
   git clone https://github.com/RMO291001/u-s-healthcare-industry-dynamics.git
   ```
2. Open `dashboards.pbix` in Power BI Desktop.
3. Use the slicers and filters on each page to explore the data interactively.
4. For a quick preview without Power BI installed, open `report.pdf`.

## Roadmap

- Live data integration via direct query or scheduled refresh against a healthcare data source
- Predictive layer using machine-learning models for readmission risk and revenue forecasting
- Row-level security for role-based access (executive vs. facility vs. analyst views)
- Mobile-optimized layouts for on-the-go review

## Author

**Ribbie Mohammad Omar**
- GitHub: [@RMO291001](https://github.com/RMO291001)
- LinkedIn: [Ribbie Md Omar](www.linkedin.com/in/ribbie-md-omar)

## License

This project is shared for educational and portfolio purposes. For commercial or other use, please contact the author.

---

If this project is useful to you, a ⭐ on the repository is appreciated.
