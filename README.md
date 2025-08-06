 **Gold Price Prediction Using Machine Learning**

 **Project Overview**

This project focuses on predicting gold prices using historical data scraped from Yahoo Finance. The aim is to analyze market trends and apply machine learning models to forecast future prices, helping investors and businesses make informed financial decisions.

**Problem Statement**
Gold is considered a key economic indicator and a safe-haven investment. Accurately predicting its price helps in strategic planning for trading, hedging, and investment. This project uses machine learning algorithms to model and forecast gold prices based on past trends.

**Tools & Technologies**

Language: Python

Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

Modeling: Linear Regression, Random Forest, XGBoost

Web Scraping: yfinance Python package

Environment: Jupyter Notebook

**Dataset**

Source: Yahoo Finance (yfinance library)

Period: Historical gold price data from [Jan 2010] to [Jan 2024]

Features:

Date, Open, High, Low, Close, Volume, Adjusted Close

**Data Preprocessing**

Removed null values and cleaned data

Converted date columns and indexed the dataset

Generated additional features like:

Moving averages (7-day, 30-day)

Percentage returns

Lagged variables for time series modeling

**Exploratory Data Analysis (EDA)**

Visualized gold price trends over time

<img width="1783" height="669" alt="image" src="https://github.com/user-attachments/assets/06399b8c-e2ab-4c00-bc77-2644144c8773" />

Analyzed seasonal patterns and volatility

Correlation matrix to identify feature importance

<img width="812" height="686" alt="image" src="https://github.com/user-attachments/assets/09b1234b-2e9b-4678-ac9b-40826364824a" />


**Model Building**

Regression Models Used:

Linear Regression

Random Forest Regressor

 Ridge Regression
 
 Lasso Regression
 
 Elastic net
 
 Decision Tree Regressor
 
 Gradient Boosting Regressor
 
 Support vector machine 


**Evaluation Metrics:**

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R-squared (R² Score)


**Results**
Model	R² Score	

<img width="400" height="369" alt="image" src="https://github.com/user-attachments/assets/eba05c16-7f21-4f58-a834-2f1cb30e708d" />


**Future Enhancements**

Deploy the model using Flask or Streamlit

Incorporate external economic indicators (e.g., inflation, interest rates)

Fine-tune hyperparameters for improved accuracy

Explore LSTM model for time series forecasting


**My Role**

Web scraped financial data using yfinance

Engineered features and conducted full EDA

Built, compared, and evaluated multiple ML models

Documented insights and created visualizations
