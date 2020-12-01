Reliance Closing Price Analysis
Data Source : finance.yahoo.com

1) The data file contains 7 attributes/variables and 6282 observations where data is from 1st January 1996 to 27th November 2020.
2) There are 127 missing values.
3) Attribute/Variable details
    i]   Date  - Date Variable, Particular date
    ii]  Open  - Opening Price on particular date
    iii] High  - How much High the price went / Maximum Price on particular date
    iv]  Low   - How much Low the price went / Minimum Price on particular date
    v]   Close - Closing Price on particular date
                 Close price adjusted for split.
    vi]  Adj Close - Adjusted Closing Price on particular date
                     Adjusted close price adjusted for both dividends and splits.
    vii] Volume - Trading volume is a measure of how much of a given financial asset has traded in a period of time. 

4) Time Series Algorithms used are Simple / Single Exponential Smoothing, Holt's Linear Trend Method / Double Exponential Smoothing,
   Holt's Winter Method / Triple Exponential Smoothing, ARIMA to predict the Average Monthly Closing Price. 
                                  
5) Used RMSE and AIC to evaluate the Models
    RMSE - Root Mean Squared Error
    AIC - Akaike information criterion
