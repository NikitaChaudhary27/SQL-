# 🚗 Urban Mobility Data Analytics using SQL

## 📌 Project Overview

This project analyzes an urban mobility dataset using SQL to uncover insights related to rides, users, drivers, vehicles, cities, payments, and revenue.

The project focuses on transforming raw mobility data into meaningful business insights using SQL queries and relational database concepts.

---

## 🎯 Objectives

- Analyze ride and user activity across different cities
- Identify high-performing drivers and users
- Analyze revenue and fare patterns
- Study ride cancellations and surge pricing
- Identify popular payment methods
- Compare vehicle and city performance
- Practice SQL concepts used in real-world data analytics

---

## 🗂️ Database Structure

The project uses multiple interconnected tables:

- `users` – Customer information and ride activity
- `rides` – Ride details, fares, distance, status, and surge
- `drivers` – Driver information, ratings, and cancellation rates
- `cities` – City information
- `vehicles` – Vehicle make, year, and details
- `payments` – Payment information

These tables are connected using Primary Keys and Foreign Keys.

---

## 🛠️ Tools & Technologies

- MySQL
- MySQL Workbench
- SQL
- GitHub

---

## 🔍 SQL Concepts Used

The project covers a range of SQL concepts:

- SELECT
- WHERE
- JOIN
- LEFT JOIN
- GROUP BY
- HAVING
- ORDER BY
- LIMIT
- COUNT()
- SUM()
- AVG()
- CASE WHEN
- Subqueries

---

## 📊 Key Analysis Areas

### 1. City & User Analysis
Analyzed the number of rides and users across different cities.

### 2. Ride Performance
Calculated average fares, ride distances, cancellations, and completed rides.

### 3. Customer Analysis
Identified high-spending users and users who have never booked a ride.

### 4. Driver Analysis
Identified highly-rated drivers and drivers with above-average cancellation rates.

### 5. Revenue Analysis
Compared revenue across cities, vehicle brands, drivers, and rides.

### 6. Payment Analysis
Identified the most popular payment mode.

### 7. Distance Categorization
Used `CASE WHEN` to categorize rides into:
- Short
- Medium
- Long

---

## 💡 Key Insights

The analysis helps answer important business questions such as:

- Which city has the highest ride activity?
- Which users contribute the most revenue?
- Which drivers have high ratings?
- What percentage of rides are cancelled?
- Which vehicle generates the highest revenue?
- Which city has the highest average surge?
- Which payment mode is most popular?

---

## 📁 Project Structure

```text
Urban-Mobility-SQL-Project/
│
├── README.md
├── SQL_Queries.sql
├── Dataset/
│   ├── users.csv
│   ├── rides.csv
│   ├── drivers.csv
│   ├── vehicles.csv
│   ├── cities.csv
│   └── payments.csv
│
└── Project_Presentation.pdf
