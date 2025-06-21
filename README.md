# 🛒 FMCG Sales Analysis Dashboard

This repository contains a comprehensive sales analysis of a supermarket operating in the Fast-Moving Consumer Goods (FMCG) sector. The analysis was performed using **Microsoft Power BI**, transforming raw transactional data into a multi-faceted, interactive dashboard designed to provide actionable insights for business stakeholders.

---

## 🎯 Project Goal

The primary objective of this project was to analyze three months of sales data to identify key trends, evaluate performance across different branches and product categories, and understand customer purchasing behavior. The goal was to move beyond simple reporting to create a diagnostic tool that could answer critical business questions and support data-driven decision-making.

---

## 🛠️ Technical Skills and Process

- **Data Modeling**: The raw CSV data was loaded into Power BI and transformed into a robust **Star Schema**. This involved creating a central `Sales` fact table and connecting it to `Products` and `Calendar` dimension tables, ensuring optimal performance and scalability.

- **DAX (Data Analysis Expressions)**: Over 15 DAX measures were created to calculate key business metrics, including:
  - **Time intelligence measures** (e.g., `Sales Last Month`, `Month-over-Month Growth`)
  - **Advanced KPIs** (e.g., `Average Transaction Value`, `Average Items per Transaction`)
  - **Conditional formatting measures** to dynamically highlight performance against targets.

- **Data Visualization**: A multi-page report was designed with a focus on user experience, interactivity, and clear data storytelling.

- **Power Query (M Language)**: A dynamic and reusable calendar table was built using M language to support all time-based analysis.

---

## 📖 The Dashboard: A Page-by-Page Story

The final report consists of five distinct pages, each designed to answer a specific set of business questions.

### 1. 📈 Key Performance Indicators (KPI) Overview

<img width="1280" alt="1" src="https://github.com/user-attachments/assets/4eec0819-a4dd-4b35-b258-cbf71a488c73" />

**Purpose**: To provide a high-level executive summary of the business's overall health at a glance.

**Key Insights & Visuals**:
- **Core Metrics**: The dashboard leads with crucial KPIs, including **Total Revenue ($307.59K)**, **Total Profit ($15.38K)**, and **Total Transactions (1,000)**.
- **Operational Efficiency**: Metrics like **Average Transaction Value ($307.59)** and **Average Items per Transaction (5.51)** provide insight into customer basket size and purchasing power.
- **Month-Over-Month Performance**: A dedicated KPI visual shows that **revenue grew by 12.59%** over the previous month.
- **Daily Revenue Trend**: A line chart tracks daily revenue fluctuations, identifying outlier days and helping understand revenue velocity over time.

---

### 2. 🏢 Branch Performance

<img width="1280" alt="1" src="https://github.com/user-attachments/assets/f1728149-50aa-414a-b4dc-6d55b52fb3d5" />

**Purpose**: To analyze and compare the sales and profitability of the supermarket's different city branches.

**Key Insights & Visuals**:
- **Sales vs. Profit**: Side-by-side visuals reveal that while **Naypyitaw** generates the highest revenue (**$111K**), its profitability (**$5.3K**) is only marginally higher than other branches, indicating potential differences in **product mix** or **operational costs**.
- **Customer & Payment Segmentation**: Donut charts show that **"Member" customers make up 56.5% of transactions**, and payment methods are evenly split across **Cash**, **Credit Card**, and **E-wallet**.
- **Interactivity**: Slicers for **Customer Type** and **Payment Method** allow users to dynamically explore segment-specific performance within each branch.

---

### 3. 📦 Product Performance

<img width="1280" alt="1" src="https://github.com/user-attachments/assets/8c171150-90ef-46af-9541-ff6b54b51f16" />

**Purpose**: To understand which product categories are driving revenue and sales volume.

**Key Insights & Visuals**:
- **Revenue vs. Volume**: "Food and beverages" lead in **revenue ($56K)**, while "Electronic accessories" top the **unit sales (971)**.
- **Balanced Portfolio**: The top five product lines each contribute about **16-17%** of total revenue — showing a well-diversified product portfolio with no single point of failure.

---

### 4. ⏰ Time Trends

<img width="1280" alt="1" src="https://github.com/user-attachments/assets/f92cc22e-4fb8-4a6b-b671-f259907f3017" />

**Purpose**: To analyze sales patterns over different time granularities (monthly and daily).

**Key Insights & Visuals**:
- **Monthly Performance Dip**: A clear **sales dip in February** is followed by a strong **recovery in March** — suggesting a need for deeper analysis (e.g., holidays, stockouts, promotions).
- **Weekly Sales Rhythm**: **Saturday** is the highest-performing day of the week, averaging **$4.3K** in sales — helpful for staffing and promotional planning.

---

### 5. 👥 Customer Insights

<img width="1280" alt="1" src="https://github.com/user-attachments/assets/20745331-cadb-4922-a29f-d7f5ec69cb5c" />

**Purpose**: To perform a deep-dive analysis into the purchasing behavior of different customer segments, specifically by gender.

**Key Insights & Visuals**:
- **Average Spend Analysis**: **Males spend more per visit ($324.70)** compared to **Females ($284.81)** on average.
- **Product Preference by Gender**: Males dominate spending on **"Health and beauty"**, while Females lead in **"Fashion accessories"**.
- **Trend Analysis by Segment**: A line chart reveals that the **February sales dip** was more pronounced among **male customers**, showing segmentation-driven seasonality.

---

## ✨ Conclusion

This Power BI dashboard successfully transforms raw transactional data into a powerful analytical tool. It provides a clear, 360-degree view of business performance and delivers actionable insights that can help stakeholders optimize marketing strategies, improve operational efficiency, and drive profitable growth.
