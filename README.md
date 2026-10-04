# 🎵 Music Store SQL Analysis

## 📌 Project Overview

This project analyzes a digital music store database using **PostgreSQL** and **SQL**.

The analysis focuses on customers, invoices, artists, albums, tracks, genres, and employees to answer different business-related questions and extract meaningful insights from the data.

The project contains SQL queries ranging from **basic to advanced SQL concepts**, making it useful for practicing real-world data analysis using SQL.

---

## 🛠️ Tools & Technologies

- PostgreSQL
- pgAdmin
- SQL

---

## 🗄️ Database Tables

The project uses the following main tables:

- `employee`
- `customer`
- `invoice`
- `invoice_line`
- `track`
- `album`
- `artist`
- `genre`
- `media_type`
- `playlist`
- `playlist_track`

---

## 📊 SQL Analysis

The queries are divided into three difficulty levels.

### 🟢 Easy Level

#### Q1. Senior Most Employee
Find the senior-most employee based on job level.

**Concepts Used:**
- SELECT
- ORDER BY
- LIMIT

#### Q2. Countries with the Most Invoices
Identify countries having the highest number of invoices.

**Concepts Used:**
- COUNT()
- GROUP BY
- ORDER BY

#### Q3. Top 3 Invoice Values
Find the three highest invoice amounts.

**Concepts Used:**
- ORDER BY
- LIMIT

#### Q4. City with the Best Customers
Find the city generating the highest total invoice revenue.

**Concepts Used:**
- SUM()
- GROUP BY
- ORDER BY

---

### 🟡 Moderate Level

#### Q5. Best Customer
Identify the customer who has spent the most money.

**Concepts Used:**
- JOIN
- SUM()
- GROUP BY
- ORDER BY
- LIMIT

#### Q6. Rock Music Listeners
Find customers who listen to Rock music and return their email, first name, and last name.

**Concepts Used:**
- JOIN
- DISTINCT
- Subqueries
- IN
- WHERE
- ORDER BY

#### Q7. Top 10 Rock Artists
Find the top 10 artists who have created the most Rock tracks.

**Concepts Used:**
- Multiple JOINs
- COUNT()
- GROUP BY
- ORDER BY
- LIMIT

#### Q8. Tracks Longer Than Average
Find tracks whose length is greater than the average track length.

**Concepts Used:**
- AVG()
- Subquery
- WHERE
- ORDER BY

---

### 🔴 Advanced Level

#### Q9. Customer Spending on the Best-Selling Artist
Identify the best-selling artist and determine how much each customer spent on that artist.

**Concepts Used:**
- CTE
- Multiple JOINs
- SUM()
- GROUP BY
- Calculations

#### Q10. Most Popular Genre by Country
Find the most popular music genre in each country based on the number of purchases.

**Concepts Used:**
- CTE
- Window Functions
- ROW_NUMBER()
- PARTITION BY
- COUNT()
- Multiple JOINs

#### Q11. Highest-Spending Customer by Country
Find the customer who spent the most money in each country.

**Concepts Used:**
- CTE
- Window Functions
- ROW_NUMBER()
- PARTITION BY
- SUM()
- Multiple JOINs

---

## 📚 SQL Concepts Practiced

Through this project, I practiced:

- SELECT
- WHERE
- ORDER BY
- LIMIT
- DISTINCT
- COUNT()
- SUM()
- AVG()
- GROUP BY
- INNER JOIN
- Subqueries
- Common Table Expressions (CTEs)
- Window Functions
- PARTITION BY
- ROW_NUMBER()
- Aggregate Functions

---

## 🎯 Project Objectives

The main objectives of this project are to:

- Analyze customer purchasing behavior
- Identify top-performing artists and genres
- Analyze sales across different countries and cities
- Identify high-value customers
- Practice SQL joins and aggregations
- Apply advanced SQL concepts to real-world business questions

---

## 📁 Project Files

```text
Music-Store-SQL-Analysis/
│
├── analysis_queries.sql
├── Music_Store_database.sql
└── README.md

analysis_queries.sql

Contains SQL queries used to solve the business questions.

Music_Store_database.sql

Contains the database SQL script used to recreate the Music Store database.

README.md

Contains project information, analysis details, and SQL concepts used.

💡 Key Learning

This project helped me strengthen my SQL skills by working with a relational database and solving business-oriented questions using both basic and advanced SQL techniques.