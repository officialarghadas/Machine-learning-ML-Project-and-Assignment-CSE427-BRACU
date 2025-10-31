# Retail Store Inventory Forecasting - EDA & Prediction

This project focuses on **retail store inventory forecasting** using exploratory data analysis (EDA) and machine learning prediction techniques. The notebook provides a comprehensive walkthrough of the process, from understanding the dataset to applying multiple regression models for demand forecasting.

## Project Overview

Retail stores need to efficiently manage their inventories to minimize costs and maximize sales. This project demonstrates how to analyze retail inventory data and build predictive models to forecast product demand, helping stores optimize their stock levels.

### Key Steps Covered:

- **Data Import & Cleaning:**  
  The dataset is loaded, checked for missing values and duplicates, and unnecessary columns are dropped for clarity.

- **Feature Engineering:**  
  Columns are renamed for simplicity and new features are explored to enhance model performance.

- **Exploratory Data Analysis (EDA):**  
  Visualizations (box plots, histograms) provide insights into inventory, sales, pricing, discounts, and other key features.

- **Regression Modeling:**  
  Several machine learning models are implemented for demand forecasting:
  - Linear Regression
  - Support Vector Regression (SVR)
  - Decision Tree Regressor
  - K-Nearest Neighbors (KNN) Regressor

- **Model Evaluation:**  
  Each model is assessed using metrics such as RMSE, MAE, and R² score to identify the best approach for accurate predictions.

- **Insights & Recommendations:**  
  Conclusions from the analysis guide inventory management strategies and highlight factors affecting demand (weather, promotions, competitor pricing, etc.).

## Dataset Features

- **Date**: Daily records.
- **Store ID & Product ID**: Unique identifiers for stores and products.
- **Category**: Product category (Electronics, Clothing, Groceries, etc.).
- **Region**: Store location.
- **Inventory Level**: Opening stock.
- **Units Sold / Ordered**: Daily sales and orders.
- **Demand Forecast**: Predicted demand (target variable).
- **Price / Discount / Competitor Price**: Pricing data.
- **Weather Condition / Seasonality**: Environmental effects.
- **Holiday/Promotion**: Special sales events.

## How to Use

- Review the EDA section for an understanding of the dataset and its features.
- Follow along with the modeling steps to learn how different regressors perform on retail demand data.
- Use the insights and recommendations to inform your own inventory management and forecasting solutions.

---

**Ideal For:**  
Students, data analysts, and retail professionals interested in practical machine learning applications for inventory forecasting.

**Technologies Used:**  
Python, Pandas, Numpy, Seaborn, Plotly, Scikit-learn

---

> **Explore the notebook to see step-by-step code, visualizations, and results!**
