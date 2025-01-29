# 📌 Netflix Subscription Forecasting

## 📊 Project Overview
This project aims to forecast Netflix subscription growth using two different time series models:
- **ARIMA (AutoRegressive Integrated Moving Average)**
- **LSTM (Long Short-Term Memory Neural Network)**

The objective is to compare the predictive performance of these models and analyze their effectiveness in forecasting Netflix's subscriber base.

## 📂 Project Structure
```
📁 Netflix_Subscription_Forecasting
│── 📄 netflix_forecasting.py  # Main script for data processing and modeling
│── 📄 requirements.txt        # Dependencies and libraries
│── 📄 README.md               # Project documentation (this file)
│── 📊 data/                   # Folder containing the dataset
└── 📊 results/                # Model predictions and visualizations
```

## 🛠️ Setup Instructions
### 1️⃣ Install Dependencies
Make sure you have Python installed, then run:
```bash
pip install -r requirements.txt
```

### 2️⃣ Run the Model
Execute the script to train the models and generate predictions:
```bash
python netflix_forecasting.py
```

## 📈 Results & Analysis
- **ARIMA Model:** Predicts a linear trend based on past data.
- **LSTM Model:** Captures more complex patterns and non-linearity.
- **Comparison:** Results are visualized to compare both approaches.

## 🏆 Next Steps
- Fine-tune LSTM hyperparameters for better accuracy.
- Evaluate models using RMSE and MAE.
- Test on different time-series datasets.

🔗 **Contributions and suggestions are welcome!** 🚀
