# 🏙️ Sky Curtains: Market Expansion & Product Insights

## 📌 Project Overview
**Sky Curtains**, a company specializing in electric curtains, aims to identify growth opportunities and optimize operational efficiency. 

This project is a comprehensive **Business Case Study** designed to analyze sales performance across different regions, customer behavior, and product categories to answer the critical question: **"Where should the company expand next?"**

## 🛠️ Technical Solution & Workflow

### 1. Data Transformation (Power Query)
Connected raw Excel data to Power BI and performed essential cleaning and enrichment:
* **Data Cleaning:** Removed blank rows and filtered out irrelevant records to ensure data quality.
* **Key Generation:** Created a custom `Sales Rep ID` column to establish a relationship between the `Sales` and `Rep` tables (Handling missing keys).
* **Date Dimension:** Built a standard `Dim_Date` table for time-intelligence analysis.

### 2. Data Modeling (Star Schema) ⭐
Designed a Star Schema model to optimize performance and filter propagation:
* **Fact Table:** `Fact_Sales`
* **Dimension Tables:** `Dim_Rep`, `Dim_Target`, `Dim_Date`.
<img width="1050" height="844" alt="Data Modeling " src="https://github.com/user-attachments/assets/f8251b77-98e5-43ba-bee5-d737713dbde3" />

### 3. DAX & Key Metrics
Developed measures to track financial and operational health:
* **Financials:** `Total Revenue`, `Achievement %`, `Monthly Growth Rate`.
* **Operational:** `Avg Installation Time (Days)`, `Total Quantity`.
* **Customer Centric:** `CRR` (Customer Retention Rate), `Avg Customer Satisfaction`.

---

## 📊 Executive Summary & Strategic Insights

### 1. Overall Financial Performance
* **Revenue Growth:** Generated **$7.09M** in total revenue, marking a **14.4% increase** from the previous month.
* **Target Achievement:** The company exceeded expectations with an **116% Achievement Rate**.
* **Volume:** A customer base of **388 clients** purchased **1.51K units**.

### 2. Operational Efficiency & Service Quality (Critical Findings) ⚠️
* **Customer Retention:** The **CRR is 45.68%**, indicating a need for retention strategies.
* **Satisfaction Gap:** Average Customer Satisfaction is **4.29**, which is **0.7 points below target**.
* **Installation Bottleneck:** Average Installation Time is **3.05 Days** (0.82 days above target).
* **Key Correlation:** An **inverse correlation** was found between *Installation Time* and *Customer Satisfaction*. (Longer installation = Unhappy customers).

### 3. Top Performers
* **Top Area:** **Cairo** leads the market with **$1.4M** in sales.
* **Top Category:** **Premium** curtains are the highest revenue generator.
* **Top Sales Rep:** **Lina** is the top-performing representative with **$2.1M** sales.

---

## 💡 Recommendations (Action Plan)

Based on the data analysis, the following actions are recommended for Sky Curtains:

### 1. Investment & Expansion 🚀
* **Focus on Cairo:** Concentrate marketing efforts and resources in **Cairo** as it demonstrates the highest ROI and volume.
* **Push Premium Products:** Prioritize the **Premium** category inventory and marketing, as it drives the majority of revenue.

### 2. Operational Improvement 🔧
* **Reduce Installation Time:** Immediate action is needed to lower the avg. installation time (currently 3.05 days). The data proves that faster installation directly leads to higher customer satisfaction scores.

---

## 📷 Dashboard Snapshot
<img width="1503" height="867" alt="Dashboard" src="https://github.com/user-attachments/assets/d1ce24e6-b117-4661-a1bc-bc163e7564e0" />

## 🚀 How to Run
1.  Download the `.pbix` file.
2.  Open in Power BI Desktop.
3.  Check the "Summary" page for the visualized insights.
