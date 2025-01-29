# Ecommerce Data Warehouse – Snowflake & Azure  

## Overview  
This project is a continuation of the **Ecommerce Data Model and Analysis** project, where we previously focused on creating a relational data model and performing ecommerce analytics. In this phase, we **transform the relational model into a dimensional model** using **Snowflake** and **Azure**, leveraging cloud data warehousing for enhanced analytics capabilities.  

By integrating **Snowflake's scalable architecture** with **Azure services**, we enable efficient **data ingestion, storage, and processing** to extract valuable insights from ecommerce transactions.  

---

## Architecture & Technologies  
- **Snowflake** – Cloud-based data warehouse for scalable analytics  
- **Azure Storage** – Data ingestion and storage integration  
- **SQL** – Querying and data transformation  
- **Dimensional Modeling** – Fact and dimension table design  

---

## Project Flow  
1. **Set up Snowflake & Azure Storage**  
   - Ensure access to a **Snowflake account** and **Azure Storage account**  
2. **Data Ingestion into Snowflake**  
   - Execute `staging.sql` to create staging tables and load raw data into Snowflake  
3. **Dimensional Model Implementation**  
   - Execute `dimensional_model.sql` to create **fact tables** (measurable metrics) and **dimension tables** (descriptive attributes)  
4. **Run Analytical Queries**  
   - Execute queries from `practice_questions.sql` to extract ecommerce insights  

---

## Dimensional Model  
The **dimensional model** consists of:  

### Fact Table:  
- `fact_orders` – Stores transaction details (order_id, user_id, total_products, reordered_count, etc.)  

### Dimension Tables:  
- `dim_users` – User details  
- `dim_products` – Product catalog  
- `dim_departments` – Department information  
- `dim_aisles` – Aisle details  
- `dim_time` – Date & time attributes for trend analysis  

---

## Analytical Queries  
The project includes **advanced SQL queries** to analyze ecommerce trends:  

- 📌 **Total number of products ordered per department**  
- 📌 **Top 5 aisles with the highest number of reordered products**  
- 📌 **Average number of products added to the cart per order by day of the week**  
- 📌 **Top 10 users with the highest number of unique products ordered**  

These queries help in understanding **customer behavior, purchasing patterns, and product demand** across different categories.  

---
