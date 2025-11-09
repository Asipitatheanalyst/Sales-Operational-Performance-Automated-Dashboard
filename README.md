# 🧾 2024 Sales & Operational Performance Dashboard

This project presents a **comprehensive business intelligence dashboard** that analyzes 2024 company-wide sales and operational data.  
It visualizes key metrics such as **revenue, profit, product performance, and regional operations**, helping decision-makers identify growth opportunities and improve efficiency across channels and regions.

---

## 📚 Table of Contents
- [Project Overview](#project-overview)
- [Problem Statement](#problem-statement)
- [Objectives](#objectives)
- [Dataset](#dataset)
- [Process & Analysis](#process--analysis)
- [Dashboard Features](#dashboard-features)
- [Key Insights](#key-insights)
- [Tools Used](#tools-used)
- [VBA Code](#vba-code)
- [Overall Performance Summary](#overall-performance-summary)
- [Conclusion](#conclusion)

---

## Project Overview

The **2024 Sales & Operational Performance Dashboard** is an analytical visualization tool built to **track, monitor, and interpret business performance metrics** across different product categories, countries, and channels.

It comprises **two main automated dashboards**:
1. **Sales Performance Dashboard** – focuses on overall sales, profit, and product-level performance.
2. **Regional & Operational Performance Dashboard** – focuses on country-level, regional, and operational efficiency metrics.

The project aims to help business leaders quickly answer:
- *Which products and countries drive the highest profit?*  
- *How do sales channels (online vs. offline) perform?*  
- *What seasonal or regional trends exist within the data?*

---

## Problem Statement

In 2024, the company expanded bulk product sales across multiple countries and channels.  
However, executives struggled to **gain a unified view of performance**—profitability varied by region, products fluctuated in demand, and operational delays affected delivery efficiency.

Key business challenges included:
- Disjointed reporting systems across departments.
- Limited visibility into monthly sales and shipping performance.
- Difficulty identifying underperforming markets and product categories.
- No centralized dashboard to summarize company-wide insights.

---

## Objectives

The project’s core objective was to **design an interactive dashboards** that integrates sales and operational data to:
1. Provide **real-time visibility** into sales performance and profitability.
2. Identify **top-performing products, countries, and regions**.
3. Compare **online vs. offline sales channels**.
4. Evaluate **operational metrics** like shipping time and order priorities.
5. Support **data-driven decision-making** for future planning.

---

## Dataset

The dataset represents **bulk product sales transactions** across multiple global regions for 2024.  
Each record captures details about:
- Product category  
- Country and region  
- Sales channel (Online / Offline)  
- Order priority  
- Units sold  
- Revenue and profit  
- Shipping duration (in days)

**Data Summary:**
| Metric | Value |
|:--|:--|
| Total Unit Sold | 500M |
| Total Orders | 100K |
| Total Revenue | $133.6B |
| Total Profit | $39.4B |
| Average Profit Margin | 29% |
| Average Shipping Days | 25 |
| Average Profit per Order | $394K |

---

## Process & Analysis

The project followed a **structured workflow** combining data cleaning, modeling, and visualization.

### Step 1: Data Cleaning & Preparation
- Removed duplicates and missing values.
- Standardized date formats and product categories.
- Ensured all monetary values were consistent (USD).

### Step 2: Data Modeling
- Defined calculated measures (Total Revenue, Total Profit, Profit Margin, etc.).
- Used DAX formulas and Excel pivot calculations to enhance accuracy.

### Step 3: Visualization & Interactivity
- Developed two dashboards using **Excel Pivot Charts**, **Slicers**, and **VBA automation buttons**.
- Added **dynamic filters** (country, region, product, and channel).
- Implemented a **“Reset All Filters” VBA button** for easy dashboard refresh.

---

## Dashboard Features

### 1️⃣ Sales Performance Dashboard (2024)
**Focus:** Profit, Revenue, and Product-Level Metrics  

**Key Features:**
- **Monthly Revenue Trend (Jan–Dec 2024):** Tracks revenue fluctuations throughout the year.  
- **Product Profit Breakdown:** Highlights top categories by profit.  
- **Revenue by Channel:** Compares Online vs. Offline performance.  
- **Order Priority Split:** Visualizes distribution of Critical, High, Medium, and Low orders.

**Top Metrics:**
| Metric | Value |
|:--|:--|
| Total Unit Sold | 500M |
| Total Revenue | $133.6B |
| Total Profit | $39.4B |
| Average Profit Margin | 29% |
| Top Country | Sudan |

**Product Profit Breakdown:**
| Category | Profit ($B) |
|:--|:--|
| Cosmetics | 7.3 |
| Household | 6.9 |
| Office Supplies | 5.3 |
| Baby Food | 4.0 |
| Cereal | 3.7 |
| Clothes | 3.1 |

> **Insight:** Cosmetics and Household categories are the biggest profit drivers, collectively contributing over **35% of total profit**.

<img width="1048" height="534" alt="Sales Performance 1" src="https://github.com/user-attachments/assets/71e754af-800a-4c86-bf89-213f2b250bfc" />


---

### 2️⃣ Regional & Operational Performance Dashboard (2024)
**Focus:** Regional Profitability, Shipping, and Order Efficiency  

**Key Features:**
- **Profit by Country & Region:** Displays comparative performance globally.  
- **Monthly Profit Trend:** Visualizes profitability trends over time.  
- **Operational Metrics:** Average shipping days and profit per order.  

**Regional Profit Breakdown:**
| Region | Profit ($B) |
|:--|:--|
| Sub-Saharan Africa | 10.3 |
| Europe | 10.1 |
| Asia | 5.7 |
| MENA | 5.0 |
| Central America & Caribbean | 4.3 |
| Australia & Oceania | 3.2 |
| North America | 0.87 |

**Top 10 Countries by Profit:**
1. Sudan – $249.5M  
2. Nigeria – $241.9M  
3. Morocco – $241.0M  
4. Libya  
5. Australia  
6. Benin  
7. New Zealand  
8. Bahrain  
9. Marshall Islands  
10. Malta  

> **Insight:** Sub-Saharan Africa and Europe dominate profitability, accounting for over **50% of total company profit**.

<img width="936" height="537" alt="Sales Performance 2" src="https://github.com/user-attachments/assets/bb066512-ce9a-4342-a4fe-1de93edc86e8" />


---

## Key Insights

- **Top-Performing Country:** Sudan leads in profit and sales volume.  
- **Top Product Category:** Cosmetics generates the highest profit.  
- **Regional Dominance:** Sub-Saharan Africa and Europe outperform all other regions.  
- **Balanced Sales Channels:** Online and Offline each account for 50% of revenue.  
- **Mid-Year Performance Peak:** Profit and revenue were highest between **March–June 2024**.  
- **Operational Delays:** Average shipping days (25) indicate room for logistical improvement.

---

## Tools Used

| Tool | Purpose |
|:--|:--|
| **Microsoft Excel** | Data cleaning, analysis, and dashboard visualization |
| **VBA (Visual Basic for Applications)** | Automation (Reset Filters, interactivity) |
| **Pivot Tables & Charts** | Data aggregation and trend visualization |
| **Slicers** | Dynamic filtering |

---

## VBA Code

<img width="564" height="447" alt="Pivot Table Automated" src="https://github.com/user-attachments/assets/129b67db-7a4c-42e6-a84e-b9f8aed6f38d" />

<img width="542" height="495" alt="Export Report VBA" src="https://github.com/user-attachments/assets/aad57266-600b-45cf-8747-2c028608a990" />

<img width="564" height="445" alt="Reset VBA" src="https://github.com/user-attachments/assets/44309e0f-d905-4738-8834-5b464d99c218" />


---

## Overall Performance Summary

| Aspect | Highlight |
|:--|:--|
| Strongest Market | **Sudan (Sub-Saharan Africa)** |
| Top Product | **Cosmetics** |
| Channel Performance | **50% Online / 50% Offline** |
| Profit Trend | **Peaked Mid-Year (Mar–Jun)** |
| Regional Leaders | **Africa & Europe** |
| Weak Spots | **Late-Year Decline in Profit and Shipping Delays** |

> The company’s profitability is strong, driven by African and European markets, but late-year operational inefficiencies highlight the need for supply chain optimization.

---

## Conclusion

The 2024 dashboard successfully provided a **unified performance view** across departments, enabling leadership to:
- Track real-time sales performance.  
- Compare product and regional profitability.  
- Identify operational bottlenecks.  

Through Excel automation and visualization, the project demonstrated the **power of accessible business intelligence tools** even without advanced BI software.
