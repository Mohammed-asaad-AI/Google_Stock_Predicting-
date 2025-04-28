# 📈 Stock Price Prediction: Google (GOOG)

This project uses Machine Learning models to predict the future stock prices of Google (GOOG) using historical data.

## 📚 Project Description

We apply two machine learning models:
- Support Vector Machine (SVM)
- Linear Regression

The models are trained on engineered features:
- High-Low Percentage (`HL_PCT`)
- Percentage Change (`PCT_Change`)
- Adjusted Closing Price
- Trading Volume

## 🛠️ Libraries Used
- pandas
- numpy
- matplotlib
- scikit-learn
- pickle

## 🧠 Machine Learning Models
- **SVM** with linear kernel
- **Linear Regression**

Both models are evaluated for accuracy, and the forecasts are plotted to visualize performance.

## 🚀 How to Run
1. Install requirements:
   ```bash
   pip install pandas numpy matplotlib scikit-learn
2. Run the Python script.
3. View the plotted predictions comparing actual prices vs. forecasted prices.

## 📈 Outputs
- Two models: svm_linear.pickle and linearregression.pickle

- Forecast plots comparing both models with actual historical prices.

Author: Mohammed Asaad
Year: 2025
