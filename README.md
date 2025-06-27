# Stock-Price-Prediction-LSTM
#  Stock Price Trend Prediction using LSTM

This project uses deep learning (LSTM) to forecast stock price trends based on historical data from Yahoo Finance. It was developed as part of a 2-week internship project to explore financial time series prediction using neural networks.

---

##  Objective

To predict future stock prices using LSTM (Long Short-Term Memory) based on past stock data and evaluate model performance against actual values.

---

##  Tools & Technologies Used

- Python
- Jupyter Notebook
- Keras / TensorFlow
- yfinance
- NumPy & Pandas
- Matplotlib & Seaborn
- Scikit-learn

---

##  Steps Involved

1. **Data Collection**: Fetched data from Yahoo Finance using `yfinance` for a selected stock ticker (e.g., TATASTEEL.NS).
2. **Preprocessing**:
   - Scaled features using `MinMaxScaler`
   - Created sequences for training LSTM
3. **Model Building**: Implemented a multi-layer LSTM using `Keras`
4. **Training & Testing**: Trained and evaluated model performance on historical closing price
5. **Visualization**:
   - Plotted predicted vs actual prices
   - Added Moving Average and RSI analysis

---

##  Sample Output

![Predicted vs Actual] 
*Predicted vs Actual stock price plot*

---

##  Project Structure
Stock-Price-Prediction-LSTM
├── StockPriceLSTM_.ipynb
├── README.md
├── requirements.txt
├── assets/
│ └── output_graph.png
└── Stock_Price_Report.pdf
