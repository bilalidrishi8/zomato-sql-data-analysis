# 🍽️ Zomato SQL Data Analysis Project

## 📌 Project Overview

This project analyzes Zomato restaurant data using SQL to uncover meaningful business insights. The analysis focuses on restaurant performance, customer preferences, pricing, ratings, cuisines, online delivery, table booking, and city-wise trends.

The project demonstrates SQL skills ranging from beginner to advanced, including joins, aggregate functions, window functions, Common Table Expressions (CTEs), subqueries, and business problem solving.

---

# 🎯 Objectives

- Analyze restaurant performance
- Identify top-rated restaurants
- Compare restaurant prices across cities
- Analyze customer ratings
- Study cuisine popularity
- Evaluate online delivery and table booking services
- Generate business insights for restaurant owners
- Practice real-world SQL business problems

---

# 🛠️ Tech Stack

- PostgreSQL
- SQL
- pgAdmin 4
- CSV Dataset
- Git & GitHub

---

# 📂 Dataset

The project uses Zomato restaurant data containing information such as:

- Restaurant Name
- Restaurant ID
- Country
- City
- Locality
- Cuisines
- Average Cost for Two
- Currency
- Has Table Booking
- Has Online Delivery
- Aggregate Rating
- Rating Color
- Rating Text
- Votes

---

# 🗄️ Database Schema

Main Table:

```sql
zomato_restaurants
```

---

# 📊 SQL Concepts Used

### Beginner

- SELECT
- WHERE
- ORDER BY
- LIMIT
- DISTINCT
- COUNT
- SUM
- AVG
- MIN
- MAX

### Intermediate

- GROUP BY
- HAVING
- CASE WHEN
- INNER JOIN
- LEFT JOIN
- RIGHT JOIN
- SELF JOIN
- Subqueries

### Advanced

- CTE (WITH)
- Window Functions
- RANK()
- DENSE_RANK()
- ROW_NUMBER()
- NTILE()
- LEAD()
- LAG()
- Running Totals
- Percentage Contribution

---

## 📈 Business Questions

##  --1. Find the top 10 restaurants based on rating.
##  --2. Find the top 10 restaurants based on votes.
##  --3. Find the most popular cuisine.
##  --4. Find the average rating for each price range.
##--5. Find cities with more than 100 restaurants.
##--6. Find the percentage of restaurants offering online delivery.
##--7. Find the most expensive restaurants.
##  --8. Find the city with the highest average restaurant rating.
##  --9. Find the city with the highest average cost for two.
##  --10. Find restaurants whose rating is above the city average.
##  --11. Find restaurants with above-average votes and ratings.
##  --12. Find the percentage contribution of each price range to total restaurants.
##  --13. Find the top 10% restaurants based on votes.
##  --14. Find the most popular cuisine in every city.
##  --15. Find the highest-rated restaurant in each country.
##  --16. Categorize restaurants into Low, Medium, and High rated using CASE.

# 📁 Repository Structure

```
zomato-sql-data-analysis/
│
├── Dataset/
│   └── Zomato_Project.csv
│
├── Database/
│   └── Create_Table.sql
│
├── SQL Queries/
│   ├── Beginner.sql
│   ├── Intermediate.sql
│   └── Advanced.sql
│
├── ER Diagram/
│   └── ER_Diagram.png
│
├── Screenshots/
│   ├── Query_Results.png
│   └── Dashboard.png
│
└── README.md
```

---

# 📈 Key Insights

- Identified top-performing restaurants by ratings and votes.
- Analyzed city-wise restaurant distribution.
- Compared average pricing across cities.
- Determined the most popular cuisines.
- Evaluated the impact of online delivery and table booking.
- Ranked restaurants using SQL window functions.
- Generated actionable business recommendations.

---

# 🚀 Skills Demonstrated

- SQL Query Writing
- Data Cleaning
- Aggregate Functions
- Window Functions
- CTEs
- Joins
- Subqueries
- Business Analytics
- Query Optimization
- Data Analysis

---

# 📌 Learning Outcomes

This project demonstrates how SQL can be used to solve real-world business problems by transforming raw restaurant data into meaningful insights for decision-making.

---

## ⭐ If you found this project helpful, consider giving it a Star!
