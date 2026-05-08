# 🚗 BMW Sales Analysis using SQL

![SQL](https://img.shields.io/badge/SQL-MySQL-blue?style=for-the-badge&logo=mysql)
![Project](https://img.shields.io/badge/Project-Completed-brightgreen?style=for-the-badge)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-Business%20Insights-orange?style=for-the-badge)

---

# 📌 Project Overview

This project focuses on analyzing BMW sales data using SQL to uncover valuable business insights related to:

- 📈 Sales trends
- 🌍 Regional performance
- ⛽ Fuel type preferences
- ⚙️ Transmission trends
- 💰 Pricing analysis
- 🚘 Top-selling BMW models

The project demonstrates how SQL can be used to transform raw automotive sales data into actionable business insights.

---

# 🎯 Objectives

- Analyze BMW sales performance across different regions
- Identify the most expensive and top-selling BMW models
- Understand customer preferences for fuel type and transmission
- Evaluate mileage and pricing trends
- Perform business analysis using SQL queries

---

# 🛠️ Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| MySQL | Data Querying & Analysis |
| SQL | Data Analysis |
| GitHub | Project Hosting |

---

# 🗂️ Dataset Features

| Column Name | Description |
|-------------|-------------|
| Model | BMW vehicle model |
| Year | Manufacturing/Sales year |
| Region | Sales region |
| Color | Vehicle color |
| Fuel_Type | Fuel category |
| Transmission | Manual/Automatic |
| Engine_Size_L | Engine size |
| Mileage_KM | Vehicle mileage |
| Price_USD | Vehicle price |
| Sales_Volume | Total units sold |
| Sales_Classification | Sales performance category |

---

# 🧠 SQL Concepts Used

✅ SELECT  
✅ WHERE  
✅ ORDER BY  
✅ GROUP BY  
✅ HAVING  
✅ LIMIT  
✅ COUNT  
✅ SUM  
✅ AVG  
✅ MIN / MAX  
✅ LIKE  
✅ BETWEEN  
✅ IN  

---

# 📊 Business Questions Solved

## 🔹 Basic Analysis
1. BMW cars sold in Asia
2. Top 5 most expensive BMW models
3. Cars with mileage above 150,000 KM
4. Petrol cars with manual transmission
5. Cars sold in each region

## 🔹 Intermediate Analysis
6. Average BMW price in Europe
7. Models with engine size between 2.0L and 4.0L
8. Total sales volume by fuel type
9. Regions with average sales above 5000
10. Cheapest car in each region

## 🔹 Advanced Analysis
11. Most fuel-efficient BMW
12. Total BMW sales in 2015
13. Most profitable region
14. Most popular fuel type
15. Automatic vs Manual preference
16. Top-selling BMW model in North America

---

# 📈 Key Insights

🚘 Hybrid vehicles are the most popular fuel type among buyers.  

🌎 North America is the most profitable region based on sales volume.  

⚙️ Manual transmission vehicles appear more frequently in the dataset.  

📊 Europe and North America show consistently strong market demand.  

🏆 BMW 7 Series is the top-selling model in North America.  

---

# 📁 Project Structure

```bash
BMW-Sales-Analysis-SQL/
│
├── README.md
├── BMW_Sales_Analysis_SQL.pdf
├── sql_queries.sql
├── dataset.csv
└── screenshots/
```

---

# 📄 Project Presentation

## 👉 Open Full PDF Presentation

[Click Here to View Project PDF](./BMW_Sales_Analysis_SQL.pdf)

---

# 💻 Sample SQL Query

```sql
SELECT fuel_type, SUM(sales_volume) AS total_sales
FROM bmw
GROUP BY fuel_type;
```

---

# 🚀 Project Outcome

This project demonstrates:

✔️ SQL querying skills  
✔️ Business problem-solving  
✔️ Data analysis techniques  
✔️ Aggregation & filtering operations  
✔️ Real-world sales analysis  

---

# 👨‍💻 Author

## Shubham Sarkar

📌 Aspiring Data Analyst | SQL Enthusiast | Business Analytics Learner

---

# ⭐ If You Like This Project

Give this repository a ⭐ on GitHub!
