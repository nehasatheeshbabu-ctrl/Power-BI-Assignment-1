# Power BI Assignment 1 – Data Transformation & Data Modeling: E-Commerce Sales Analysis

## 📌 Project Overview
This project explores e-commerce sales data analysis using **Microsoft Power BI**[span_0](start_span)[span_0](end_span). The objective of this assignment is to practice end-to-end data ingestion, Power Query transformations, data modeling, and sales performance analysis using provided e-commerce datasets[span_1](start_span)[span_1](end_span).

---

## 📂 Dataset Description
The project utilizes three CSV files[span_2](start_span)[span_2](end_span):
1. **`List of Orders.csv`**[span_3](start_span)[span_3](end_span) – Contains order-level details including Order ID, Order Date, Customer Name, and location details[span_4](start_span)[span_4](end_span).
2. **`Order Details.csv`**[span_5](start_span)[span_5](end_span) – Contains line-item transaction details including Order ID, Amount, Profit, Quantity, and Product Categories[span_6](start_span)[span_6](end_span).
3. **`Sales target.csv`**[span_7](start_span)[span_7](end_span) – Contains monthly sales target benchmarks across different product categories[span_8](start_span)[span_8](end_span).

---

## 🛠️ Key Steps & Transformations Performed

### 1. Data Ingestion
* Imported `List of Orders.csv` into Power BI Desktop[span_9](start_span)[span_9](end_span).
* Opened the dataset in **Power Query Editor** using the *Transform Data* option[span_10](start_span)[span_10](end_span).
* Imported `Order Details.csv` and `Sales target.csv` directly into Power Query Editor[span_11](start_span)[span_11](end_span).

### 2. Data Transformation (Power Query)
* **Row Filtering:** Restricted the `List of Orders` table to the top **500 rows**[span_12](start_span)[span_12](end_span).
* **Date Formatting:** Verified and set the `Order Date` column in `List of Orders` to the **Date** data type[span_13](start_span)[span_13](end_span).
* **Currency/Decimal Formatting:** Updated the `Amount` and `Target` columns to **Fixed Decimal Number** for accurate financial calculations[span_14](start_span)[span_14](end_span).
* **Text Standardization:** Formatted the `CustomerName` column to **Proper Case** (Capitalize Each Word) to ensure consistent naming conventions[span_15](start_span)[span_15](end_span).

### 3. Data Modeling & Analysis
* Established relationships between `List of Orders`, `Order Details`, and `Sales target` in the Model view[span_16](start_span)[span_16](end_span).
* Analyzed actual sales performance against defined sales targets[span_17](start_span)[span_17](end_span).

---
