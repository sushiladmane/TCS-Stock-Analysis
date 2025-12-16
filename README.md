# 📊 TCS Stock Analysis & Price Prediction (Python + ML)

## 🔹 Project Overview

This project performs an **end-to-end analysis of Tata Consultancy Services (TCS) stock data** using Python. It covers **exploratory data analysis (EDA)**, **time-series decomposition**, and a **machine learning model** to predict the **next-day closing price**.

The project is designed to be **portfolio-ready**, easy to understand, and suitable for **data analyst / entry-level ML roles**.

---

## 🔹 Objectives

* Analyze historical stock price movement of TCS
* Identify trends, seasonality, and volume behavior
* Perform time-series decomposition on closing prices
* Build a machine learning model to predict the next day’s closing price
* Present insights in a clear, business-friendly manner

---

## 🔹 Dataset Information

* **Source:** Historical TCS stock price data (NSE)
* **Frequency:** Daily
* **Columns Used:**

  * Date
  * Open
  * High
  * Low
  * Close
  * Volume

---

## 🔹 Tools & Libraries Used

* **Python**
* pandas
* numpy
* matplotlib
* seaborn
* statsmodels (Time Series Decomposition)
* scikit-learn (Machine Learning)

---

## 🔹 Project Workflow

### 1️⃣ Data Loading & Cleaning

* Converted Date column to datetime format
* Sorted data chronologically
* Set Date as index for time-series analysis

### 2️⃣ Exploratory Data Analysis (EDA)

* Closing price trend analysis
* Trading volume analysis
* Correlation heatmap between price features
* Moving averages (20-day & 50-day)

### 3️⃣ Time Series Analysis

* Monthly resampling of closing prices
* Seasonal decomposition into:

  * Trend
  * Seasonality
  * Residuals

### 4️⃣ Feature Engineering

* Created lag-based target variable (next-day closing price)
* Selected price and volume-based features
* Prepared dataset for machine learning

### 5️⃣ Machine Learning Model

* **Algorithm:** Linear Regression
* **Train-Test Split:** Time-series safe split (no shuffling)
* **Target:** Next day closing price

### 6️⃣ Model Evaluation

* RMSE (Root Mean Squared Error)
* R² Score
* Actual vs Predicted price comparison

---

## 🔹 Key Insights

* TCS stock shows a **long-term upward trend**
* Moving averages help identify bullish and bearish phases
* Volume spikes often align with significant price movements
* Linear Regression provides **reasonable short-term predictions**

---

## 🔹 Results

* Successfully built an end-to-end stock analysis pipeline
* Generated interpretable insights from financial time-series data
* Created a baseline ML model suitable for short-term forecasting

---

## 🔹 Future Enhancements

* Implement advanced models (Random Forest, XGBoost, LSTM)
* Add technical indicators (RSI, MACD, Bollinger Bands)
* Build an interactive **Power BI dashboard**
* Automate data refresh using APIs

---

## 🔹 How to Run the Project

1. Clone the repository
2. Install required libraries

   ```bash
   pip install pandas numpy matplotlib seaborn statsmodels scikit-learn
   ```
3. Run the Python script / notebook
4. Review visualizations and model outputs

---

## 🔹 Portfolio Value

This project demonstrates:

* Python data analysis skills
* Time-series understanding
* Machine learning fundamentals
* Business-focused insight generation

---

## 🔹 Author

**Your Name**
Admane Sushil
Aspiring Data Analyst / Machine Learning Enthusiast

---

⭐ *If you find this project useful, feel free to star the repository!*
# TCS-Stock-Analysis
