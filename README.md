# Multivariate-Financial-Time-Series-Analysis

## Data acquisition

In this study, I utilized Google stock prices from January 2016 to June 2018 as the dependent variable. I employed Topic Modeling techniques such as NMF and LDA to identify relevant topics from articles about Google and used them as independent features. Additionally, I utilized Textblob to obtain the sentiment index of Google from major US newspapers. Furthermore, I extracted Google Trends Indices of these features, as well as stock prices/ETF prices data, to be used as additional independent features.

## Data Pre-processing

Including data resampling (convert weekly data into daily), data scaling (normalize the data to get rid of the unit inifluence and prepare for machine learning usage) and stationary (basic assumption in time series analysis).

Plot of GOOGL stock prices and Google Trends search frequency data (Before Data Scaling)

![]

Plot of GOOGL stock prices and Google Trends search frequency data (After Data Scaling)

![]

## Feature Selection

Ridge, LASSO and ElasticNet Regression

## Apply Different Models

Including ARIMAX, k-NN Regression, Decision Tree, Random Forest and LSTM networks.

ARIMAX (Actual vs Prediction) Plot

![]

k-NN Regression (Actual vs Prediction) Plot

![]

Decision Tree (Actual vs Prediction) Plot

![]

Random Forest (Actual vs Prediction) Plot

![]

LSTM (Actual vs Prediction) Plot

![]

## Prediction Accuracy Comparison
Use RMSE and Out-of-Sample prediction plots.

![]

We find ARIMAX as the best fitting model