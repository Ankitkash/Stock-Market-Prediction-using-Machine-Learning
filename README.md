📈 Stock Market Prediction using Machine Learning

## Project Overview
This project analyzes Tesla and Google stock market data and applies machine learning techniques. Stock market prediction is a challenging task due to market volatility. In this project, we explore historical stock data of Tesla and Google, building an **LSTM-based machine learning model** to forecast future stock prices for Google, while using **regression techniques** for Tesla.

---

## Google Stock Price Prediction

### Dataset
The **Google stock market dataset** includes:
- **Date**: Timestamp of the stock record.
- **Open Price**: The price of the stock at market open.
- **High Price**: The highest recorded price during the trading session.
- **Low Price**: The lowest recorded price during the trading session.
- **Close Price**: The final stock price at market close (used for prediction).
- **Volume**: The number of shares traded.

### Project Workflow
1. **Data Preprocessing**:
   - Load `Google_train_data.csv` and `Google_test_data.csv`.
   - Handle missing values and normalize the data using **MinMaxScaler**.
   - Create sequential input for the LSTM model.
2. **Model Training**:
   - Define an LSTM model with multiple layers.
   - Train using historical **Google** stock prices.
3. **Model Evaluation & Prediction**:
   - Evaluate model performance on test data.
   - Plot actual vs predicted Google stock prices.

---

## Tesla Stock Price Prediction

### Dataset
The **Tesla stock market dataset** includes:
- **Date**: Timestamp of the stock record.
- **Open Price**: The price of the stock at market open.
- **High Price**: The highest recorded price during the trading session.
- **Low Price**: The lowest recorded price during the trading session.
- **Close Price**: The final stock price at market close (used for prediction).
- **Volume**: The number of shares traded.

### Project Workflow
1. **Data Preprocessing**:
   - Load, clean, and normalize Tesla stock market data.  
2. **Exploratory Data Analysis (EDA)**:
   - Identify trends and patterns in stock price movement.  
3. **Model Training**:
   - Implement regression techniques for predicting stock prices.  
4. **Model Evaluation**:
   - Assess model accuracy and performance.  
5. **Visualization**:
   - Compare actual vs. predicted Tesla stock prices.

---

## Technologies Used
- **Python**
- **Pandas** (Data processing)
- **NumPy** (Numerical computations)
- **Matplotlib** (Data visualization)
- **Scikit-learn** (Preprocessing)
- **TensorFlow/Keras** (LSTM model implementation)

---

## Results
- The LSTM model effectively predicts stock price trends for **Google** and regression model predicts **Tesla** stock prices.
- The final visualization compares **actual** and **predicted** stock prices separately for each dataset.
