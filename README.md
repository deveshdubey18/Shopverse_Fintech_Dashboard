# Shopverse Fintech Power BI Dashboard

A comprehensive fintech analytics project built using Microsoft Power BI to analyze financial performance, transaction trends, fraud patterns, customer behavior, merchant performance, and operational efficiency. The project combines interactive dashboards with strategic business analysis through SWOT and Fishbone Root Cause Analysis.

---

## 📥 Project Resources

Download the complete project files, including the dataset, Power BI dashboard, and documentation:

[**Shopverse Fintech Dashboard — Kaggle Dataset**](https://www.kaggle.com/datasets/deveshdubey18/shopverse-fintech-powerbi-dashboard)

---

## 📊 Project Overview

Shopverse Fintech is a fintech analytics case study designed to demonstrate how business intelligence can transform transaction-level data into actionable business insights.

The dashboard provides an overview of financial performance, revenue and profit generation, transaction outcomes, fraud trends, customer segments, merchant categories, and business growth strategies.

In addition to quantitative analysis, the project includes a SWOT Analysis to evaluate the business environment and a Fishbone Diagram to investigate potential causes of transaction failures and pending transactions.

### Project Objectives

- Monitor revenue, profit, active users, and transaction performance.
- Analyze revenue and profit trends across months, quarters, and years.
- Evaluate merchant categories and investor types based on financial contribution.
- Examine transaction success, failure, and pending rates.
- Investigate fraud patterns, fraud types, and yearly fraud trends.
- Understand customer segments, gender distribution, and transaction-related behavior.
- Evaluate growth strategies and identify potential operational bottlenecks.
- Translate analytical findings into strategic business recommendations.

---

## 🖥️ Dashboard Preview

The project includes interactive Power BI reports and supporting business analysis.

### 1. Financial Performance & Transaction Analysis

<img width="1343" height="682" alt="image" src=".github/assets/Screenshot 2026-10-14 175739.png" />

The main dashboard consolidates financial KPIs, revenue and profit trends, transaction outcomes, merchant performance, and investor contributions.

**Key Performance Indicators (as displayed in the dashboard):**

| KPI | Displayed Value |
|---|---:|
| Active Users | 15T |
| Total Revenue | 89.88M |
| Total Profit | 35.92M |
| Success Rate | 0.33 |
| Fraud Rate | 5.03% |
| Average Credit Score | 599.88 |


**Dashboard components:**

- Revenue contribution by investor type.
- Monthly and quarterly revenue and profit trends.
- Transaction amount distribution by transaction status.
- Revenue and profit comparison by merchant category.
- Profit distribution by gender and fraud type.

---

### 2. Customer, Fraud & Operational Analysis

<img width="1343" height="682" alt="image" src=".github/assets/Screenshot 2026-10-14 175801.png" />

This report explores customer segmentation, historical fraud counts, growth strategy performance, and transaction volume over time.

**Key visualizations:**

- Net revenue distribution across SME, Corporate, and Retail customer segments.
- Year-wise fraud counts from 2020 to 2025.
- Profit comparison across Acquisition, Cost Cutting, Digital Push, and Expansion strategies.
- Annual transaction amount trends.

These visualizations help identify changes in fraud activity, compare strategic initiatives, and understand the distribution of financial performance across customer groups.

---

### 3. SWOT Analysis

<img width="1343" height="682" alt="image" src=".github/assets/Screenshot 2026-10-14 175819.png" />

The SWOT analysis evaluates the business from four strategic perspectives.

| Strengths | Weaknesses |
|---|---|
| Comprehensive fintech service offering. | Low brand awareness in a competitive market. |
| Focus on financial inclusion. | High transaction failure and pending rates. |
| User-friendly digital experience. | Dependence on third-party APIs and partner systems. |
| Growing banking and retail partnerships. | Limited personalization and regional coverage. |
| Data-driven decision-making capabilities. | Complex compliance processes. |

| Opportunities | Threats |
|---|---|
| Growing adoption of digital payments. | Competition from established banks and fintech companies. |
| Expansion into underserved markets. | Regulatory changes and compliance requirements. |
| Partnerships with banks, NBFCs, and fintech enablers. | Cybersecurity and data privacy risks. |
| Growth in e-commerce and MSMEs. | Partner reliability and system uptime risks. |
| AI/ML-based risk assessment and personalization. | Economic downturns and changing customer expectations. |

The SWOT analysis provides a framework for evaluating internal capabilities and external market conditions when planning future business improvements.

---

### 4. Root Cause Analysis — Fishbone Diagram

<img width="1343" height="682" alt="image" src=".github/assets/Screenshot 2026-10-14 175834.png" />

The Fishbone Diagram investigates potential reasons behind the transaction outcomes displayed in the dashboard.

The analysis organizes potential contributing factors into six categories:

- **People:** Limited financial literacy, incorrect transaction details, low digital adoption, and insufficient support training.
- **Process:** Complex transaction steps, slow KYC verification, confirmation delays, and unclear communication.
- **Technology:** System downtime, payment gateway timeouts, database bottlenecks, and integration failures.
- **Partnerships:** Bank service disruptions, partner failures, limited network coverage, and third-party API instability.
- **Policies:** Strict compliance checks, policy changes, risk rules, and limited exception handling.
- **Marketing:** Low awareness of transaction statuses, unclear value communication, traffic spikes, and mismatched customer expectations.

The diagram helps structure further investigation into transaction failures and pending payments. These factors represent potential causes to validate using transaction logs, operational metrics, and stakeholder feedback rather than confirmed causal findings.

---

## 📈 Key Business Insights

Based on the supplied dashboard and supporting analyses:

1. **Financial performance:** The dashboard reports 89.88M in total revenue and 35.92M in total profit, providing a high-level view of business performance.
2. **Transaction outcomes:** Success, pending, and failed transactions are presented at approximately one-third each in the supplied visualization, highlighting a potential area for operational investigation.
3. **Merchant performance:** Retail, Food, Ecommerce, and Travel categories are compared by revenue and profit to support merchant-level performance evaluation.
4. **Fraud monitoring:** Year-wise fraud counts reveal changes in reported fraud activity, including a visible increase in 2024 relative to 2023.
5. **Customer segmentation:** SME, Corporate, and Retail segments contribute nearly equal proportions of net revenue in the displayed chart.
6. **Growth strategy evaluation:** Acquisition, Cost Cutting, Digital Push, and Expansion are compared using profit to support strategic assessment.
7. **Operational reliability:** System downtime, API response time, application latency, and transaction success metrics provide potential indicators for investigating service quality.

These observations describe the supplied visualizations. Further validation against the underlying dataset and measures is recommended before using them for operational or financial decisions.

---

## 🗂️ Dataset Description

The dataset contains transaction-level, financial, customer, fraud, business growth, and operational information.

The 73 supplied columns are organized below by analytical domain.

| Category | Columns |
|---|---|
| Transaction Identification & Time | `transaction_id`, `date`, `year`, `quarter`, `month`, `week`, `day`, `day_of_week`, `is_weekend`, `financial_year` |
| Company Information | `company_name`, `company_type`, `hq_city`, `country`, `company_founded_year`, `total_employees`, `market_share_percent`, `active_users` |
| Transaction Details | `transaction_amount`, `transaction_type`, `transaction_status`, `payment_channel`, `device_type`, `transaction_currency`, `cross_border_flag` |
| Financial Performance | `revenue`, `profit`, `processing_fee`, `commission_fee`, `gst_amount`, `net_revenue`, `cost_of_acquisition` |
| Merchant Analysis | `merchant_category` |
| Customer Information | `customer_id`, `customer_age`, `customer_age_group`, `gender`, `customer_segment`, `customer_region`, `customer_city`, `customer_tenure_months`, `avg_monthly_transactions`, `customer_lifetime_value` |
| Lending & Credit | `interest_rate`, `loan_amount`, `loan_tenure`, `emi_amount`, `default_flag`, `credit_score` |
| Fraud & Disputes | `fraud_flag`, `fraud_type`, `risk_score`, `fraud_detection_time_sec`, `chargeback_flag`, `dispute_status` |
| Investment & Growth | `funding_round`, `funding_amount`, `investor_type`, `valuation`, `growth_strategy`, `expansion_region` |
| Customer Engagement & Retention | `app_sessions`, `session_duration_sec`, `bounce_rate`, `feature_used`, `churn_flag`, `retention_rate` |
| System Performance & Reliability | `app_latency_ms`, `api_response_time_ms`, `success_rate`, `failure_rate`, `downtime_minutes`, `server_region` |

> **Dataset access:** [Download the dataset and Power BI dashboard from Kaggle](https://www.kaggle.com/datasets/deveshdubey18/shopverse-fintech-powerbi-dashboard).

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI** — Interactive dashboards and business intelligence reporting.
- **Power Query** — Data transformation and preparation.
- **DAX** — Calculated measures and KPI analysis, where applicable.
- **Data Visualization** — KPI cards, line and area charts, donut charts, bar charts, and decomposition-style analysis.
- **Business Analysis** — SWOT analysis and Fishbone root cause analysis.

---

## 🔍 Analytical Areas

The project covers the following business intelligence use cases:

- Financial KPI monitoring.
- Revenue and profitability analysis.
- Transaction status and payment performance.
- Fraud and risk monitoring.
- Customer segmentation and retention.
- Merchant and investor contribution analysis.
- Business growth strategy evaluation.
- Root cause investigation and strategic planning.

---

## 🚀 How to Access the Project

1. Open the [Shopverse Fintech Kaggle dataset page](https://www.kaggle.com/datasets/deveshdubey18/shopverse-fintech-powerbi-dashboard).
2. Download the available dataset, Power BI dashboard, and supporting documentation.
3. Extract the downloaded files if they are provided in an archive.
4. Open the `.pbix` file using Microsoft Power BI Desktop.
5. If Power BI prompts for a data source, update the file path to match the location of the downloaded dataset.
6. Refresh the data if required and explore the report pages and available filters.

---

## 🎯 Project Outcome

Shopverse Fintech demonstrates how Power BI dashboards and structured business analysis can be combined to examine financial performance, customer behavior, fraud patterns, transaction reliability, and growth opportunities.

The project showcases practical business intelligence concepts, data visualization, KPI reporting, and root cause analysis in a fintech context.

---

## 👨‍💻 Author

**Devesh Dubey** (https://github.com/deveshdubey18)

Data Analytics | Power BI | SQL | Python

- **Kaggle Dataset:** [Shopverse Fintech Power BI Dashboard](https://www.kaggle.com/datasets/deveshdubey18/shopverse-fintech-powerbi-dashboard)
- **GitHub:** [deveshdubey18](https://github.com/deveshdubey18)

---

*If you find this project useful, consider starring the repository and sharing your feedback.*
