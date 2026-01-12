# Customer Value & Channel Performance Analysis

This project analyzes e-commerce customer behavior and acquisition channel performance to identify the main drivers of revenue and retention opportunities.  
Using SQL and Power BI, the analysis focuses on understanding how repeat customers contribute to revenue and how different marketing channels impact customer value.

---

## Business Objective

The main goals of this analysis are:
- Identify how revenue is distributed between one-time and repeat customers.
- Measure the contribution of repeat customers to total revenue.
- Evaluate acquisition channel performance in terms of scale and customer value.
- Provide actionable insights to support retention-focused growth strategies.

---

## Dataset

**Source:** Google BigQuery Public Dataset  
`bigquery-public-data.thelook_ecommerce`

**Main tables used:**
- `order_items`: transactional data at item level.
- `users`: customer information, including acquisition channel (`traffic_source`).

---

## Methodology

1. Performed exploratory analysis to understand order volume and revenue distribution.
2. Segmented customers into **one-time** and **repeat** buyers based on purchase behavior.
3. Analyzed revenue concentration by customer type.
4. Evaluated acquisition channels by:
   - Total revenue
   - Averag

