# StockPriceForecast

Description :

This project forecasts stock prices for Infosys.

Dataset :

Infosys daily stock prices dataset from 2000 - 2021 dataset is used. Data is converted into monthly dataset for simplicity and better interpretibility.

Shape - (5306x14)

Languages and libraries:

This project uses python3, sklearn, numpy, pandas, matplotlib, datetime, statsmodels, pmdarima in jupyter notebook(Anaconda Distribution).

Models and techniques used :

 1. SARIMAX model is used for forecasting.
 2. Autocorrelation and partial autocorrelation plots are used to find p, q and P, Q values for the SARIMAX model.
 3. ADFuller and KPSS test are done to find d and D values.
