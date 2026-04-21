# 🍽️ Zomato Data Analysis

### SQL + Python + Tableau | End-to-End Data Analytics Project

---

## 📌 Overview

This project performs an in-depth analysis of Zomato restaurant data to uncover **customer behavior, sales trends, and business insights**.

It follows a complete analytics workflow:
**Data → SQL → Analysis → Visualization → Insights**

---

## 🎯 Business Problem

Food delivery platforms need to:

* Identify top-performing restaurants
* Understand customer ordering behavior
* Optimize pricing and menu strategies
* Improve overall business performance

👉 This project provides **data-driven solutions** to these problems.

---

## 🛠️ Tech Stack

* **SQL (PostgreSQL)** – Data extraction & querying
* **Python (Pandas, Matplotlib, Seaborn)** – Data cleaning & EDA
* **Tableau** – Dashboard & visualization
* **Excel** – Data preprocessing

---

## 📊 Key Insights

* Top 20% customers contribute majority of revenue
* High-income users order more frequently
* Peak orders occur during lunch & dinner time
* Weekends have higher order volume
* Popular cuisines dominate overall sales

---

## 🔍 Sample SQL Query

```sql
SELECT r.name, COUNT(DISTINCT m.f_id) AS item_count
FROM restaurant r
JOIN menu m ON r.id = m.r_id
GROUP BY r.name
ORDER BY item_count DESC
LIMIT 10;
```

---

## 💼 Business Impact

* Enables targeted marketing strategies
* Helps identify high-value customers
* Improves decision-making using data insights
* Supports business growth and optimization

---

## 📁 Project Structure

```
Zomato-Data-Analysis/
│
├── Dataset/
├── SQL/
├── Images/
├── Solutions/
├── README.md
```

---

## 👤 Author

**Siddhant Panigrahi**

Data Analyst | Aspiring Data Scientist
