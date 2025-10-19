# 🛍️ Mega Campaign Performance & SKU Health Analysis

## 📊 Project Overview

This project was developed during my time at **Daraz** to analyze **Mega Campaign performance** across multiple product categories and time windows.  
The goal was to create a **centralized SQL-based system** that measures campaign success, tracks GMV and order growth, and identifies **out-of-stock SKUs** or **pricing gaps** that impact sales performance.

The query served as the **data backbone** for automated dashboards used by category managers, campaign planners, and leadership to monitor campaign outcomes in real time.

---

## 🧩 Problem Statement

During Mega Campaigns (e.g., 11.11, 12.12, Ramadan, etc.), millions of SKUs are sold across various categories — making it difficult to manually assess:
- Which **categories** and **industries** are performing best  
- How **sales and orders** compare month-over-month or year-over-year  
- Which **SKUs went out of stock** during peak demand periods  
- Whether **price changes** affected conversion and sales volume  

To solve this, an **automated SQL framework** was designed to provide a complete performance snapshot of campaign effectiveness.

---

## 🧠 Approach

- Designed and implemented an **ODPS SQL script** that:
  - Calculates **GMV**, **Orders**, and **Growth Rates** across multiple time windows:  
    - Last Month (LM), Current Month (CM), Current Quarter (CQ), Current Year (CY)  
    - Compared to corresponding last year periods (LLM, LCM, LCQ, LY)  
  - Segments SKUs into key **industries** (Electronics, Fashion, Lifestyle, FMCG, Digital Goods)  
  - Identifies **out-of-stock** or **low-inventory SKUs** impacting campaign performance  
  - Evaluates **price consistency and its relation to sales volume**  
- Ensured clean data input by filtering:
  - Irrelevant accounts and low-value items  
  - Non-fulfilled or cancelled orders  
- The results were integrated into **Power BI dashboards** for real-time visibility and insights.

---

## 📊 Metrics Tracked

| Metric | Description |
|---------|--------------|
| **GMV (Gross Merchandise Value)** | Total campaign sales per industry |
| **Orders** | Number of fulfilled transactions |
| **SKU Availability** | Identification of out-of-stock or low-inventory products |
| **Price Tracking** | Analysis of pricing trends and their effect on performance |
| **Growth Rates** | Month-over-Month, Quarter-over-Quarter, and Year-over-Year % changes |
| **Category Segmentation** | Industry-level breakdown for cross-category comparison |

---

## 🛠️ Tools & Technologies

- **ODPS SQL (Alibaba MaxCompute)** – core aggregation, filtering, and data computation  
- **Power BI** – campaign performance visualization and KPI dashboards  
- **Excel** – quick exploratory analysis and validation  
- **Databricks / Python (optional)** – for workflow automation and scheduling  

---

## 📈 Outcome / Impact

- Automated generation of campaign performance metrics for all industries.  
- Provided **real-time insights** on out-of-stock SKUs, helping category teams act faster.  
- Improved **pricing strategy visibility** by correlating price changes with GMV and Orders.  
- Reduced manual reporting time by automating all key growth and stock metrics.  
- Delivered a **standardized data framework** for future campaign performance tracking.

---

## 🔒 Confidentiality Note

Due to company data protection policies, raw data and campaign performance figures are not shared.  
This repository focuses on the **SQL methodology** and **dashboard automation logic** used to monitor Mega Campaigns.

---

## 👤 Author

**Noor Wali**  
Growth & Data Analyst | Daraz  
[LinkedIn](https://www.linkedin.com/in/your-link) | [GitHub](https://github.com/noorw8354)

---

### 🔖 Tags
#SQL #Daraz #EcommerceAnalytics #MegaCampaign #GMV #PowerBI  
#DataAutomation #BusinessIntelligence #PerformanceTracking #StockAnalysis #PriceAnalytics
