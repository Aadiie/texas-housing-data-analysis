# Texas Housing Data Analysis and Machine Learning

## Overview
This project performs Exploratory Data Analysis (EDA), statistical analysis, dimensionality reduction, clustering, and machine learning on the Texas Housing dataset.

The project analyzes housing market trends across multiple Texas cities and builds predictive models for housing prices using regression techniques.

---

## Objectives
- Analyze housing market patterns in Texas
- Perform data cleaning and preprocessing
- Visualize trends and correlations
- Apply clustering and dimensionality reduction techniques
- Build a machine learning regression model for housing price prediction

---

## Dataset
Dataset Source:
- Texas Housing Dataset (`txhousing.csv`)

Features used include:
- Sales
- Volume
- Median Price
- Listings
- Inventory
- City
- Year
- Month

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

---

## Project Workflow

### 1. Data Preprocessing
- Handling missing values
- Removing duplicates
- Feature preparation
- Standardization

### 2. Exploratory Data Analysis
- Summary statistics
- Distribution analysis
- Correlation heatmaps
- Trend visualization
- City-wise comparisons

### 3. Clustering
- Minimum Spanning Tree (MST) clustering
- Cluster visualization

### 4. Dimensionality Reduction
- PCA
- SVD
- Factor Analysis

### 5. Machine Learning
Linear Regression model for predicting median housing prices.

---

## Model Performance

| Metric | Value |
|---|---|
| R² Score | 0.6902 |
| MAE | $15,973 |
| RMSE | $20,295 |

---

## Key Insights
- Housing prices vary significantly across Texas cities
- Sales and volume show strong correlation
- PCA captured over 80% variance in two components
- Regression model achieved reasonable predictive performance

---

## Future Improvements
- Add advanced ML models (Random Forest, XGBoost)
- Build interactive dashboards
- Deploy as a web application
- Add time-series forecasting

---

## Author
Aditya Dhamala
