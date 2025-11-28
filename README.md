# Saudi Gasoline Consumption Forecasting

Time Series Forecasting Project using SARIMA Model  

This project analyzes and forecasts gasoline consumption in Saudi Arabia using historical monthly data from 2002 to 2024.

---

## Project Overview
The goal of this project is to:
- Explore gasoline consumption patterns over the years
- Analyze seasonality and long-term trends
- Build and evaluate a SARIMA time series model
- Forecast future consumption for upcoming years (2025–2027)

---

## Dataset Description
| Column | Description |
|--------|-------------|
| Time   | Month and Year in format `YY-MMM` |
| Value  | Gasoline consumption in kb/d (thousand barrels per day) |

---

## Steps Completed

### 1. Data Preparation
- Converted Time to datetime format  
- Extracted Year and Month  
- Created a time-series index

---

### 2. Exploratory Data Analysis (EDA)
Visualized key insights using:
- Yearly trend analysis  
- Monthly seasonality  
- Boxplot (monthly variability)  
- Histogram (distribution of consumption)  

---

### 3. Time Series Modeling
- Conducted ADF Test to check stationarity  
- Split data into Train (all except last 12 months) and Test (last 12 months)  
- Trained SARIMA model: (1,1,1)x(1,1,1,12)  

Model Evaluation:


---

### 4. Future Forecasting
Forecasted gasoline consumption for future years (2025–2027), including confidence intervals.

---

## Sample Outputs

| Plot | Description |
|------|-------------|
| Yearly Trend | Long-term consumption growth |
| Monthly Seasonality | Consumption changes by month |
| SARIMA Split | Train vs Test vs Forecast |
| Future Forecast | Consumption prediction for 2025–2027 |

(Replace this section with images)

---

## Tools and Libraries

| Category | Libraries |
|----------|-----------|
| Data Analysis | pandas, numpy |
| Visualization | matplotlib |
| Forecasting | statsmodels (SARIMAX) |
| Evaluation | sklearn |

---

## What I Learned
- How to analyze time-series data  
- Understanding trend, seasonality, and stationarity  
- How to apply SARIMA model  
- Interpreting model performance using MAE and RMSE  

---

## Future Enhancements
- Compare with other models such as ARIMA, Prophet, or LSTM  
- Build a dashboard using Power BI or Tableau  
- Deploy the model using Streamlit  

---

## Author
Reema Bin Mohsen  
LinkedIn: (add your link)  
Email: (add your email)


