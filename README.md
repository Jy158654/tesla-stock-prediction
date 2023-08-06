# tesla-stock-prediction 🗠

## 💡 Overview
This project is set out to explore the relationship between Tesla's historical stock data and Elon Musk's impactful tweets. 

A highlight of this project is the use of stacking model ```XGBoost``` that combines the predictions from the time series forecasting model ```ARIMA``` and the ```large language model (LLM)``` for sentiment analysis on Musk's tweets. This ensemble model aims to make better predictions and achieve better performance than any single contributing model by reducing the spread or dispersion of the predictions and model performance.

## 🗂️ Dataset
For time series forecasting, I have used ```Beautiful Soup``` and ```Selenium``` to scrape tesla's historical stock data from the NASDAQ website, due to its data availability from 2013 to 2023.

For sentiment analysis, I am now using ```Twint``` API due to its limitless usage restriction and is able to retrieve historical tweets beyond the time frame provided by the ```Twitter``` API, to extract the Elon Musk's tweet.

## ⭐ Project Pipeline 
1. Web Scraping
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Model Building
5. Machine Learning



