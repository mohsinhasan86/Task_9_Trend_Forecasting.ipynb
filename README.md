# 📊 Task 9 – Retail Sales Trend Forecasting

## 📌 Project Overview

This project is part of the **PlaceMux Phase 1 – Data Analyst Industry Immersion Program**.

The objective of this task is to analyze historical retail sales trends and build a simple forecasting workflow that can support future business planning.

The analysis uses the cleaned retail sales dataset generated during **Task 8 – Executive Insight**.

---

## 🎯 Objectives

* Analyze monthly retail sales trends
* Identify missing periods in the time series
* Create a validation dataset
* Establish a Naive forecasting baseline
* Apply Simple Exponential Smoothing (SES)
* Apply Holt's Exponential Smoothing
* Compare forecasting models using MAE
* Generate future sales forecasts
* Estimate and communicate forecast uncertainty
* Identify limitations and assumptions

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Statsmodels**
* **Scikit-learn**
* **Google Colab**
* **GitHub**

---

## 📂 Dataset

The analysis uses:

`Task_8_Cleaned_Retail_Sales.csv`

The dataset contains cleaned retail transaction information along with calculated sales metrics such as:

* Gross Sales
* Discount Amount
* Net Sales
* Order Date
* Category
* Sales Channel
* Order Status

---

## 📈 Methodology

### 1. Monthly Sales Aggregation

Transaction-level `net_sales` values were aggregated by month to create a monthly time series.

### 2. Trend Analysis

The monthly sales series was visualized to understand the histor
