
# FoodPanda Data Analysis

## 📊 Overview

Analyze FoodPanda order and delivery data to find customer trends, top items, revenue insights, and delivery performance.

## 🧠 Objectives

* Clean and prepare raw data.
* Perform Exploratory Data Analysis (EDA).
* Visualize key business KPIs.
* Summarize actionable insights.

## 🗂️ Project Structure

```
├─ foodpandaAnalysis.ipynb   # Main notebook
├─ data/                     # Raw & processed data
├─ assets/                   # Charts & exports
└─ README.md                 # Project documentation
```

## ⚙️ Requirements

```
pandas
jupyterlab
```

Install:

```bash
pip install -r requirements.txt
```

## 🚀 Run the Notebook

```bash
jupyter notebook foodpandaAnalysis.ipynb
```

## 🔍 Steps in Notebook

1. Load and clean data (missing values, date format `YYYY-MM-DD`).
2. Create features like `order_hour`, `delivery_time_minutes`.
3. EDA – peak times, top restaurants, average delivery time.
4. Visualize trends using bar & line charts.
5. Summarize insights and recommendations.

## 📈 Sample Insights

* Peak orders: 12–2 PM & 7–9 PM.
* Avg delivery time: ~30 mins.
* Top 10% restaurants = 70% revenue.

## 📬 Next Steps

* Predict delivery delays.
* Forecast daily orders.
* Customer segmentation for retention.

