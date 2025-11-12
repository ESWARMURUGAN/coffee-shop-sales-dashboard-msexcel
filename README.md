# Coffee Shop Sales Performance Analysis & Dashboard using Microsoft Excel

---

## Executive Summary

This project demonstrates the use of **Microsoft Excel** as a powerful tool for end-to-end **Data Analysis and Business Intelligence (BI)**. I transformed raw transactional data from a coffee shop into a dynamic, interactive dashboard, providing management with clear insights to optimize sales, staffing, and marketing efforts.

| Component | Detail | Business Impact |
| :--- | :--- | :--- |
| **Business Objective** | Analyze sales data to understand performance variation by time, location, and product, aiming to **improve overall sales performance**. | Enabled **data-driven decision-making** for resource allocation and marketing spend. |
| **Tool & Methodology** | Used **MS Excel** features including **Power Query** for ETL and **Pivot Tables/Charts** for the analytical model and visualization. | Created a **fully dynamic dashboard** where filtering by month/day instantly updates all key metrics. |
| **Key Metrics Tracked** | Total Sales, Customer Footfall, Average Bill per Person, Average Order per Person. | Established **key performance indicators (KPIs)** for monitoring operational efficiency and customer behavior. |
| **Project Outcome** | A professional, single-sheet Sales Dashboard that is easily updated and requires **no specialized BI software** for viewing by non-technical managers. | Delivered a scalable and highly accessible reporting solution. |

---

## Business Questions Driving the Analysis 💡

The core goal of this project was to answer critical questions about sales performance to identify areas of waste, growth opportunity, and operational efficiency:

1.  **Sales Trends:** What is the **Total Sales Revenue** generated for each month?

2.  **Daily & Weekly Fluctuation:** How do **Sales Vary by Day of the Week** (e.g., peak performance on weekends vs. weekdays)?

3.  **Peak Hours & Staffing:** Are there any **Peak Times of Sales Activity** (by hour of the day) that require adjusted staffing levels?

4.  **Geographic Performance:** How are sales performing across **different store locations**?

5.  **Customer Behavior:** What is the **Average Bill and Average Order Size** to inform upselling strategies?

---

## Methodology: Data Analysis Workflow in Excel

The project followed a standard analytical workflow, leveraging advanced Excel capabilities:

### 1. Data Cleaning and Preparation (Power Query)

* **ETL:** Imported and connected the raw transactional sales data into the **Power Query Editor**.
  
* **Data Transformation:** Crucial steps were taken to standardize the data, including:
    * **Size Standardization:** Separating product size indicators (e.g., "LG," "RG," "SM" for Large, Regular, Small) from the main Product Name column to enable clear analysis by size category.
  
    * **Data Type Integrity:** Ensuring columns like `Sales`, `Price`, and `Revenue` were correctly formatted as decimals/currency, and Date/Time fields were usable for time-series analysis.

### 2. Analytical Modeling (Pivot Tables)

The cleaned data was used to construct multiple **Pivot Tables**. These tables serve as the analytical engine, summarizing the raw data into the metrics required for the dashboard visuals.

* **Metric Calculation:** Each Pivot Table focused on aggregating a specific metric (e.g., Total Sales by Month, Footfall by Hour of Day) to create the source data for the charts.

> **Visual: Pivot Tables – The Analytical Engine**
> *This image showcases the underlying Pivot Tables that structure the data and perform all the complex calculations for the final dashboard visuals.*
>
> ![Excel Pivot Tables used for sales metric calculation](https://github.com/ESWARMURUGAN/coffee-shop-sales-dashboard-msexcel/blob/0f5230bdf21f5532e6bfb4793679e5c401677e28/pivot_tables.png)

### 3. Visualization and Interactivity

* **Dashboard Layout:** Charts and KPIs were designed and placed on a dedicated **Dashboard Sheet** to provide a clear, one-page view of performance.
* **Dynamic Filtering:** **Slicers** were inserted and connected to all Pivot Tables. Slicers for **Month Name** and **Day of the Week** provide complete interactivity, allowing users to instantly segment sales data by any time period.

---

## Final Findings and Recommendations 💰

The completed dashboard offers actionable insights for management to improve profitability:

> **Visual: Coffee Shop Sales Analysis Dashboard**
> *This is the final, interactive dashboard used by management to track all key sales performance indicators.*
>
> ![Final, interactive Coffee Shop Sales Analysis Dashboard in MS Excel](https://raw.githubusercontent.com/ESWARMURUGAN/coffee-shop-sales-dashboard-msexcel/0ca28f42acf713dd3a6b5f5345ed134f2e4977c5/coffe_shop_sales_analysis_dashboard.png)

### Business Findings

* **Peak Time Insight:** The analysis clearly isolates the **peak sales hours** (e.g., 9 AM - 11 AM and 2 PM - 4 PM), which contribute the highest proportion of daily revenue.
* **Revenue Concentration:** Revenue is highly concentrated on specific days of the week, necessitating tailored marketing efforts on slower days to smooth revenue flow.
* **Customer Size:** The **Average Bill per Person** metric provides a benchmark for staff training, indicating if upselling attempts (e.g., suggesting a pastry with a coffee) are successful in increasing transaction value.

### Operational Recommendations

1.  **Staffing Optimization:** Schedule the highest-performing baristas and the greatest number of staff during the identified peak hours to **maximize customer throughput** and minimize wait times during busy periods.

2.  **Targeted Promotions:** Implement **Happy Hour or discounted bundled promotions** (e.g., coffee and breakfast item combos) during the slowest hours of the day to drive footfall during off-peak times.

3.  **Product Strategy:** Use the size-segmented product analysis to identify which product sizes (Small, Regular, Large) are most popular for the highest-margin items, guiding future inventory and procurement decisions.
