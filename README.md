
# 📈 Stock Price Prediction - GOOG (Google)

A machine learning project to forecast Google's stock price using historical data and multiple regression models.

---

## 🧠 What This Project Does

This project:
- Loads historical stock data (Google - GOOG)
- Performs feature engineering (volatility, percentage change)
- Trains and evaluates three models:
  - Support Vector Machine (SVM)
  - Linear Regression
  - Random Forest Regression
- Forecasts future stock prices
- Visualizes predictions vs actual prices

---

## 🔍 Features Used

| Feature        | Description                                      |
|----------------|--------------------------------------------------|
| `Adj Close`    | Adjusted closing price                           |
| `HL_PCT`       | High-Low percentage to reflect daily volatility  |
| `PCT_Change`   | Percentage change between open and close prices  |
| `Volume`       | Trading volume of the stock                      |

---

## 🤖 Models Trained

- ✅ Support Vector Machine (`SVR`)
- ✅ Linear Regression
- ✅ Random Forest Regressor (`100 trees`)

Each model is saved using `pickle` for reuse.

---

## 🧪 Model Performance

Each model's accuracy is evaluated using `.score()` on a test set.

You’ll see results like:

```
Model Accuracy (SVM): 0.79
Model Accuracy (Linear Regression): 0.83
Model Accuracy (Random Forest): 0.88
```

(Note: actual numbers may vary depending on data range.)

---

## 📊 Visualization

- Actual stock price from 2004 onward
- Forecasts shown from the most recent date forward
- Colors:
  - 🔵 Actual Price
  - 🟢 SVM
  - 🔴 Linear Regression
  - 🟠 Random Forest

---

## 🗂 File Structure

```
├── GOOG.csv                   # Input dataset (downloaded)
├── stock_forecasting.py       # Full training and visualization script
├── svm_linear.pickle          # Saved SVM model
├── linearregression.pickle    # Saved Linear Regression model
├── randomforest.pickle        # Saved Random Forest model
├── forecast_plot.png          # Result image (optional)
├── requirements.txt           # Python dependencies
└── README.md                  # Project documentation
```

---

## ▶️ How to Run

```bash
# Clone the repo
git clone https://github.com/yourusername/your-repo.git
cd your-repo

# Install requirements
pip install -r requirements.txt

# Run the model
python stock_forecasting.py
```

---

## 📦 Dependencies

```text
pandas
numpy
matplotlib
scikit-learn
pickle-mixin
```

---

## 👤 Author

**Mohammed Asaad**  
📧 mo.asaad999@gmail.com  
🌍 [LinkedIn](https://www.linkedin.com/in/mohammed-asaad99)

---

## ⚖️ License

This project is licensed under the **MIT License**.  
Feel free to use, modify, or build on it with attribution.
