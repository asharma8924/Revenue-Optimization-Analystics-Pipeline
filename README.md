# Revenue Optimization Analytics Pipeline

## Overview
This project focuses on building an end-to-end data analytics pipeline to analyze e-commerce transaction data and uncover key drivers of revenue. The goal was to transform raw data into actionable insights related to customer behavior, product performance, and overall business growth.

---

## Dataset
This project uses a publicly available e-commerce dataset containing 20,000+ transaction-level records spanning a 12-month period.

Key attributes include:
- Customer demographics (age, gender, loyalty status)
- Product details (type, SKU)
- Transaction metrics (quantity, unit price, total price)
- Order information (status, payment method, shipping type)
- Purchase dates for time-based analysis

---

## Tech Stack
- **PostgreSQL** – Data storage and transformation
- **SQL** – CTEs, window functions, aggregations
- **Power BI** – Dashboarding and visualization
- **ETL Pipeline** – Raw → Staging → Analytics layers

---

## Data Pipeline Architecture
The project follows a structured data pipeline:

- **Raw Layer**: Ingested unprocessed CSV data  
- **Staging Layer (stg)**: Cleaned and transformed data types  
- **Analytics Layer (mart)**: Aggregated tables for reporting  

This design improves scalability, maintainability, and query performance.

---

## Key Features
- Built a PostgreSQL data warehouse to process 20K+ records  
- Performed data cleaning and transformation using SQL  
- Implemented advanced SQL logic using:
  - Common Table Expressions (CTEs)
  - Window functions
- Created interactive Power BI dashboards with filters and KPIs  
- Designed data models to support business analysis  

---

## Key Insights
- Loyalty members showed higher overall customer value  
- Add-on products contributed to increased average order value  
- Cancellation patterns revealed potential revenue loss areas  
- Product performance varied significantly across categories  

---

## Dashboard
The Power BI dashboard includes:
- Revenue Overview  
- Product Performance  
- Customer Loyalty Impact  
- Time-based Sales Trends  

---

## Challenges & Learnings
One of the main challenges was optimizing query performance on large datasets. This was addressed by using efficient SQL transformations, CTEs, and structuring the data into multiple layers.

This project strengthened my skills in:
- Data modeling and warehousing  
- Writing optimized SQL queries  
- Translating data into business insights  
- Building interactive dashboards  

---

## How to Run This Project
1. Import the dataset into PostgreSQL  
2. Run SQL scripts to create staging and analytics tables  
3. Connect Power BI to the database  
4. Load and explore the dashboards  

---

## Future Improvements
- Automate data ingestion using scheduled pipelines  
- Integrate real-time data streaming  
- Enhance predictive analytics using machine learning models  

---

## Author
Angad Sharma  
