# Customer Cohort Retention Analysis (Superstore Dataset)
By Saddam Fachriza Yusuf & Baira Rahayu

## Project Overview

This project analyzes customer purchasing behavior using **cohort retention analysis** to understand how well the business retains customers over time.
By grouping customers based on their **first purchase period (cohort)**, we can observe retention patterns and identify opportunities to improve **customer loyalty and repeat purchases**.

The analysis uses the **Superstore dataset (2014–2017)** and focuses on identifying trends in customer retention across different quarterly cohorts.

---

## Objectives

* Analyze **customer retention behavior** over time.
* Identify **repeat purchase patterns** using cohort analysis.
* Visualize retention trends using **heatmaps and line plots**.
* Generate **business insights and strategic recommendations** to improve customer retention.

---

## Dataset

Dataset used: **Sample Superstore Dataset**

The dataset contains transactional data including:

* Customer ID
* Order Date
* Product Category
* Sales
* Profit
* Region
* Segment

For the cohort analysis, the primary variables used were:

* **Customer ID** → identify unique customers
* **Order Date** → determine transaction period and cohort group

---

## Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Seaborn**
* **Matplotlib**
* **Jupyter Notebook / VS Code**

---

## Methodology

The cohort analysis process includes the following steps:

1. **Data Preparation**

   * Convert order date into datetime format
   * Extract transaction quarter

2. **Cohort Identification**

   * Identify each customer's **first purchase quarter**

3. **Retention Calculation**

   * Measure the number of returning customers per cohort over time
   * Calculate retention rate based on the initial cohort size

4. **Data Visualization**

   * Cohort retention heatmap
   * Cohort retention line plot

---

## Key Insights

* Customer retention drops significantly after the **first purchase period**, indicating many customers make only a **single purchase**.
* Most cohorts stabilize at a **20–50% retention rate** in later quarters.
* Some cohorts show temporary increases in retention, possibly influenced by **seasonal demand or promotions**.
* Customers who remain active after several periods tend to become **long-term loyal customers**.

---

## Business Recommendations

Based on the analysis, several strategies can help improve customer retention:

* Implement **loyalty programs** to encourage repeat purchases.
* Use **personalized marketing campaigns** based on purchase history.
* Offer **repeat purchase incentives** such as discounts or reward points.
* Improve overall **customer experience** to increase long-term engagement.

---

## Project Output

The analysis includes several visualizations:

* **Cohort Retention Heatmap**
* **Cohort Retention Line Plot**
* Additional exploratory visualizations for understanding customer behavior.

---

## Project Structure

```
customer-cohort-retention-analysis
│
├── dataset
│   └── Sample-Superstore.csv
│
├── notebook
│   └── cohort_retention_analysis.ipynb
│
├── visualization
│   └── cohort_heatmap.png
│   └── cohort_lineplot.png
│
└── README.md
```

---
