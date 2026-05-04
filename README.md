# 📊 E-commerce Analytics Project

## 🔍 Project Overview

This project explores an online retail dataset to analyze revenue trends, customer behavior, and retention patterns. The goal was to simulate a real-world business analysis workflow — from raw data cleaning to building an interactive dashboard.

---

## 🎯 Objectives

* Analyze revenue trends over time
* Identify top-performing products
* Identify high-value customers
* Segment customers using RFM analysis
* Evaluate customer retention using cohort analysis

---

## 📈 Key Insights

* Revenue shows clear seasonality, peaking in November (~1.15M), indicating strong Q4 performance
* The top 10 customers generate approximately **17% of total revenue**, highlighting high customer concentration
* A small number of products dominate sales, with the top product generating over **160K in revenue**
* Customer spending is highly skewed: the average revenue per customer (~2048) is significantly higher than the median (~668), indicating the presence of high-value clients
* Cohort analysis shows that over **70% of customers do not return after their first purchase**, suggesting weak customer retention

---

## 🛠 Tools & Technologies

* Python (Pandas)
* Jupyter Notebook
* Tableau Public

---

## 📊 Dashboard
![Dashboard](Dashboard_retail.pdf)
👉 [View Tableau Dashboard](https://public.tableau.com/views/E-commerseSalesdashboard/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## 📁 Data

Due to file size limitations, the cleaned dataset is not included in this repository.

You can access the dataset here:
👉 [Download Data](https://www.kaggle.com/datasets/azhartilekova/cleaned-onlineretail-data)

---

## ⚙️ Data Cleaning Steps

* Removed transactions with negative or zero quantity
* Removed transactions with zero unit price
* Dropped missing Customer IDs
* Created a new feature: `Revenue = Quantity × UnitPrice`
* Converted `InvoiceDate` to datetime format
* Removed duplicate records
* Filtered out non-product entries (e.g., POSTAGE, Manual)

---

## 📊 Analysis Performed

* Revenue over time
* Top 10 products by revenue
* Top 10 customers by revenue
* Customer segmentation (RFM)
* Cohort retention analysis

---

## 🚀 What I Learned

* How to clean and preprocess real-world transactional data
* How to extract meaningful business insights
* How to perform customer segmentation (RFM)
* How to build and present dashboards in Tableau
* How to structure an end-to-end analytics project

---

## 📌 Project Structure

```bash
data/
notebooks/
analysis.ipynb
README.md
```

---

## 👀 Next Steps

* Add more advanced customer segmentation
* Build predictive models (e.g., customer lifetime value)
* Improve dashboard interactivity
