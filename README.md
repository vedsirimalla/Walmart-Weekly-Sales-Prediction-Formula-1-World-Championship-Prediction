# Walmart Weekly Sales Prediction & Formula 1 World Championship Prediction

## Project Overview
This project focuses on building predictive models for two distinct datasets:  
1. **Walmart Weekly Sales Prediction**: Seasonal time-series forecasting.  
2. **Formula 1 World Championship Prediction**: Non-seasonal performance prediction and analysis.  

By bridging time-series forecasting and performance analysis, the project demonstrates the application of machine learning to diverse real-world problems.

---

## Walmart Weekly Sales Prediction

### Problem Statement
Walmart faces significant demand fluctuations due to:
- Seasonal variations
- Holidays
- Weather patterns
- Sales campaigns
- Economic factors  

Accurate sales forecasting is essential for:
- **Inventory management**
- **Revenue optimization**
- **Data-driven strategic decision-making**

### Dataset
- Data spans **2010–2012**, capturing:
  - Weekly sales performance across stores and departments.
  - External factors such as holidays and weather.

### Methodology
1. **Data Preprocessing**: Cleaning and structuring data.
2. **Exploratory Data Analysis (EDA)**: Identifying trends and patterns.
3. **Feature Engineering**: Incorporating external factors like holidays and store types.
4. **Model Selection**: Evaluated multiple models:
   - ARIMA
   - SARIMA
   - Auto-ARIMA
5. **Model Evaluation**: Assessed performance using standard metrics.

### Key Findings
- **Holidays** (Thanksgiving, Christmas) drive significant sales peaks.
- **Type A stores** consistently achieve the highest weekly sales during peak periods.
- **Auto-SARIMA** outperformed Auto-ARIMA across all evaluation metrics.

---

## Formula 1 World Championship Prediction

### Problem Statement
Analyze Formula 1 team and driver performance to predict the future World Champion with the highest points in upcoming seasons.

### Dataset
- Data spans **75 years** (1950–2024).
- Includes:
  - **1,144 races**
  - **859 drivers**
  - **212 teams**

### Methodology
1. **Data Preprocessing**: Cleaning and preparing historical data.
2. **Time Series Analysis**: Analyzing trends over decades.
3. **Model Development**: Evaluated models:
   - ARMA
   - ARIMA
   - SARIMA
4. **Performance Evaluation**: Focused on RMSE and other metrics.

### Key Findings
- **ARMA model**: Best-performing model with the lowest RMSE of **90.781**.
- **Altitude impacts team performance**:
  - **Mercedes** excels at high altitudes.
  - **Ferrari** performs best at sea level.
  - **Red Bull** demonstrates consistent adaptability.

---

## Conclusion
This project highlights the power of **data-driven forecasting techniques** in tackling real-world challenges:  
1. **Walmart Weekly Sales Prediction**: Revealed seasonal trends critical for inventory and revenue optimization.  
2. **Formula 1 Prediction**: Provided insights into team and driver performance, aiding in championship forecasting.  

The findings demonstrate how organizations and teams can make informed decisions, optimize performance, and achieve sustained success.

---

## Technologies Used
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**

---

## Contributors
- Kriti C Parikh
- **Statsmodels**
- **pmdarima**
