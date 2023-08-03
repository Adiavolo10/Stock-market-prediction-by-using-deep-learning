# Stock-market-prediction-by-using-deep-learning
Stock Market Prediction using Deep Learning Models : 

>Aim and Dataset Background
 
The aim of this project is - to predict stock market prices for two companies, Reliance Industries and Adani Enterprises, using deep learning models such as Stacked Long Short-Term Memory (LSTM) and ARIMA (AutoRegressive Integrated Moving Average) models. The historical data spans the last 5 years and includes various parameters like Date, Open, High, Low, Close, Weighted Average Price (WAP), Number of Shares, Number of Trades, Total Turnover, Deliverable Quantity, % Deliverable Quantity to Traded Quantity, Spread High-Low, and Spread Close-Open. The historical dataset was sourced from Quandl.

>Libraries and Modules
The project code utilized the following libraries and modules:

pandas - For data manipulation and analysis.
matplotlib - For data visualization and creating plots.
statsmodels - For implementing the ARIMA model.
sklearn.metrics - For computing the Mean Squared Error (MSE) in the LSTM model.
seaborn - For creating advanced visualizations.
numpy - For numerical computing and array operations.
tensorflow - For building and training the LSTM model.
pmdarima - The pmdarima module, short for "Pyramid AutoARIMA," is a Python library that provides an easy-to-use interface for implementing AutoARIMA models. 

>Tasks Completed

Data Analysis Task - A correlation heatmap plot was derived between Stock closing prices and the number of trades/total shares bought or sold. This analysis helped to understand the relationships between stock prices and trading activity.

Machine Learning Task - LSTM Model: The dataset was split into training and testing sets, and a 3/2 layer LSTM model (depending on the dataset) was implemented to predict stock prices. The Root Mean Squared Error (RMSE) was calculated to assess the accuracy of the model's predictions.

Machine Learning Task - LSTM Forecasting: After training the LSTM model, the next step involved forecasting stock prices for the upcoming n days (in this case, the next 10 days). This allowed us to assess the model's predictive capabilities for short-term future values.

Machine Learning Task - ARIMA Model: For the Reliance Industries stock, an ARIMA model was implemented. The appropriate values of (p,d,q) were determined using autocorrelation and partial autocorrelation function plots. The ARIMA model was then fitted, and the predicted values were compared with the observed values. Additionally, forecasting was performed for the next 30 days after splitting the dataset into training and testing sets.

> Conclusion 
This project demonstrates the application of deep learning models, specifically LSTM, and traditional time series forecasting models like ARIMA, to predict stock market prices. The repository contains the Python files with the implemented models, the dataset in CSV format, and this README file describing the project and its tasks.
