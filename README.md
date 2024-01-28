**ITC Stock Price Prediction using LSTM**



This project aims to predict the closing price of ITC stock for the next 30 days using Long Short-Term Memory (LSTM) neural networks.
![image](https://github.com/sijoalex157/Stock-Prediction-using-LSTM/assets/136322927/eeeffb84-d999-47ef-8512-248258e49ccb)

The data used consists of 10 years of historical daily closing prices for ITC stock.

The LSTM model was trained on the past 30 days of closing prices to predict the next 30 days.

The model evaluation metrics are:

Mean Absolute Error (MAE): 3.86
Root Mean Squared Error (RMSE): 5.08
These results indicate reasonably accurate predictions given the volatility of stock prices.

The model was implemented in Python using Keras with Tensorflow backend. Key steps included:
![image](https://github.com/sijoalex157/Stock-Prediction-using-LSTM/assets/136322927/9b5a63a0-5b88-4183-b640-65cd9911d9e5)

Data preprocessing: Scaling and transforming prices
LSTM model configuration and training for 50 epochs
Evaluation on test set prices
The results demonstrate that LSTMs can effectively learn the patterns in stock price movements. Further improvements to the model architecture and input features could potentially improve prediction accuracy.

Overall, this project provides a solid foundation for using LSTM neural networks for financial time series forecasting. The code and details are available here on GitHub to serve as a base for further development.
