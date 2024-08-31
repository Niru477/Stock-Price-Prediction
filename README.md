# Stock-Price-Prediction-Using-LSTM
This project focuses on predicting the stock prices of Agriculture Development Bank using a Long Short-Term Memory (LSTM) model. The data was collected from the NEPSE website, covering the date range from 08/13/2019 to 08/13/2024. The dataset includes the following headers: Symbol, Date, Open, High, Low, Close, Percent Change, Volume.
# Introduction
This project aims to develop a predictive model that forecasts stock prices using historical data. The model leverages the power of LSTM, a type of Recurrent Neural Network (RNN), known for its effectiveness in handling time-series data.
# Data Collection
The dataset was sourced from the NEPSE website, specifically focusing on the Agriculture Development Bank. The data spans from 08/13/2019 to 08/13/2024 and includes columns such as Symbol, Date, Open, High, Low, Close, Percent Change, and Volume.
# Data Visualization
Before building the model, extensive data visualization was performed to understand the underlying patterns and trends in the stock prices. This step helped in identifying key features that contribute to the prediction.

# Data Preprocessing
Data preprocessing involved cleaning the dataset by handling missing values, normalizing the data, and creating new features as needed. The cleaned dataset was then prepared for model training.
# Model Building
A sequential LSTM model was constructed, which included:

Input Layer: To receive the processed time-series data.
LSTM Layers: For capturing the temporal dependencies in the stock prices.
Dense Layer: To produce the final output.
The model was trained using the cleaned dataset, and various hyperparameters were tuned to optimize performance.

# Model Loading
The trained model was also loaded to make predictions on new data. This allows for real-time stock price forecasting based on the latest available data.

# Results
The model's performance was evaluated using various metrics such as RMSE. The results demonstrate the model's ability to accurately predict future stock prices, making it a valuable tool for quantitative trading.
# How to Run
To run this project locally, follow these steps:

1. Clone the repository:
git clone https://github.com/Niru477/stock-price-prediction.git
2. Install the required dependencies:
pip install -r requirements.txt
3. Run the model:
python main.py
# Conclusion
This project successfully demonstrates the use of an LSTM model for stock price prediction. The model shows promising results and can be further enhanced with more data and feature engineering.
