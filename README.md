# Data-analyst-internship-task-4

# E-Commerce SQL Analysis Project

## 📌 Project Overview
This project contains SQL scripts and queries for analyzing an **E-commerce database**.  
The dataset includes tables for customers, products, orders, campaigns, suppliers, and more.  
Queries are written for **PostgreSQL** and executed using **pgAdmin 4**.

---

## 📂 Dataset Tables
The database consists of the following CSVs (imported into PostgreSQL):

| Table Name                  | Description |
|-----------------------------|-------------|
| `category`                  | Product categories |
| `subcategory`               | Product subcategories |
| `product`                   | Product details |
| `supplier`                  | Supplier information |
| `customer`                  | Customer details |
| `orders`                    | Orders placed by customers |
| `orderitem`                 | Items within each order |
| `payment_method`            | Payment method details |
| `returns`                   | Returned orders and reasons |
| `marketing_campaigns`       | Campaign data |
| `campaign_product_subcategory` | Mapping of campaigns to subcategories |
| `customer_product_ratings`  | Ratings given by customers |

---

## 🛠 SQL Features Used
The queries demonstrate the use of:
- **Basic SQL**
  - `SELECT`, `WHERE`, `ORDER BY`, `GROUP BY`
- **Joins**
  - `INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`
- **Aggregate Functions**
  - `SUM()`, `AVG()`, `COUNT()`
- **Subqueries**
  - Used for filtering and advanced analysis
- **Views**
  - Created for reusable reports
- **Indexes**
  - Suggested for performance optimization

---

## 📊 Example Analysis Queries
Some of the key queries in this project include:
1. Top-selling products by revenue
2. Most active customers by number of orders
3. Average rating per product category
4. Sales performance of marketing campaigns
5. Return rate analysis by supplier
6. Monthly sales trend analysis

---

## 📁 Project Structure
ecommerce_sql_project/
│
├── data/ # CSV datasets
│ ├── category.csv
│ ├── subcategory.csv
│ ├── product.csv
│ ├── ...
│
├── queries/ # SQL scripts
│ ├── create_tables.sql
│ ├── insert_data.sql
│ ├── analysis_queries.sql
│ ├── views.sql
│
└── README.md # Project documentation

**Import Tables**
Use pgAdmin's Import/Export to load CSVs.
Or run create_tables.sql and insert_data.sql.

**Run Queries**

Open analysis_queries.sql in pgAdmin's Query Tool and execute.

 **Author**
Deepak Kumhar
📧 Contact: (deepakkumhar129@gmail.com)
📅 Year: 2025
