# Walmart Sales Forecast Project

## Overview
This project analyzes Walmart store sales data and builds a forecasting model to predict weekly sales for different stores and departments.  
The goal is to understand sales trends, seasonal patterns, and holiday impacts, and provide accurate sales predictions using Machine Learning techniques.

## Features
- **Data Analysis & Visualization:** Explore sales trends by store, department, holiday, and season.
- **Feature Engineering:** Time-based features (week, month, year) and store characteristics (type, size).
- **Forecasting Models:** Regression-based models for sales prediction.
- **Performance Metrics:** RMSE, MAE, R² to evaluate model accuracy.

## Project Workflow
- ✅ **Data Preprocessing**
  - Cleaned and merged datasets (features, sales, stores)
  - Converted `Date` column into datetime format
  - Added `IsHoliday` feature properly across datasets
- ✅ **Exploratory Data Analysis (EDA)**
  - Analyzed sales trends by date, store, department, holidays, and size
  - Identified seasonal patterns and spikes around major holidays
- ✅ **Feature Engineering**
  - Created meaningful time-based features (week, month, year)
  - Incorporated store-related factors (type, size)
- ✅ **Modeling & Evaluation**
  - Trained regression models for sales forecasting
  - Achieved strong results:
    - RMSE ~ 2850
    - MAE ~ 1365
    - R² ~ 0.9833

## Dataset
- `train.csv` – historical weekly sales data
- `test.csv` – weekly sales data to predict
- `features.csv` – additional store features
- `stores.csv` – store information (type, size)

## Requirements
- Python 3.x
- Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

**Install dependencies:**
```bash
pip install -r requirements.txt

```

**Clone the REpository**
```bash
git clone https://github.com/Utkarsha88/Walmart_sales_forecast_project.git
```
**open Jupyter notebook**
```bash
jupyter notebook Walmart_sales_Forcast.ipynb
```









