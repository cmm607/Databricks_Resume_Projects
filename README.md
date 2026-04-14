# Retail Sales Analytics, Customer Segmentation, and Churn Modeling in Databricks

## Overview
This project is an end-to-end retail analytics workflow built in Databricks using sales, product, customer, and store data. The goal was to simulate a real-world analytics project by building a medallion-style data pipeline, performing exploratory data analysis, engineering features, and developing machine learning models for customer segmentation, churn prediction, and sales forecasting.

## Business Problem
Retail organizations need to understand customer behavior, product performance, and store-level trends in order to improve retention, increase revenue, and support better decision-making. This project uses transactional retail data to generate business insights and predictive models that can support those goals.

## Objectives
- Build a Bronze, Silver, and Gold data pipeline in Databricks
- Clean and integrate sales, product, customer, and store datasets
- Perform exploratory data analysis to identify revenue and customer behavior trends
- Engineer customer-level and transaction-level features
- Segment customers using RFM-based clustering
- Predict sales outcomes using regression models
- Evaluate models using robust metrics including ROC AUC, RMSE, and Brier Score

## Tech Stack
- Databricks
- PySpark
- SQL
- Python
- scikit-learn
- pandas
- matplotlib

## Dataset
The project uses four retail datasets:
- **Sales**: transaction-level sales data
- **Products**: product information and attributes
- **Customers**: customer details and identifiers
- **Stores**: store information and attributes

These datasets were joined into a unified analytical table for downstream analysis and modeling.
