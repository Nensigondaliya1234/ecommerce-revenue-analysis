# Olist E-Commerce Analysis 📊

## Overview
End-to-end exploratory data analysis of 100,000+ real orders from Brazil's largest 
e-commerce platform. Built using Python across 6 relational datasets to surface 
actionable business insights across revenue, logistics, and customer behavior.

## Analysis Areas
- **Revenue** — Top categories and states by gross revenue, with concentration analysis
- **Customer Behavior** — Repeat purchase patterns and one-time buyer breakdown
- **Delivery Performance** — On-time vs late delivery rates, average delivery days by state
- **Payment Trends** — Payment method usage and credit card installment distribution
- **Customer Satisfaction** — Review score drivers, including impact of late delivery
- **Cross-Analysis** — Category risk map connecting delivery performance, review scores, and revenue

## Key Findings
- 📦 Late deliveries drop review scores by **1.66 points** (4.21 → 2.55 / 5)
- 🗺️ São Paulo alone drives **38% of total revenue** — top 3 states account for 63%
- 🔁 **97% of customers never return** — retention is the single biggest growth gap
- 💳 Credit card is the dominant payment method, with installment plans widely preferred
- 📈 Revenue peaked in **November 2017** at 1.7x the monthly average — likely Black Friday demand

## Tools
Python · Pandas · Matplotlib · Seaborn · Jupyter Notebook

## Dataset
[Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) — Kaggle

## How to Run
1. Clone this repository
2. Download the dataset from Kaggle and place all CSV files in the project folder
3. Install dependencies:
```bash
pip install pandas matplotlib seaborn
```
4. Open and run `olist_ecommerce_analysis.ipynb` top to bottom (Kernel → Restart & Run All)

## Author
Nensi Gondaliya
