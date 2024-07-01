# Stock Price Prediction Project
**This project tackles stock price prediction for Tata Global Beverages (NSE: TATAGLOBAL) using a LSTM model and visualizes predictions with an interactive dashboard.**

Part 1: LSTM Stock Price Prediction
- Data Acquisition: We obtain historical stock price data (Open, High, Low, Close, Volume) for TATAGLOBAL from the NSE dataset.
- Data Preprocessing: The data is cleaned and formatted including converting dates into numerical representations for the LSTM model. 
- LSTM Model Building: Here we built a LSTM model to predict future closing prices. 
- Model Training: The model is trained on historical data, learning to identify patterns that influence stock price movements.
- Prediction Visualization: Of predicted stock costs with actual stock costs

Part 2: Interactive Dashboard
- Framework Selection: We utilize Plotly Dash, a Python framework, to create an interactive dashboard for visualizing predictions.
- Data Integration: The predicted closing prices and actual closing prices are integrated into the dashboard.
- Visualization Components: The dashboard displays interactive charts and graphs. These might include:
- - Line chart showing historical closing prices and the predicted price trend.
- - Scatter plot for comparing predicted prices to actual closing prices.
- User Interaction: Users can explore the dashboard to:
- - View high and low price trends.
- - Analyze the model's predicted price movement.

Refered: https://data-flair.training/blogs/stock-price-prediction-machine-learning-project-in-python/

The following are some output examples:

![image](https://github.com/devikajonjale/stockprice_prediction/assets/119109892/20c1d117-f054-477a-848f-b0cba60f74f6)

![image](https://github.com/devikajonjale/stockprice_prediction/assets/119109892/9a810646-2a7d-468c-bcc1-85ce5ae28c4a)

![image](https://github.com/devikajonjale/stockprice_prediction/assets/119109892/144a1629-ae9e-456b-88c5-797686a3fb22)

![image](https://github.com/devikajonjale/stockprice_prediction/assets/119109892/31f44ce0-37e4-43ef-bcc0-39e969444eea)
