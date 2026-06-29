# Stock Price Prediction using ANN & LSTM

## 📌 Overview
This project predicts stock prices using Artificial Neural Networks (ANN) and Long Short-Term Memory (LSTM) networks. Historical stock market data is analyzed to forecast future stock prices, helping investors make informed decisions.

## 🚀 Features
- Historical stock data analysis
- Data preprocessing and visualization
- Stock price prediction using ANN
- Stock price prediction using LSTM
- Performance comparison between ANN and LSTM
- Visualization of actual vs predicted stock prices

## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- TensorFlow / Keras
- yFinance
- Jupyter Notebook

## 📂 Project Structure

```
Stock-Prediction-ANN-LSTM/
│
├── dataset/
│   └── stock_data.csv
├── models/
│   ├── ann_model.h5
│   └── lstm_model.h5
├── notebooks/
│   └── Stock_Prediction.ipynb
├── images/
│   ├── training_loss.png
│   └── prediction_result.png
├── main.py
├── requirements.txt
└── README.md
```

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/Stock-Prediction-ANN-LSTM.git
cd Stock-Prediction-ANN-LSTM
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

## ▶️ How to Run

```bash
python main.py
```

Or open the Jupyter Notebook:

```bash
jupyter notebook
```

## 📊 Workflow

1. Collect historical stock market data.
2. Preprocess and normalize the dataset.
3. Split the dataset into training and testing sets.
4. Train ANN and LSTM models.
5. Predict future stock prices.
6. Compare actual and predicted values.
7. Visualize the results.

## 📈 Model Architecture

### ANN
- Input Layer
- Hidden Layers (Dense)
- Output Layer

### LSTM
- Input Layer
- LSTM Layers
- Dropout Layers
- Dense Output Layer

## 📸 Results

The LSTM model generally performs better than ANN for time-series forecasting because it captures long-term dependencies in stock market data.

### Evaluation Metrics
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)

## 🎯 Applications
- Stock market forecasting
- Financial analysis
- Investment decision support
- Time-series prediction

## 🔮 Future Enhancements
- Integrate real-time stock data APIs
- Add sentiment analysis from social media/news
- Deploy as a web application
- Support multiple stock predictions simultaneously

## 👩‍💻 Authors
- Your Name

## 📚 References
- Yahoo Finance Dataset
- TensorFlow Documentation
- Keras Documentation
