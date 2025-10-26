# Providing-Insights-for-Crisis-Recovery-in-an-Online-Food-Delivery-Startup
 This project is an analysis for the Codebasics Revolutionize Challenge (RPC) 18, focusing on crisis recovery for a food delivery startup.


 # Codebasics RPC 18: QuickBite Express Crisis Recovery Analysis

## Project Overview

This repository contains the data analysis and code submission for the Codebasics Revolutionize Power BI Challenge (RPC) 18. The project focuses on providing actionable insights and a crisis recovery strategy for **QuickBite Express**, a Bengaluru-based food-tech startup that faced a major crisis in June 2025 due to food safety incidents and a week-long delivery outage.

The crisis resulted in a sharp decline in daily orders, customer satisfaction scores, and an increase in customer acquisition costs (CAC).

## Goal

The primary goal is to provide **detailed insights and strategic recommendations** to QuickBite's management team for their recovery efforts, specifically analyzing customer segments, order patterns, and delivery performance across three phases: **Pre-Crisis (Jan-May 2025)**, **Crisis (Jun-Sep 2025)**, and **Recovery (Post-Sep 2025, implied)**.

## Analysis Focus (Primary Questions)

The analysis addresses critical questions based on the available data, including:

* **Order Decline Severity:** Comparing total orders across pre-crisis vs. crisis period.
* **Geographical Impact:** Identifying the top 5 city groups with the highest percentage decline in orders.
* **Restaurant Churn:** Analyzing high-volume restaurants that experienced the largest percentage decline in order counts.
* **Operational Metrics:** Tracking cancellation rate trends, Delivery SLA compliance, and month-by-month customer rating fluctuation.
* **Revenue Impact:** Estimating revenue loss based on subtotal, discount, and delivery fee.
* **Customer Lifetime Decline:** Identifying high-value customers (top 5% by total spend before the crisis) with the largest drop in order frequency and ratings during the crisis.

## Repository Structure

| File/Folder | Description |
| :--- | :--- |
| `CodeBasicChallenge_2_python_colab.ipynb` | The main Jupyter Notebook containing the data cleaning, analysis, feature engineering, and a machine learning model for **High-Value Order Classification**. |
| `Primary and Secondary Analysis.pdf` | The official document outlining the primary analysis questions and suggestions for secondary analysis. |
| `RPC_18_Problem_Statement.pdf` | The official problem statement detailing the business context and management expectations. |
| `requirements.txt` | A list of all Python dependencies required to run the code. |
| `.gitignore` | Standard file to ignore temporary, cache, and large data files. |
| `/data` | **(Placeholder)** Directory for the dimension and fact tables (e.g., `dim_customer.csv`, `fact_orders.csv`). |

## Tech Stack

The analysis was performed using the following tools and libraries:

* **Language:** Python
* **Environment:** Google Colab
* **Core Libraries:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn (`RandomForestClassifier`, `train_test_split`, `classification_report`, `roc_auc_score`)



