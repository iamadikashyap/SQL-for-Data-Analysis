# SQL-for-Data-Analysis


# 🛒 SQL for Data Analysis – Ecommerce_SQL_Database (Google Colab)

## 🎯 Objective
To learn and apply SQL techniques to analyze an Ecommerce dataset using **Google Colab + SQLite**.

This project demonstrates how to:
- Create and manage relational tables  
- Use SQL queries to extract and analyze data  
- Perform aggregations, joins, subqueries, and create views  
- Optimize queries using indexes  

---

## 🧰 Tools Used
- **Google Colab** — interactive notebook environment  
- **SQLite3** — lightweight SQL database (no installation required)  
- **Pandas** — to display query results as tables  

---

## 🗂️ Dataset: Ecommerce_SQL_Database
The database contains 5 interconnected tables:

| Table | Description |
|--------|-------------|
| **customers** | Customer details (name, city, signup date) |
| **products** | Product details (category, price) |
| **orders** | Order-level data (order date, total amount) |
| **order_items** | Product quantity per order |
| **shipping** | Shipping status and delivery details |

All tables and sample data are **automatically created** when you run the setup cell in Colab — no external file needed.

---

## 🧠 SQL Tasks Performed

| # | Task | SQL Concept |
|---|------|-------------|
| 1 | View all customers | `SELECT` |
| 2 | Filter customers by city | `WHERE` |
| 3 | Count orders per customer | `JOIN`, `GROUP BY` |
| 4 | Find highest order value | `ORDER BY DESC`, `LIMIT` |
| 5 | Calculate average product price by category | `AVG()`, `GROUP BY` |
| 6 | Join multiple tables (order + product + shipping) | `INNER JOIN` |
| 7 | Identify top spenders (> ₹50,000) | Subquery, `HAVING` |
| 8 | Create customer spending summary | `CREATE VIEW` |
| 9 | Optimize query performance | `CREATE INDEX` |

---

## ⚙️ How to Run This Project in Google Colab

1. Open **[Google Colab](https://colab.research.google.com/drive/1qLj8xx6t9NcP35Ls7l_aZuHGcc3SK9mv?usp=sharing)**  
2. Copy-paste the provided SQL + Python code cells  
3. Run each cell in order (Setup → Create Tables → Run Queries)  
4. View results directly in the output cells  
5. Take screenshots of query outputs for submission  

---

## 📸 Deliverables
- `Ecommerce_SQL_Database.db` (auto-created SQLite file)  
- `README.md` (this document)  
- Colab notebook (`.ipynb`)  
- Screenshots of query results  

---

## 🏁 Outcome
After completing this project, you will be able to:
- Work with relational data using SQL  
- Write complex queries with joins and subqueries  
- Summarize and analyze data using aggregate functions  
- Create views and indexes for better performance  
- Integrate SQL workflows seamlessly in Google Colab  

---

✅ **Developed and Tested on Google Colab using SQLite3**
