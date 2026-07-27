Customer Segmentation and Sales Growth Prediction using Machine Learning
Overview

This project analyzes an Online Retail dataset containing more than 541,000 transaction records.

The project applies Machine Learning techniques to:

Segment customers based on purchasing behavior.
Predict customer type for new customers.
Analyze and estimate country-wise sales growth trends.

The project demonstrates both Unsupervised Learning and Supervised Learning using Python and Scikit-learn.

Objectives
Clean and preprocess retail transaction data.
Perform customer segmentation using K-Means Clustering.
Predict customer segments using Random Forest.
Estimate country-wise sales growth using Linear Regression.
Visualize customer behavior and business insights.
Dataset

Dataset: Online Retail Dataset

Dataset contains:

541,909 transaction records
Customer purchase history
Product information
Invoice details
Country information
Sales values

Since the dataset does not contain customer labels, it is considered an Unlabelled Dataset.

Technologies Used
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Scikit-learn
Machine Learning Algorithms
Unsupervised Learning
K-Means Clustering

Purpose:

Automatically groups customers based on purchasing behavior.

Supervised Learning
Random Forest Classifier

Purpose:

Predicts customer type for new customer data.

Regression
Linear Regression

Purpose:

Estimates country-wise monthly sales growth.

Features Created

The following customer features were generated:

Total Spending
Total Quantity Purchased
Total Transactions
Average Product Price

Workflow

Load Dataset
        ↓
Data Cleaning
        ↓
Feature Engineering
        ↓
Outlier Removal
        ↓
Feature Scaling
        ↓
K-Means Clustering
        ↓
Cluster Profiling
        ↓
Random Forest Prediction
        ↓
Country Sales Growth Analysis
        ↓
Visualization

Visualizations
Elbow Method
Customer Segments Scatter Plot
Customer Distribution Bar Chart
Country Sales Growth Chart
Monthly Revenue Trend
Results
Customer Segmentation

Customers were divided into:

Low Value Customers
Regular Customers
High Value Customers
Premium Customers
Customer Prediction

The trained model predicts the customer segment using:

Total Spending
Total Quantity
Total Transactions
Average Price
Country Growth Prediction

Linear Regression is used to estimate the monthly sales growth rate for different countries and identify the fastest-growing markets.

Applications
Customer Segmentation
Personalized Marketing
Customer Retention
Sales Analysis
Business Intelligence
Retail Analytics
Market Expansion
Sales Forecasting
Future Improvements
Streamlit Web Application
Real-time Prediction
SQL Database Integration
Power BI Dashboard
Model Deployment
REST API
Author

Sanvi Arora

B.Tech CSE (AI & ML)
