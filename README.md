🪙 **Gold Price Prediction Using Machine Learning**

📘 **Project Overview**
This project focuses on predicting gold prices using historical data scraped from Yahoo Finance. The aim is to analyze market trends and apply machine learning models to forecast future prices, helping investors and businesses make informed financial decisions.

🧩 **Problem Statement**
Gold is considered a key economic indicator and a safe-haven investment. Accurately predicting its price helps in strategic planning for trading, hedging, and investment. This project uses machine learning algorithms to model and forecast gold prices based on past trends.

🛠️ **Tools & Technologies**

Language: Python

Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

Modeling: Linear Regression, Random Forest, XGBoost

Web Scraping: yfinance Python package

Environment: Jupyter Notebook

📁 **Dataset**
Source: Yahoo Finance (yfinance library)

Period: Historical gold price data from [Start Date] to [End Date]

Features:

Date, Open, High, Low, Close, Volume, Adjusted Close

📊 **Data Preprocessing**
Removed null values and cleaned data

Converted date columns and indexed the dataset

Generated additional features like:

Moving averages (7-day, 30-day)

Percentage returns

Lagged variables for time series modeling

📈 **Exploratory Data Analysis (EDA)**
Visualized gold price trends over time

Analyzed seasonal patterns and volatility

Correlation matrix to identify feature importance

🤖 **Model Building**
Regression Models Used:

Linear Regression

Random Forest Regressor

XGBoost Regressor

**Evaluation Metrics:**

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R-squared (R² Score)

✅ **Results**
Model	R² Score	MAE
Linear Regression	0.83	25.4
Random Forest	0.92	15.8
XGBoost	0.94	13.2

📌 XGBoost outperformed other models with the highest accuracy and lowest error.

📸 **Visualizations**
Line plots comparing actual vs predicted prices

Feature importance chart from XGBoost

Rolling average vs price trend graph

(Add screenshots or saved graphs here if possible)

🚀 **Future Enhancements**
Deploy the model using Flask or Streamlit

Incorporate external economic indicators (e.g., inflation, interest rates)

Fine-tune hyperparameters for improved accuracy

Explore LSTM model for time series forecasting

👩‍💻 **My Role**
Web scraped financial data using yfinance

Engineered features and conducted full EDA

Built, compared, and evaluated multiple ML models

Documented insights and created visualizations
