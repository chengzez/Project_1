# Project_1

1. Data Exploration & Preprocessing
- Investigated missing values, outliers, and the statistical properties of the dataset.
- Transformed and cleaned data, normalizing, handling time series gaps.

2. Stationarity Analysis
- Checked for stationarity in time series using Augmented Dickey-Fuller (ADF) Test, KPSS Test, PP Test, Ljung Box Test.
- Differenced the data and applied other transformations to make the series stationary to observe stationarity.
- Ensured that stationarity was maintained for predictive modeling (important for statistical models like ARIMA/GARCH).
  
3.  Lead-Lag Relationship Analysis
- Examined Granger Causality Tests between different features and the LL100 index to identify leading and lagging indicators.
- Used cross-correlations to check whether certain variables predict future index movements.

4. Momentum Strategy
- Design Simulated trading strategies using MA of 5 
- Test and Evaluated different volatility filter
- Mimic volatilty using Gaussian noise and re-evaluate the reuslt
  
5. ARIMA, ARIMAX & LSTM
- Built a forecasting framework using ARIMA, ARIMAX and LSTM
- Evaulate the performance ofthe model
- Did hyperparameter tuning to achieve best reslt
- Implement strategy according to model prediction
   
