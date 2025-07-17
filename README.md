# 📈 Stock Market Analysis — Predicting INFY Opening Price

## 🧠 Project Overview

**Title:** Stock Market Analysis  
**Objective:** Predict the **Opening Price** of INFOSYS (INFY) stock based on historical stock data using machine learning.

This project focuses on applying a supervised learning algorithm to analyze stock market data and forecast the next day's opening price based on past trading data.

---

## 📌 Problem Statement

Stock market prediction is a challenging task due to the volatile and non-linear nature of financial data. The goal is to use a dataset containing historical stock information of INFOSYS (INFY) and apply machine learning to estimate future opening prices based on various trading indicators.

---

## 📊 Dataset Description

The dataset used is `INFY.csv`, which includes:

- **Features (Inputs):**
  - `High`: Highest stock price during the trading day
  - `Low`: Lowest stock price during the trading day
  - `Last`: Last traded price of the stock
  - `Close`: Closing price of the stock
  - `Total Trade Quantity`: Number of shares traded
  - `Turnover (Lacs)`: Total turnover in lakhs
  
- **Target (Output):**
  - `Open`: Opening price of the stock for the day

---

## ⚙️ Methodology

### Steps Performed:
1. Loaded and explored the CSV dataset using `pandas`.
2. Selected features (`x`) from columns `High` to `Turnover (Lacs)`.
3. Chose `Open` as the target variable (`y`).
4. Split the data into training and test sets using `train_test_split`.
5. Trained a **Decision Tree Regressor** model.
6. Tested the model on sample input and evaluated performance using R² score.

---

## 🧪 Machine Learning Model

### ✅ Model Used: Decision Tree Regressor

- Chosen for its simplicity and ability to model non-linear relationships.

### ✅ Pros:
- Simple and easy to understand
- No need for feature scaling
- Captures non-linear patterns
- Quick to train

### ❌ Cons:
- Prone to overfitting on small datasets
- Not as robust or accurate as ensemble methods
- Can be sensitive to small variations in data

---

## 🔁 Alternatives You Can Explore

- **Random Forest Regressor** – Ensemble of decision trees, reduces overfitting.
- **Linear Regression** – For simple linear relationships.
- **Gradient Boosting/XGBoost** – Highly accurate, handles complex patterns well.
- **LSTM (Deep Learning)** – Suitable for sequential time-series prediction.

---

## 💻 How to Run Locally

## ✅ Prerequisites:

- Python 3.x installed on your system
- Install required Python packages:

```bash
pip install pandas scikit-learn
```

## ✅ Prerequisites:

- Clone or download this project directory.
- Run the script using:

```bash
python Stock_DT_algo.py
```

## 🖥️ You Should See:
- The predicted opening price for the provided test input.
- The R² score showing model accuracy on the test data.

## Conclusion
This project provides a basic framework for applying machine learning to stock market data. Using a Decision Tree Regressor, it demonstrates how historical trading features can be used to predict future stock opening prices. While the approach is simple and interpretable, there are many opportunities for enhancement:

- Try advanced models like Random Forest, XGBoost, or LSTM.
- Include more features such as technical indicators or macroeconomic signals.
- Improve model performance with feature engineering and hyperparameter tuning.
- Visualize trends and model predictions for better insights.
- This project lays the groundwork for more sophisticated stock market analysis in the future.



