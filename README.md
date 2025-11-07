# 🛍️ Customer Shopping Trend Analysis: 
## 🎯 Project Overview & Business Value

This analytical initiative is focused on leveraging **3,500 transactional records** to understand the core drivers of sales performance and customer retention. The primary objective was to dissect purchase behaviors, identify high-value customer segments, and provide **actionable insights** to optimize marketing spend and the subscription model for sustained revenue growth.

**Key Performance Indicators (KPIs):**

| Metric | Value | Insight |
| :--- | :--- | :--- |
| **Total Revenue** | **$209K** | Overall portfolio performance baseline. |
| **Active Customers** | **3.5K** | The size of the consumer base analyzed. |
| **Avg. Purchase Amount** | **$59.71** | Used as the benchmark for segment performance. |
| **Subscription Status** | Yes: 30.09% | A key focus area for loyalty-based monetization. |

---

## 🛠️ Technology Stack & Data Pipeline

The project utilized a robust pipeline for data preparation, querying, and visualization:

| Tool | Role | Process / Deliverable |
| :--- | :--- | :--- |
| **Python** (Pandas, NumPy) | **Data Preparation & Cleaning** | Imputed **37 missing values** in `Review Rating` using category median and performed **Feature Engineering** (`age_group`). |
| **SQL** (PostgreSQL) | **Data Aggregation & Metrics** | Loaded cleaned data for complex querying (e.g., Discount rate by product, Revenue by age/gender). |
| **Power BI** | **Interactive Dashboard** | Built the final **Customer Trend Dashboard** to present all strategic insights visually. |

---

## 📈 Strategic Business Recommendations (Final Report Version)

### I. High-Impact Actions
Based on the SQL query results, the following actions are the most impactful for revenue growth and margin control:

1.  **Maximize Gender/Age Focus (Targeting):**
    * **Action:** Invest in highly targeted marketing campaigns aimed at the **Male segment** and the **Middle-aged group** (highest revenue contributors).
    * **Goal:** Capitalize on the most valuable existing customer segments for maximum **Return on Ad Spend (ROAS)**.

2.  **Address Discount-Dependency (Margin Control):**
    * **Action:** Re-evaluate the discount strategy for high-volume, discount-dependent items like **Hat (59.00% discount rate)** and **Sneakers (55.00% discount rate)**.
    * **Goal:** Protect profit margins by substituting deep discounts with value-added bundles or loyalty points.

3.  **Optimize Loyalty Conversion (Retention):**
    * **Action:** Design targeted campaigns (e.g., email sequences, special offers) to convert the **628 Returning customers** into the highly stable **Loyal segment (2,802 customers)**.
    * **Goal:** Increase the **Customer Lifetime Value (CLTV)** by moving repeat buyers into the most retained group.

> **❗️ NOTE ON SUBSCRIPTION DATA:** The raw SQL data showed **Non-Subscribers** had a negligibly higher average spend (**$59.81**) than Subscribers (**$59.49**). The largest opportunity lies in converting the high volume of Non-Subscribers (**69.91%** of base).

### II. Secondary Insights & Product Health
* **Top Revenue Categories:** The **Clothing** and **Accessories** categories are the highest revenue drivers.
* **Top-Rated Products:** Prominently feature top-rated products like **Gloves (3.89 avg. rating)** and **Sandals (3.85 avg. rating)** in marketing to build trust.

---

## 🖼️ Dashboard Snapshots

Here is a visual overview of the final Power BI dashboard for the Customer Shopping Trend Analysis:

\[Insert your dashboard image here using Markdown format: `![Dashboard Main View](path/to/your/image.png)`]

---
## 📁 Repository Structure

The project files are organized into functional folders for clarity and professional review:

| Folder | Content |
| :--- | :--- |
| **`Power BI Project File/`** | Contains the working Power BI Desktop file (`Customer Trend Dashboard.pbix`). |
| **`Data/`** | Contains the source data file (`Customer_shopping_RAW_data.xls`). |
| **`Code/`** | Contains the Python Jupyter notebook (`Customer_shopping_trends_EDA.ipynb`) for data cleaning and EDA. |
| **`SQL/`** | Contains the **SQL** file (`Customer Trend Analysis SQL.sql`) with all custom database queries used for metric generation. |
| **`Image/`** | Contains dashboard snapshot images used in the `README.md` file. |
| **`Documentation/`** | Contains all final deliverables: PDF Report, PPT Presentation, and other supporting documentation. (`Customer Shopping Trend - REPORT PDF.pdf`, `Customer Shopping Trend Analysis - PPT.pdf`) |
| **`README.md`** | This file: Project summary, KPIs, and recommendations. |
| **`LICENSE`** | The project's open-source license file. |


## 📜 License

This project is open-source and released under the **MIT License**.