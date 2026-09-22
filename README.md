# 🍕 Pizza Sales Analysis using SQL

## 📌 Project Overview

This project focuses on analyzing pizza sales data using Microsoft SQL Server to extract actionable business insights from transactional records. By leveraging relational tables—including Orders, Order_Details, Pizzas, and Pizza_Types—the analysis evaluates sales performance and customer purchasing behavior. Advanced SQL techniques such as multi-table JOINs, aggregations, Common Table Expressions (CTEs), and Window Functions are applied to generate meaningful, data-driven business insights.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Sales & Revenue Analysis: Evaluate total revenue, average order value, and daily sales trends.
- Product Performance Analysis: Identify top-selling and least-ordered pizza types, categories, and sizes.
- Operational & Temporal Insights: Analyze hourly ordering patterns and peak sales days to support operational planning.
- SQL & Reporting Skills: Demonstrate practical SQL skills through complex queries, data analysis, and business reporting.


---

## 🗂️ Dataset Overview

The dataset consists of four relational tables:

### 1. Orders
- Order_ID
- Date
- Time

### 2. Order_Details
- Order_Details_ID
- Order_ID
- Pizza_ID
- Quantity

### 3. Pizzas
- Pizza_ID
- Pizza_Type_ID
- Size
- Price

### 4. Pizza_Types
- Pizza_Type_ID
- Name
- Category
- Ingredients

---

## 🧠 Business Questions

The analysis answers 15 business questions:

1. Retrieve all orders placed on `2015-01-01`
2. List all distinct pizza categories
3. Find the total number of pizzas ordered
4. Find the top 5 most frequently ordered pizza types
5. Find total pizzas ordered in each order
6. Find the number of orders placed in each hour
7. Find the day with the maximum number of orders
8. Find the earliest and latest order time for each day
9. Find total revenue generated from each pizza type
10. Identify the pizza category generating maximum revenue
11. Calculate the average number of pizzas per order
12. Find the top 3 highest-spending orders
13. Calculate cumulative revenue throughout the day
14. Identify the least-ordered pizza
15. Calculate each pizza category's percentage contribution to total revenue

---

## 🛠️ Technologies Used

- **Microsoft SQL Server**
- **SQL**

---

## 📊 Key Insights

- $817.86K revenue generated from 21.35K orders.
- 49.57K pizzas sold with 2.32 pizzas per order.
- Classic Deluxe Pizza is the top-selling pizza by quantity.
- Thai Chicken Pizza generates the highest revenue.
- Classic Category contributes the largest share of total revenue.
- Large pizzas are the most preferred size.
- Peak order volumes are recorded between 12:00 PM – 1:00 PM and 5:00 PM – 6:00 PM.
- Friday & Saturday show high order demand.
- Brie Carre Pizza is the lowest-performing product.

---

🚀 Conclusion

The project demonstrates how SQL can be used to transform transactional pizza sales data into meaningful business insights.

The analysis covers sales performance, product demand, revenue contribution, customer ordering behavior, and temporal ordering patterns using Microsoft SQL Server.

---

## 👤 Author
Jatin Rajpal
