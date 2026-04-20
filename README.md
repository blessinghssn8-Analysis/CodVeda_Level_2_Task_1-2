# CodVeda_Level_2_Task_1-2
This project analyzes ~497,000 stock market records containing Open, Close, High, Low, Volume, and Date variables. The work demonstrates strong statistical modeling, structured preprocessing, and clear financial data interpretation using Python (pandas, scikit-learn, statsmodels, matplotlib, seaborn).
# Stock Market Price Analysis  
### Regression Modeling and Time Series Decomposition
## Overview

This project analyzes approximately 497,471 historical stock market records containing daily trading data including Open, Close, High, Low, Volume, and Date.  

The study applies Simple Linear Regression and Time Series Analysis to understand price relationships, market trends, and volatility behavior using Python.

## Dataset Description

The dataset contains the following variables:

- Symbols: Stock identifier  
- Date: Trading date  
- Open: Opening price  
- Close: Closing price  
- High: Highest price of the day  
- Low: Lowest price of the day  
- Volume: Trading volume  

This dataset represents structured daily stock market activity suitable for quantitative financial analysis.
## Aim of the Project

The objectives of this project are:

- To analyze the relationship between Open and Close prices  
- To build a Simple Linear Regression model for prediction  
- To study time-based patterns in stock prices  
- To identify trend, seasonality, and noise components  
## Type of Analysis Performed
- Data Cleaning and Preprocessing  
- Exploratory Data Analysis  
- Simple Linear Regression  
- Model Evaluation (R² and MSE)  
- Time Series Decomposition  
- Moving Average Smoothing
  
## Methodology

The analysis followed a structured workflow:

1. Load and inspect dataset  
2. Handle missing values  
3. Convert Date column to datetime format  
4. Sort data chronologically  
5. Select features (Open as predictor, Close as target)  
6. Split data into training and testing sets (80/20)  
7. Train Linear Regression model  
8. Evaluate model using R² and MSE  
9. Perform time series decomposition (trend, seasonality, residuals)  
10. Apply rolling mean smoothing (7-day and 30-day windows)  

## Results

### Linear Regression Results

- R-squared (R²): 0.9997  
- Mean Squared Error (MSE): 2.726  
- Coefficient (Slope): ~0.9999  

The model shows an almost perfect linear relationship between Open and Close prices, indicating extremely high predictive alignment within same-day price movements.


### Time Series Results

- Clear long-term upward/downward trends observed  
- Weak or minimal seasonal patterns detected  
- Residuals capture short-term market volatility  
- Moving averages effectively smooth noise and highlight trends  

## Key Insights

- Open and Close prices are almost perfectly linearly correlated  
- Same-day price prediction is highly accurate  
- Market behavior is primarily trend-driven  
- Volatility is captured in residual components  
- Smoothing techniques improve interpretability of price movements  


## Recommendations

- Extend analysis to forecast future (next-day) prices  
- Use log returns instead of raw prices for stronger financial modeling  
- Include additional features such as Volume and price ranges  
- Apply advanced models (ARIMA, SARIMA, or Machine Learning regression)  
- Conduct symbol-level analysis for deeper insights  

---

## Tools Used

- Python  
- pandas  
- numpy  
- scikit-learn  
- statsmodels  
- matplotlib  
- seaborn  
- Google Colab  


## Conclusion

This project demonstrates structured financial data analysis using regression and time series techniques. The results show strong statistical relationships and provide a foundation for more advanced predictive modeling in financial markets.
