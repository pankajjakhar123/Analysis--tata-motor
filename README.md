
# **TECHNICAL ANALYSIS OF TATA MOTORS STOCK**

## **Project Overview**
This project performs a comprehensive technical analysis of **TATA Motors' stock** using historical data to predict market trends and stock movements. It leverages multiple technical indicators, including Moving Averages (MA), Exponential Moving Averages (EMA), Relative Strength Index (RSI), and the Moving Average Convergence Divergence (MACD). The goal is to uncover valuable insights into the stock's behavior, identify trading signals, and enhance decision-making.

## **Key Features**
- **Historical Data Analysis**: Analyzed historical closing prices of TATA Motors stock over the past 3 years.
- **Technical Indicators**: Implemented Moving Averages, Exponential Moving Averages, RSI, and MACD for identifying trends and patterns.
- **Combined Indicator Model**: Developed a model that combines multiple technical indicators with weighted correlations for better prediction accuracy.
- **Bullish/Bearish Prediction**: Created a methodology for predicting bullish and bearish market positions.
- **Visualization**: Visualized stock trends and signals through charts and graphs to assist in decision-making.
- **Prediction Accuracy**: Evaluated the accuracy of predictions to refine investment strategies.



## **Data Source**
- The dataset used in this project is sourced from the **"TATAMOTORS.NS.csv"** file, which contains historical closing prices of TATA Motors over the last 3 years. 

## **Technical Indicators Used**
1. **Moving Averages (MA)**: Smoothed average of the closing prices over a specified window.
2. **Exponential Moving Average (EMA)**: A weighted moving average giving more importance to recent prices.
3. **Relative Strength Index (RSI)**: Measures overbought or oversold conditions based on price changes.
4. **Moving Average Convergence Divergence (MACD)**: Shows the relationship between two moving averages of a stock's price.

## **Methodology**
1. **Data Preprocessing**: Cleaned and preprocessed the historical stock data to remove any missing or inconsistent values.
2. **Indicator Calculation**: Implemented the formulas for MA, EMA, RSI, and MACD to generate signals.
3. **Prediction Model**: Combined multiple indicators, assigning weights based on their correlation to predict bullish and bearish market positions.
4. **Visualization**: Plotted the stock trends and trading signals to facilitate decision-making.
5. **Accuracy Evaluation**: Compared predicted signals against actual price movements to evaluate the model's performance.

## **Results**
The project provides a set of trading signals (bullish/bearish) based on the technical indicators, along with visualizations of market trends. The accuracy of the predictions is evaluated to refine strategies for potential stock trading decisions.

## **Usage**
1. Run the Python script to fetch the data and perform analysis:

2. View visualizations of stock trends and signals.

## **Acknowledgements**
- Data source: Yahoo Finance
- Python libraries: Pandas, Numpy, Matplotlib, TA-Lib
