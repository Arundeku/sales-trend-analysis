# 🧮 Online Sales Data Analysis

This repository contains a data analysis project focused on grouping and analyzing time trends from an online sales dataset.

---

## 📊 Objective

The goal of this project is to:
- Learn how to **group data** by multiple dimensions (e.g., time, region, product).
- Analyze **time-based trends** such as revenue growth, order volume, and customer behavior.
- Develop skills in **Pandas (Python)** for business data analysis.

---

## 📁 Dataset

The dataset (`Online Sales Data.csv`) contains:
- Sales transactions from an online store
- Fields like: Date, Revenue, Product Category, Units Sold, Region, Payment Method, etc.

---

## 🛠️ Key Tasks Performed

### ✅ Data Preparation
- Loaded CSV file using `pandas`
- Renamed columns for simplicity
- Converted `Date` to datetime format
- Extracted `year` and `month` for time-based grouping

### ✅ Grouping Analysis
- Grouped by:
  - Year & Month
  - Region
  - Product Category
  - Payment Method

### ✅ Time Trend Analysis
- Monthly Revenue & Order Volume
- Revenue Trends by Region
- Product Sales Trends over Time
- Payment Method Usage Trends

---

## 📈 Sample Metrics Extracted

| Year | Month | Total Revenue | Order Volume |
|------|-------|----------------|---------------|
| 2024 | Jan   | 14,548.32      | 31            |
| 2024 | Feb   | 10,803.37      | 29            |
| ...  | ...   | ...            | ...           |

---

## 🐍 Tools Used

- Python 3
- Pandas
- Jupyter Notebook (optional)
- Matplotlib / Seaborn (for visualization, optional)

---

## 🚀 Getting Started

Clone the repo and run the analysis:

```
