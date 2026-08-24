# 📊 Enterprise Sales Performance & Financial Analytics Dashboard

An enterprise-grade Excel analytics solution designed to consolidate beverage retail sales, pricing, and profitability metrics across multiple retailers and geographic regions. This repository provides automated monitoring of top-line revenue performance, regional profitability trends, financial scenario modeling, and strategic forecasts without manual reporting overhead.

---

## 📈 Key Performance Indicators

* **Total Transactional Records**: 9,662 rows
* **Time Horizon**: January 1, 2022 – December 31, 2023
* **Total Gross Revenue**: $12,083,427.50
* **Total Operating Profit**: $4,743,611.14
* **Top Profit-Generating Brand**: Coca-Cola
* **Top Performing Region**: West

---

## 📸 Project Visuals & Screenshots

### 1. Executive Dashboard Overview
![Executive Dashboard](https://raw.githubusercontent.com/Prakhar22052005/Enterprise-Sales-Performance-Analytics/main/documentation/executive_dashboard.png)
> Primary view featuring high-level KPI cards, monthly sales trends, and regional revenue distribution.

### 2. Budget vs. Actual Financial & Break-Even Model
![Financial Model](https://raw.githubusercontent.com/Prakhar22052005/Enterprise-Sales-Performance-Analytics/main/documentation/financial_model.png)
> Dynamic scenario analysis showing variance math and unit break-even volume based on editable assumptions (3% budget growth, $500K fixed costs).

### 3. Advanced Excel Functions & Dynamic Lookups
![Advanced Functions](https://raw.githubusercontent.com/Prakhar22052005/Enterprise-Sales-Performance-Analytics/main/documentation/advanced_functions.png)
> Technical implementation using dynamic array brand performance tables and lookup formulas (`XLOOKUP`, `INDEX/MATCH`).

### 4. Power Pivot Regional Performance Analysis
![Power Pivot Report](https://raw.githubusercontent.com/Prakhar22052005/Enterprise-Sales-Performance-Analytics/main/documentation/power_pivot_report.png)
> Aggregated pivot summary comparing regional revenue breakdown and overall operating profitability.

---

## 📁 Workbook Architecture & Tab Hierarchy

| Tab Order | Sheet Name | Visibility | Purpose & Function |
| :---: | :--- | :---: | :--- |
| **1** | `Dashboard (3)` | Visible | Primary executive dashboard with monthly trends, visual KPIs, and region summaries. |
| **2** | `Data_Calculations` | Visible | Backend aggregation tables supporting dashboard visuals. |
| **3** | `Data` | Visible | Master transaction database containing granular sales, retailer, and pricing records. |
| **4** | `Financial_Model` | Visible | Budget vs. Actual scenario modeling, growth assumptions (3%), and break-even unit analysis. |
| **5** | `Advanced_Functions` | Visible | Dynamic lookup tools (`XLOOKUP`, `INDEX/MATCH`) and dynamic array brand summaries. |
| **6** | `Dashboard_Calc` | **Hidden** | Staging calculations driving executive visuals. |
| **7** | `Business Objectives` | Visible | Project goals, scope overview, and core mathematical KPI formula references. |
| **8** | `Insights_&_Recommendation` | Visible | Key business findings, strategic recommendations, and data quality risk notes. |
| **9** | `Executive_Board_Report` | Visible | Summary report formatted for board leadership presentation. |
| **10** | `Dim_Region` | Visible | Master region dimension mapping (`Northeast`, `South`, `West`, `Midwest`, `Southeast`). |
| **11** | `Power_Pivot_Report` | Visible | Aggregated pivot table summary comparing regional revenue and operating profit. |

---

## 💡 Key Business Insights & Recommendations

* **Product Profitability**: **Coca-Cola** generates the highest overall operating profit across the product portfolio. Focus marketing, promotional, and inventory investment on top-performing brands and the West region.
* **Data Quality Risk Audit**: The YoY growth metric displays an unusually high value, indicating potential incomplete data coverage for 2022. Audit and resolve this data gap before presenting figures externally.
* **Financial Model Recalibration**: The `Financial_Model` sheet currently relies on placeholder monthly growth rate assumptions (3.0%) and fixed cost estimates ($500,000). Replace these placeholders with finance-approved target figures once available.
