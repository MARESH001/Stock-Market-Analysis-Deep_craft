# Stock-Market-Analysis-Deep_craft
# Stock Price Prediction

## Overview

Stock (also known as equity) is a security that represents the ownership of a fraction of a corporation. This entitles the owner of the stock to a proportion of the corporation's assets and profits equal to how much stock they own. Units of stock are called "shares." A stock is a general term used to describe the ownership certificates of any company. 

Stock prices change every day due to market forces. If more people want to buy a stock (demand) than sell it (supply), then the price moves up. Conversely, if more people want to sell a stock than buy it, there would be greater supply than demand, and the price would fall. Understanding supply and demand is easy. However, predicting how stock prices will change is complex and uncertain. While some believe that it's not possible to predict price changes, others think that analyzing charts and past movements can help determine when to buy and sell. One certainty is that stocks are volatile and can change in price rapidly.

## Understanding the Problem Statement

Broadly, stock market analysis is divided into two parts: **Fundamental Analysis** and **Technical Analysis**.

- **Fundamental Analysis** involves analyzing a company’s future profitability based on its current business environment and financial performance.
- **Technical Analysis** focuses on reading charts and using statistical figures to identify trends in the stock market.

Our focus will be on technical analysis and visualization. We’ll be using a dataset from Stock Prices for training and testing.

## Implementation Steps

1. **Using Scikit-Learn (Machine Learning Model)**
2. **Data Preprocessing Using Dataset**
3. **Visualization of Dataset**
4. **Feature Scaling**
5. **Preparing the Datasets for Training**
6. **Model Development using ARIMA**
8. **Implementation of Sequential, Dense, LSTM, and Dropout Layers**
9. **Preprocessing the Data**
10. **Predicting the Output**
11. **Result Visualization**

## Evaluation Results

The following evaluation metrics were calculated for the model's performance:

- **Mean Absolute Error (MAE)**: 4.8973
- **Mean Squared Error (MSE)**: 27.0938
- **Root Mean Squared Error (RMSE)**: 5.2052
- **R-squared**: -8.2559

## Statistical Summary

In addition to identifying outliers, we computed basic statistics for each relevant feature to better understand the data distribution:

| Feature                   | Count  | Mean      | Std Dev   | Min    | 25%    | 50%    | 75%    | Max        |
|---------------------------|--------|-----------|-----------|--------|--------|--------|--------|------------|
| Closing Price             | 9016   | 88.5444   | 44.0169   | 33.00  | 51.80  | 83.90  | 108.03 | 243.10     |
| Opening Price             | 9016   | 88.5982   | 44.0968   | 33.00  | 51.90  | 84.00  | 108.10 | 243.10     |
| High Price                | 9016   | 89.4809   | 44.4727   | 33.20  | 52.40  | 84.80  | 109.70 | 245.10     |
| Low Price                 | 9016   | 87.7286   | 43.7323   | 32.20  | 51.20  | 83.10  | 107.00 | 241.20     |
| Trading Volume            | 9016   | 173637400 | 124323300 | 9340000|83002500|155100000|231652500|1200000000 |
| Percentage Change Rate     | 9016   | 0.0145    |1.8544     |-14.74   |-0.93    |0       |0.90    |12.63       |

### Outlier Detection Results

During the analysis of the stock price dataset, we identified several outliers across different features:

- **Outliers in Closing Price**:
    - Number of Outliers: **229**
  
- **Outliers in Opening Price**:
    - Number of Outliers: **230**

- **Outliers in High Price**:
    - Number of Outliers: **228**

- **Outliers in Low Price**:
    - Number of Outliers: **229**
### Conclusion

This project aims to provide insights into stock price prediction using machine learning techniques, focusing on technical analysis methods and improving accuraccy of the stock price prediction.

---

Feel free to modify any sections or add additional details specific to your project! If you need further assistance or adjustments, let me know!
