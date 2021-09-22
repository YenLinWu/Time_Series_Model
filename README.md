# Time Series Model

* [Introductions to Stationarity, Differencing and Autocorrelation](https://colab.research.google.com/github/YenLinWu/Time_Series_Model/blob/main/Materials/Stationarity_Differencing_and_Autocorrelation.ipynb)  
* [Introduction to Time Series Models](https://colab.research.google.com/github/YenLinWu/Time_Series_Model/blob/main/Materials/Introduction_to_Time_Series_Models.ipynb)   
* [Order Selection of ARIMA Model](https://colab.research.google.com/github/YenLinWu/Time_Series_Model/blob/main/Materials/Order_Selection_of_ARIMA_Model.ipynb)    
* ARIMA Modelling Procedure    
  (1) Plot the data and identify any unusual observations.  
  (2) If necessary, transform the data (using a [Box-Cox Transformation](https://colab.research.google.com/github/YenLinWu/Time_Series_Model/blob/main/Materials/Box_Cox_Transformation.ipynb)) to stabilise the variance.  
  (3) If the data are non-stationary, take first differences of the data until the data are stationary.  
  (4) Examine the ACF/PACF: Is an ARIMA( p, d, 0 ) or ARIMA( 0, d, q ) model appropriate?  
  (5) Try your chosen model(s), and use the AICc to search for a better model.  
  (6) Check the residuals from your chosen model by plotting the ACF of the residuals, and doing a portmanteau test of the residuals. If they do not look like white noise, try a modified model.   
  (7) Once the residuals look like white noise, calculate forecasts.   
  Example: [Seasonally adjusted electrical equipment orders](https://otexts.com/fpp2/arima-r.html#example-seasonally-adjusted-electrical-equipment-orders)

## References   
[1] [Forecasting: Principles and Practice (2nd ed online version)](https://otexts.com/fpp2/), Rob J Hyndman and George Athanasopoulos   
[2] [statsmodels v0.13.0.dev0](https://www.statsmodels.org/dev/index.html)  
[3] [statsmodels.tsa.statespace.sarimax.SARIMAX](https://www.statsmodels.org/dev/generated/statsmodels.tsa.statespace.sarimax.SARIMAX.html)

## Further Readings  
[1] [Summary of rules for identifying ARIMA models](https://people.duke.edu/~rnau/arimrule.htm), Robert Nau.   
[2] [ARIMA Model – Complete Guide to Time Series Forecasting in Python](https://www.machinelearningplus.com/time-series/arima-model-time-series-forecasting-python/), Selva Prabhakaran, Aug 22, 2021.   
[3] [A Gentle Introduction to SARIMA for Time Series Forecasting in Python](https://machinelearningmastery.com/sarima-for-time-series-forecasting-in-python/), Jason Brownlee,  Aug 18, 2018.   
[4] [Complete Guide To SARIMAX in Python for Time Series Modeling](https://analyticsindiamag.com/complete-guide-to-sarimax-in-python-for-time-series-modeling/), Yugesh Verma, Jul 30, 2021.    
[5] [End-to-End Time Series Analysis and Forecasting: a Trio of SARIMAX, LSTM and Prophet (Part 1)](https://towardsdatascience.com/end-to-end-time-series-analysis-and-forecasting-a-trio-of-sarimax-lstm-and-prophet-part-1-306367e57db8), Bruce Nguyen, Feb 7, 2021.    
  


