# 📊 Online Retail Analysis Project

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)

A comprehensive analysis of online retail data to uncover customer purchasing patterns, sales trends, and product performance using RFM segmentation and clustering techniques.

## 📌 Project Overview

This project analyzes transactional data from a UK-based online retail store (December 2009 - December 2010) to:
- Identify high-value customer segments
- Understand purchasing behaviors
- Generate actionable business insights
- Prepare data for predictive modeling

## 🛠️ Technologies & Methods

**Core Technologies:**
- Python 3
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

**Analytical Methods:**
- RFM (Recency, Frequency, Monetary) Analysis
- K-means Clustering
- Data Cleaning & Feature Engineering
- Exploratory Data Analysis (EDA)


## 🔍 Key Analyses

1. **Data Preparation**
   - Handled missing values (17.5% of Customer IDs)
   - Removed invalid transactions (negative quantities/prices)
   - Standardized date formats and currencies

2. **Feature Engineering**
   - Calculated SalesLineTotal (Quantity × Price)
   - Created RFM metrics:
     - Recency: Days since last purchase
     - Frequency: Unique invoices count
     - Monetary: Total sales value

3. **Customer Segmentation**
   - Performed K-means clustering on RFM metrics
   - Identified 4 distinct customer segments

4. **Business Insights**
   - Top-selling products and categories
   - Geographic distribution of customers
   - Seasonal purchasing patterns

## 📊 Sample Visualizations


![RFM Segments](cluster%20distribution.png)  
*Customer segments based on purchasing behavior*
