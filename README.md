# Electric_Vehicle
# EV Adoption Forecasting using Regression Models

This project aims to forecast the future adoption of Electric Vehicles (EVs) using historical data on registered electric and non-electric vehicles across Washington State. Accurate forecasts are crucial for urban planners to make informed decisions regarding EV infrastructure, such as public charging stations and road network readiness.

## Project Overview

As EV adoption continues to surge, proactive infrastructure planning becomes a necessity. This project utilizes a regression-based machine learning approach to predict future EV adoption trends. The dataset spans from **January 2017 to February 2024**, containing monthly vehicle registration data separated by **county** and **vehicle type**.


## Problem Statement

Inadequate planning for electric vehicle infrastructure can lead to operational bottlenecks, reducing user satisfaction and hindering environmental sustainability goals. Our aim is to develop a **regression model** that can:

- Forecast the number of EVs in future months/years.
- Analyze trends based on vehicle types and geographic regions.
- Help decision-makers prepare better for growing EV demands.

## 📂 Dataset

**Source**: [Kaggle - EV Population Size 2024 Dataset](https://www.kaggle.com/datasets/sahirmaharajj/electric-vehicle-population-size-2024/data)

### Key Features:

- **Date**: Monthly registration data (2017-01-31 to 2024-02-29)
- **County**: Geographic region where vehicle is registered.
- **Vehicle Primary Use**: Passenger or Truck.
- **BEVs (Battery Electric Vehicles)**: Fully electric vehicles.
- **PHEVs (Plug-In Hybrid Electric Vehicles)**: Vehicles powered by both gasoline and electricity.
- **EV Total**: Sum of BEVs and PHEVs.
- **Non-EV Total**: Count of all other types of vehicles.
- **Total Vehicles**: All vehicles, including EVs and non-EVs.
- **Percent EV**: Ratio of electric vehicles to total vehicles.

## Technologies Used

- **Python**
- **Jupyter Notebook**
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn** – Data visualization
- **Scikit-learn** – Regression modeling
- **Statsmodels** – Time series analysis (optional)
- **XGBoost / Random Forest / Linear Regression** – Predictive models

## Project Workflow

1. **Data Cleaning & Preprocessing**  
   - Handling missing values  
   - Aggregating data by time and county  
   - Feature engineering (e.g., month/year, rolling averages)

2. **Exploratory Data Analysis (EDA)**  
   - Trend analysis of EV adoption  
   - Regional distribution of EV usage  
   - Growth rates of BEVs and PHEVs

3. **Model Building**  
   - Regression models to forecast future EV totals  
   - Comparison between Linear Regression, Random Forest, and XGBoost

4. **Model Evaluation**  
   - R² Score  
   - RMSE / MAE  
   - Cross-validation

5. **Forecasting**  
   - Projecting EV adoption for upcoming years (e.g., 2025–2030)


## Sample Forecast Output

> Example (from model):  
> *By 2026, King County is expected to see over 150,000 registered electric vehicles, assuming current trends continue.*


## Use Cases
- **Urban Planning**: Estimate future demand for EV infrastructure like charging stations.
- **Policy Making**: Understand EV adoption patterns across counties.
- **Environmental Impact Studies**: Project carbon emission reduction through EV growth.
