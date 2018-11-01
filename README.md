This is a project to try and predict the hourly power consumption of the Duquesne Light Company, which supplies electricity around the Pittsburgh area. 

I have been studying time series from the book 'Forecasting: Principles and Practice' by Rob Hyndman, and this is an attempt to practice that. Specifically, the chapter on complex seasonality. For sub-weekly data, Hyndman suggests a few methods:
1. TBATS models
2. MSTL models
3. Dynamic Harmonic Regression models and
4. Using Covariates

In addition, I had heard a lot about the 'prophet' time series package developed by Facebook, and I wanted to try that out.
The best model is the covariate one, where I use hourly weather data from Pittsburgh to predict hourly power consumption. It shows a nearly 50% reduction in both RMSE and MAE over the mean baseline forecast.

Some models might not work in this notebook. The original was run as a kernel on Kaggle. It can be found [here](https://www.kaggle.com/apoorvabhide/energy-consumption-time-series-forecasting-in-r).
