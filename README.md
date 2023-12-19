# Stock Price Prediction

### Overview
This project focuses on predicting stock prices for major companies, including Apple (AAPL), Tesla (TSLA), and Google (GOOG), using advanced forecasting models such as ARIMA and LSTM. The primary goal is to achieve accurate predictions and gain insights into stock price movements.

### Table of Contents
[Introduction](https://github.com/SmitPanchal1999/Stock-Price-Prediction#introduction)
[Data Preprocessing and Exploratory Data Analysis (EDA)](https://github.com/SmitPanchal1999/Stock-Price-Prediction#data-preprocessing-and-exploratory-data-analysis-(EDA))
[ARIMA Model](https://github.com/SmitPanchal1999/Stock-Price-Prediction#arima-model)
[LSTM Model](https://github.com/SmitPanchal1999/Stock-Price-Prediction#lstm-model)
[Results](https://github.com/SmitPanchal1999/Stock-Price-Prediction#results)
[Graphs Discussion](https://github.com/SmitPanchal1999/Stock-Price-Prediction#graphs-discussion)
[Conclusion](https://github.com/SmitPanchal1999/Stock-Price-Prediction#conclusion)
[Future Work](https://github.com/SmitPanchal1999/Stock-Price-Prediction#future-work)
[Technologies Used](https://github.com/SmitPanchal1999/Stock-Price-Prediction#technologies-used)
[How to Run the Code](https://github.com/SmitPanchal1999/Stock-Price-Prediction#how-to-run-the-code)
[References](https://github.com/SmitPanchal1999/Stock-Price-Prediction#references)

### Introduction
Stock price prediction is a critical aspect of financial analysis, helping investors make informed decisions. This project explores the use of ARIMA and LSTM models for accurate predictions, leveraging historical stock data.

### Data Preprocessing and EDA
Data preprocessing involved cleaning and organizing the stock data for analysis. Exploratory Data Analysis (EDA) techniques were employed to gain insights into stock price trends, correlations, and moving averages, enhancing the effectiveness of the predictive models.

### ARIMA Model
The AutoRegressive Integrated Moving Average (ARIMA) model was utilized for its ability to capture time series patterns. The Dickey-Fuller test assessed stationarity, and logarithmic transformation was applied to handle non-stationarity. ARIMA successfully predicted stock prices, considering historical patterns.

### LSTM Model
Long Short-Term Memory (LSTM) networks, a type of recurrent neural network (RNN), were employed for their capability to capture sequential dependencies in time series data. The custom learning rate was implemented to optimize model training. The LSTM model demonstrated superior performance compared to ARIMA.

### Results
Detailed results for each stock (AAPL, TSLA, GOOG) are as follows:
![RMSE & MAPE metrics of APPL, TSLA, and GOOG using ARIMA Model](./Images/Table_arima_results.png)
![RMSE & MAPE metrics of APPL, TSLA, and GOOG using LSTM Model](./Images/Table_lstm_results)

Graphs Discussion
Graphs depicting the predicted vs. actual stock prices for each company were analyzed. The visual representations provided additional insights into the models' performance and their ability to capture price trends accurately.
![Prediction graph of APPL using ARIMA Model](./Images/apple_arima_new_graph)
![Prediction graph of APPL using LSTM Model](./Images/apple_lstm_new_graph)
![Prediction graph of GOOG using ARIMA Model](./Images/google_arima_new_graph)
![Prediction graph of GOOG using LSTM Model](./Images/google_lstm_new_graph)
![Prediction graph of TSLA using ARIMA Model](./Images/tesla_arima_new_graph)
![Prediction graph of TSLA using LSTM Model](./Images/tesla_lstm_new_graph)

### Conclusion
In conclusion, the LSTM model outperformed ARIMA in stock price prediction, achieving lower RMSE and MAPE values. This project highlights the significance of leveraging advanced machine learning models for accurate financial forecasting.

### Future Work
Future work may involve exploring additional deep learning architectures, incorporating external factors affecting stock prices, and enhancing the models for broader market applications.

### Technologies Used
Python
TensorFlow
Pandas
Matplotlib
Scikit-learn

### How to Run the Code
Clone the repository.
Run the Jupyter notebooks for ARIMA and LSTM models.

## References
