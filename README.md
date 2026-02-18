🚀 Project Overview

StockSense is a data analysis mini-project that explores historical stock market trends of major technology companies using real-world financial data. The project focuses on Amazon (AMZN) and compares its performance with other Big Tech stocks such as Apple (AAPL), Google (GOOGL), and Microsoft (MSFT).

Using Python and Yahoo Finance data, this project performs trend analysis, daily return calculations, and correlation analysis to uncover patterns in stock price movements.

This project demonstrates practical skills in data analytics, financial analysis, visualization, and working with external APIs.

🎯 Objectives

Fetch real-time and historical stock market data

Analyze stock price trends (Up vs Down days)

Compute daily returns for multiple stocks

Visualize correlations between major tech companies

Build insights from financial time-series data

🧠 Key Features

✔ Download 5 years of historical stock data using yfinance
✔ Perform trend classification (Up days vs Down days)
✔ Visualize stock movement distribution
✔ Calculate daily returns
✔ Generate correlation heatmaps between stocks
✔ Exploratory financial data analysis

🛠️ Tech Stack

Python

yfinance (financial data API)

Pandas & NumPy (data processing)

Matplotlib & Seaborn (visualization)

Jupyter Notebook (analysis environment)

📁 Project Structure
mini-project/
│
├── Mini_Project.ipynb   # Jupyter Notebook with full analysis
├── README.md           # Project documentation
└── requirements.txt    # Python dependencies (optional)

📈 Sample Analysis

The notebook includes:

Trend distribution of Amazon stock (Up vs Down days)

Daily return computation for AMZN, AAPL, GOOGL, MSFT

Correlation heatmap showing relationships between tech stocks

These analyses help answer questions like:

Do major tech stocks move together?
How volatile is Amazon compared to other tech stocks?

⚙️ How to Run Locally

Clone the repository

git clone https://github.com/your-username/stock-sense.git
cd stock-sense


Install dependencies

pip install yfinance pandas numpy matplotlib seaborn jupyter


Run the notebook

jupyter notebook Mini_Project.ipynb

💡 Use Cases

Financial market analysis

Data analytics portfolio project

Business intelligence practice

Foundation for predictive modeling in finance

🔮 Future Improvements (Version 2 Ideas)

Add stock price prediction using ML (LSTM / regression)

Build an interactive Streamlit dashboard

Integrate financial news sentiment analysis

Add technical indicators (RSI, MACD, Moving Averages)
