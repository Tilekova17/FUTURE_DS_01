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

* Revenue shows strong growth toward the end of the year (seasonality effect)
* A small group of customers generates a large share of total revenue
* Top products contribute disproportionately to overall sales
* Customer retention drops significantly after the first purchase

---

## 🛠 Tools & Technologies

* Python (Pandas)
* Jupyter Notebook
* Tableau Public

---

## 📊 Dashboard

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
