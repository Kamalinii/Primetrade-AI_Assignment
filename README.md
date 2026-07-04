# Primetrade-AI_Assignment
# PrimeTrade.ai Hiring Assignment

## Relationship Between Bitcoin Market Sentiment and Trader Performance

**Author:** Kamalini

---

## Project Overview

This project investigates the relationship between **Bitcoin market sentiment** and **trader performance** using historical trading data from Hyperliquid and the Bitcoin Fear & Greed Index.

The objective is to analyze how different market sentiment conditions (Fear, Extreme Fear, Greed, etc.) influence trading behavior, profitability, and overall trading performance. The project combines data preprocessing, exploratory data analysis (EDA), statistical analysis, and data visualization to uncover actionable insights that can support smarter trading strategies.

---

##  Objectives

- Analyze historical cryptocurrency trading data.
- Integrate Bitcoin Fear & Greed Index with trading records.
- Explore the relationship between market sentiment and trading performance.
- Identify trading patterns across different market conditions.
- Generate business insights and recommendations through data-driven analysis.

---

##  Datasets Used

### 1. Historical Trader Data
Contains detailed trade-level information including:

- Account
- Coin
- Execution Price
- Trade Size (Tokens & USD)
- Side (Buy/Sell)
- Timestamp
- Start Position
- Closed PnL
- Trading Fee

### 2. Bitcoin Fear & Greed Index

Contains daily Bitcoin market sentiment with:

- Date
- Sentiment Classification
- Sentiment Score

---

##  Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📁 Project Structure

```
PrimeTrade_Assignment/
│
├── historical_data.csv
├── fear_greed_index.csv
├── PrimeTrade_Market_Sentiment_Analysis
├── README.md
└── requirements.txt
```

---

##  Project Workflow

### 1. Data Collection

- Load historical trader dataset.
- Load Bitcoin Fear & Greed Index dataset.

### 2. Data Preprocessing

- Handle missing values
- Remove duplicate records
- Convert timestamps into datetime format
- Convert numerical columns to appropriate data types
- Create common date field for merging

### 3. Data Integration

Merge trader data with daily Bitcoin market sentiment using the Date column.

### 4. Exploratory Data Analysis (EDA)

The notebook includes:

- Dataset overview
- Descriptive statistics
- Missing value analysis
- Distribution analysis
- Profitability analysis
- Market sentiment analysis
- Coin-wise performance
- Trader-wise performance

### 5. Data Visualization

Visualizations include:

- Market Sentiment Distribution
- Average Profit by Market Sentiment
- Profit Distribution
- Buy vs Sell Analysis
- Top Performing Coins
- Top Performing Traders
- Correlation Heatmap
- Winning Trade Percentage
- Trade Size vs Closed PnL
- Trading Performance Dashboard

### 6. Statistical Analysis

- Summary statistics
- Correlation analysis
- Profitability metrics
- Win rate analysis

### 7. Business Insights

The project concludes with:

- Key findings
- Trading recommendations
- Final conclusions

---

## Key Findings

- Market sentiment influences trader profitability.
- Profitability varies significantly across different sentiment conditions.
- Trade size alone does not guarantee higher profits.
- A small number of traders contribute a large share of cumulative profits.
- Certain cryptocurrencies consistently outperform others.
- Winning trade percentage differs across market sentiment categories.

---

##  Recommendations

- Incorporate market sentiment into trading decisions.
- Use disciplined risk management during periods of Fear and Extreme Fear.
- Monitor historical trader performance to identify successful strategies.
- Focus on consistently profitable cryptocurrencies.
- Combine sentiment indicators with technical analysis for better decision-making.

---

## How to Run the Project

### Install dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
PrimeTrade_Market_Sentiment_Analysis.ipynb
```

Run all notebook cells sequentially.

---

## Expected Output

The notebook generates:

- Cleaned and merged dataset
- Descriptive statistics
- Exploratory Data Analysis (EDA)
- Interactive visualizations
- Correlation analysis
- Trading performance dashboard
- Business insights
- Trading recommendations
- Final conclusion

---

## Author

**Kamalini**

PrimeTrade.ai Hiring Assignment – July 2026
