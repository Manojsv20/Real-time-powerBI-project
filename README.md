# 📊 Dashboard 360 – Real‑Time Power BI Project

[![Power BI](https://img.shields.io/badge/Tool‑Power%20BI‑04A6C1?logo=power-bi&logoColor=white)](https://powerbi.microsoft.com/)  
[![GitHub Issues](https://img.shields.io/github/issues/Manojsv20/Real-time-powerBI-project)](https://github.com/Manojsv20/Real-time-powerBI-project/issues)  
[![License](https://img.shields.io/badge/License-MIT-blue)](LICENSE)

---

## 📘 Project Overview  
**Dashboard 360** is a **real-time sales and finance analytics dashboard** built using **Power BI**. The project provides deep insights into revenue, profitability, targets vs actuals, and market performance. With interactive visuals, KPI cards, and DAX calculations, it enables data-driven decision-making for stakeholders. 💼📈

---

## 🔎 Business & Financial Analysis  

- **📈 Revenue Trends & Forecasting**:  
  Analyze month-wise, quarter-wise, and year-wise revenue. Compare actuals against forecasts and identify growth patterns.  

- **🛒 Sales Performance by Dimension**:  
  Track performance by product category, zone, or fiscal period. Identify top-performing products and regions using slicers and filters.  

- **💰 Profitability & Margin Analysis**:  
  Compute gross and net margins, identify high-profit segments, and analyze product contribution to overall revenue.  

- **🎯 Target vs Actuals Analysis**:  
  Compare finance and sales targets with actual results. Evaluate variances, % achievement, and trends using DAX measures.  

- **💵 Cash Flow / Working Capital (if included)**:  
  Insights into cash cycles, receivables, payables, and financial stability.

---

## 🛠 Technical Architecture & Data Modeling  

- **💾 Data Source**: SQL databases (`gdb041`, `gdb056`) for transactional and business data.  
- **🔄 ETL / Data Preparation**: Power Query for importing, cleaning, and transforming datasets.  
- **🗂 Data Model**: Star schema with fact tables (sales, finance) and dimension tables (date, product, region).  
- **📊 DAX Measures**: Revenue, margin, variance, YTD, MoM growth, KPIs, ranking, and trend calculations.  
- **⚡ Optimization**: Reduced cardinality, incremental refresh (optional), aggregated tables for performance.  

---

## 📈 Reporting & Visualizations  

**Report Pages:**

- 🏠 **Overview Dashboard** – High-level KPIs for revenue, profit, target achievement, and top-performing regions.  
- 📊 **Sales Trend Analysis** – Month-wise and year-wise sales trends, segmented by product, category, and zone.  
- 💹 **Margin & Profitability** – Gross/net margin analysis with top contributors and profitability trends.  
- 🎯 **Target vs Actuals** – Variance and % achievement against targets with conditional formatting for easy insights.  
- 💼 **Cash Flow / Financial Health** – Visualizations for cash, receivables, payables, and working capital performance.  

**Visuals & Interactivity:**

- Bar charts, column charts, line charts, KPI cards, and matrices.  
- Slicers for fiscal year, zone, product line, and category.  
- Conditional formatting and custom visuals for better interpretation.  
- Interactive drill-through and filtering for granular insights.

---

## 🌐 Project Files & Resources  

| 📁 **Item** | 📄 **Description** |
|---|---|
| 🗂 **Complete Project Folder** | Full repository including raw & cleaned datasets, Excel files, documentation, PBIX support files, and intermediate processing files. <br>🔗 [Project Folder](https://drive.google.com/drive/folders/13zhOzPXjNvsJ-bceR_Tv7L3MTYJvYktl?usp=sharing) |
| 📊 **Power BI Dashboard (PBIX)** | Final interactive Power BI report with all visuals, KPIs, DAX measures, and data model. <br>🔗 [Download PBIX](https://drive.google.com/file/d/1GBe3oN66kJVOempENV2jDw4XkOwwk77g/view?usp=sharing) |
| 🎥 **Dashboard Demo Video** | Walkthrough video showing dashboard interactivity, slicers, and insights for stakeholders. <br>🔗 [Watch Demo](https://drive.google.com/file/d/1sbiUWgpijatGT5BF7iBaCyWdobXLDmxz/view?usp=sharing) |
| 💾 **gdb041 Database Files** | Unzipped dataset from the `gdb041` SQL database including transactional tables, product details, and customer info. <br>🔗 [gdb041 Files](https://drive.google.com/file/d/1HCA1pWB98qCVr_vW2XsbmBb6sa5PtiwR/view?usp=sharing) |
| 💾 **gdb056 Database Files** | Unzipped dataset from the `gdb056` SQL database containing additional business tables, extended transactions, and supporting data. <br>🔗 [gdb056 Files](https://drive.google.com/file/d/1HCA1pWB98qCVr_vW2XsbmBb6sa5PtiwR/view?usp=sharing) |

---

## ✅ How to Use This Project  

1. 📥 Clone this repository locally.  
2. 🖥 Download the `.pbix` file from Google Drive and open with **Power BI Desktop**.  
3. 🔌 (Optional) Connect to `gdb041` / `gdb056` databases for live data analysis.  
4. 🔄 Refresh the dataset using Power Query.  
5. 📊 Explore report pages and interact with slicers to view insights.  
6. 🧩 Check DAX measures and model relationships to understand business logic.

---

## 🔧 Technology Stack  

- 🖥 **Power BI Desktop** – Dashboard creation and modeling  
- 🗄 **Microsoft SQL Server** – Data storage and transactional processing  
- 🔄 **Power Query** – Data transformation and ETL  
- 🧮 **DAX** – Measures, KPIs, and calculations  
- 📊 **Excel / CSV** – Intermediate or reference datasets  
- 🌐 **Google Drive** – Hosting large files

---

## 🌟 Why This Project Matters  

- 💡 Provides **data-driven decision-making** through interactive sales and finance KPIs.  
- 🔍 Improves **visibility** into revenue, margins, and financial health.  
- ⚡ Demonstrates **end-to-end BI capabilities**, from SQL ingestion to interactive reporting.  
- 🚀 Scalable design supports future data sources, advanced analytics, and dashboard expansions.  

---

## 📜 License  
This project is open-source under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

