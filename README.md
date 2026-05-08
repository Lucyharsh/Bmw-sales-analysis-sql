# BMW Sales Analysis using SQL

## Project Overview
This project focuses on analyzing BMW sales data using SQL to extract meaningful business insights related to vehicle sales, customer preferences, pricing, fuel types, transmission trends, and regional performance.

The analysis transforms raw automotive sales data into actionable insights that can support business decision-making.

---

## Objectives
- Analyze BMW sales performance across regions
- Identify top-selling BMW models
- Compare fuel type popularity
- Understand customer transmission preferences
- Evaluate pricing and mileage trends
- Perform advanced SQL analysis using aggregation and filtering

---

## Tools & Technologies Used
- MySQL
- SQL
- GitHub

---

## Dataset Features

| Column Name | Description |
|-------------|-------------|
| Model | BMW car model |
| Year | Manufacturing/Sales year |
| Region | Sales region |
| Color | Vehicle color |
| Fuel_Type | Fuel category |
| Transmission | Manual/Automatic |
| Engine_Size_L | Engine size in liters |
| Mileage_KM | Vehicle mileage |
| Price_USD | Car price |
| Sales_Volume | Total units sold |
| Sales_Classification | High/Low sales category |

---

## SQL Concepts Used
- SELECT
- WHERE
- ORDER BY
- GROUP BY
- HAVING
- LIMIT
- COUNT
- SUM
- AVG
- MIN / MAX
- LIKE
- BETWEEN
- IN

---

## Business Questions Solved

### Basic Analysis
1. BMW cars sold in Asia
2. Top 5 most expensive BMW models
3. Cars with mileage above 150,000 KM
4. Petrol cars with manual transmission
5. Cars sold in each region

### Intermediate Analysis
6. Average BMW price in Europe
7. Models with engine size between 2.0L and 4.0L
8. Total sales volume by fuel type
9. Regions with average sales above 5000
10. Cheapest car in each region

### Advanced Analysis
11. Most fuel-efficient BMW
12. Total BMW sales in 2015
13. Most profitable region
14. Most popular fuel type
15. Automatic vs Manual preference
16. Top-selling BMW model in North America

---

## Key Insights
- Hybrid vehicles are the most popular fuel type among buyers.
- Manual transmission vehicles appear more frequently in the dataset.
- North America is the most profitable region based on sales.
- Europe and North America show consistently strong demand.
- BMW 7 Series is the top-selling model in North America.

---

## Project Structure

```text
BMW-Sales-Analysis/
│
├── README.md
├── BMW_Sales_Analysis.pdf
├── sql_queries.sql
├── dataset.csv
└── screenshots/
```

---

## Sample SQL Query

```sql
SELECT fuel_type, SUM(sales_volume) AS total_sales
FROM bmw
GROUP BY fuel_type;
```

---

## Project Outcome
This project demonstrates:
- SQL querying skills
- Data analysis techniques
- Business problem-solving
- Aggregation and filtering operations
- Real-world sales analysis

---

## Author
Shubham Sarkar
