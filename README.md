# Dogecoin EDA and Prediction with Machine Learning

This project involves the exploratory data analysis (EDA) and prediction of Dogecoin prices using historical data from Yahoo Finance. The primary goal is to understand Dogecoin's price trends and develop a model to forecast future prices.

## Dataset Description

The dataset includes historical price data of Dogecoin with the following columns:
- **Date**: Trading date
- **Open**: Opening price on the trading day
- **High**: Highest price during the trading day
- **Low**: Lowest price during the trading day
- **Close**: Closing price on the trading day
- **Adj Close**: Adjusted closing price
- **Volume**: Volume of Dogecoin traded

## Exploratory Data Analysis (EDA)

The EDA section of the project includes:
1. **Closing Price Over Time**: Analysis of the closing price trends. The highest recorded closing price was around 0.22 INR.
2. **Trading Volume Over Time**: Analysis of trading volume trends. The highest trading volume observed was approximately 9 billion Dogecoins.
3. **High and Low Prices Over Time**: Analysis of price volatility. The highest recorded price was around 0.225 INR, while the lowest was around 0.05 INR.
4. **Moving Averages**: Calculation of 50-day and 200-day moving averages to identify trends.
5. **Volatility Analysis**: Examination of daily percentage changes to understand periods of high volatility.

## Prediction

A linear regression model was used to predict the closing prices of Dogecoin. The steps include:
1. **Data Preparation**: Convert dates to ordinal values and split the dataset into training and testing sets.
2. **Model Training**: Train the linear regression model.
3. **Prediction**: Predict the closing prices for the test set.
4. **Evaluation**: Evaluate the model's performance using Mean Squared Error (MSE), which was approximately 0.00058.

## Results

The model provided a basic prediction of Dogecoin's closing prices. The EDA revealed important insights about price trends, trading volumes, and volatility, which can be useful for further analysis and model improvement.

## Usage

To replicate this analysis and prediction, follow these steps:

1. Download the dataset from Yahoo Finance:
   - Visit [Yahoo Finance](https://finance.yahoo.com/)
   - Search for "Dogecoin"
   - Click on "Historical Data"
   - Download the data

2. Ensure the necessary Python libraries are installed:
   ```bash
   pip install pandas numpy matplotlib scikit-learn
   ```

3. Run the Jupyter notebook provided in this repository.

## Conclusion

This project demonstrates the application of EDA and basic predictive modeling on Dogecoin price data. While the linear regression model offers a starting point, further improvements can be made with more advanced modeling techniques.
