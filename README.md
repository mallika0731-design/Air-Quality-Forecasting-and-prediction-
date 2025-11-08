# 🌫️ Air Quality India: PM2.5 Analysis & Forecasting  

This project analyzes and forecasts **PM2.5 air pollution trends in India** using public air quality data from **2017 to 2022**.  
It combines **exploratory data analysis**, **machine learning**, and **time series forecasting** to provide actionable insights into pollution patterns and future trends.

---

## 🗂️ Table of Contents  
1. [Project Overview](#project-overview)  
2. [Dataset](#dataset)  
3. [Features](#features)  
4. [Usage](#usage)  
5. [Project Structure](#project-structure)  
6. [Results](#results)  
7. [Technologies Used](#technologies-used)  

---

## 📖 Project Overview  

Air pollution in India is a **major environmental concern**, particularly due to rising **PM2.5 levels**.  
This project performs both **descriptive** and **predictive** analytics on PM2.5 data using:
- Data visualization  
- Supervised machine learning (Random Forest, XGBoost)  
- Time series forecasting (ARIMA)  

The goal is to **analyze long-term pollution trends** and **predict future PM2.5 increases** across India.

---

## 📊 Dataset  

**Source:** [Kaggle – Air Quality Data in India (2017–2022)](https://www.kaggle.com/datasets/fedesoriano/air-quality-data-in-india)  

**Included file:** `Air quality India.csv` (must be in the repo folder)  

**Fields Used:**  
- Timestamp  
- Year, Month, Day, Hour  
- PM2.5  

**Date Range:** 2017 – 2022  

---

## ⚙️ Features  

- **Exploratory Data Analysis (EDA)** and data cleaning  
- **Visualizations:**
  - Hourly, daily, and annual PM2.5 trends  
  - Actual vs. Predicted PM2.5 (ML models)  
  - PM2.5 forecasting with ARIMA  
- **Supervised ML Models:**
  - Random Forest, XGBoost for hourly PM2.5 prediction  
  - Hyperparameter tuning via cross-validation  
- **Forecasting:**
  - Time Series Forecast (ARIMA) for next 30 days  
  - Summary statement of predicted % increase in daily PM2.5  

---
▶️ Usage

Place the dataset file Air quality India.csv in the project folder.

Run the main analysis script:

python "Air Quality Project.py"


View plots as they appear and follow console outputs for model evaluation and forecast summaries.

Close each plot window to proceed to the next.

The script ends with a statement showing the predicted percentage increase in PM2.5 for the next 30 days.


📁 Project Structure

Air Quality Project.py       # Main Python analysis script  
Air quality India.csv        # Dataset (2017-2022)  
README.md                    # Project documentation (this file)  
requirements.txt (optional)  # Dependency list for quick setup  


📊 Results


Five key analysis plots:


PM2.5 over time


Daily trend


Yearly trend


Actual vs Predicted (ML models)


Future Forecast (ARIMA)




Evaluation metrics printed in console:


MAE, RMSE, R² for each model


Forecast summary:


Predicted percentage increase in daily PM2.5 for the next 30 days


---
