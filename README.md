# 🛍️ Customer Segmentation Analysis

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.3-orange.svg)](https://scikit-learn.org/stable/)
[![Made with Pandas](https://img.shields.io/badge/Made%20with-Pandas-150458.svg)](https://pandas.pydata.org/)

---

Welcome to the Customer Segmentation Analysis project. This notebook uses real-world mall customer data and unsupervised machine learning techniques to help businesses better understand their customer base and optimize marketing strategies.

## Project Overview

Imagine you own a shopping mall and want to identify:
- High-spending customers
- Frequent visitors
- Customer groups for targeted marketing

This project explores customer demographics and spending patterns to group similar customers together using clustering algorithms.

## Dataset

- **File:** `Mall_Customers.csv`
- **Features:**
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

## What's Included?

- **Exploratory Data Analysis (EDA):**
  - Distribution plots of Age, Income, and Spending Score
  - Gender-based comparisons
  - Correlation matrix heatmap

- **Clustering:**
  - Feature selection
  - Elbow Method to determine optimal number of clusters
  - KMeans clustering to segment customers
  - 2D visualizations of clustered segments

- **Business Insights:**
  - Actionable suggestions based on identified customer segments

## How to Use

1. Open the Jupyter Notebook: `customer_segmentation.ipynb`
2. Run the notebook step-by-step:
   - Load and explore the dataset
   - Perform EDA and visualize relationships
   - Apply KMeans clustering and interpret the results
3. Review the charts and cluster insights to understand customer behavior

## Requirements

Ensure you have the following Python libraries installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
