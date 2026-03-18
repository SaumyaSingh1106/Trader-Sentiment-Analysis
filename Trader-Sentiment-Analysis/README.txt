Trader Behavior vs Market Sentiment Analysis

Project Overview

This project explores how Bitcoin market sentiment, measured using the Fear & Greed Index, influences trader behavior and trading performance. By combining sentiment data with historical trading activity, the analysis identifies patterns in trade frequency, trade size, and profitability across different market regimes.

The objective is to understand whether trader decisions and outcomes vary significantly during Fear vs Greed periods, and to derive actionable trading insights from these patterns.

 Data Sources

The analysis combines two datasets:

1. Bitcoin Fear & Greed Index
   Provides daily market sentiment classification ranging from Extreme Fear to Extreme Greed.

2. Hyperliquid Trader Data
   Contains historical trading information including trade size, profit and loss (PnL), and trading activity.

Both datasets were aligned using timestamps to enable day-level sentiment comparison.

Methodology

The analysis was conducted in several stages:

 1. Data Preparation

 Converted timestamps into a standardized datetime format
 Cleaned missing and duplicate records
 Merged trader data with sentiment data by date

 2. Feature Engineering

Key trading metrics were created, including:

Trade Size
Profit & Loss (PnL)
Trading Activity

 3. Sentiment-Based Analysis

Trader behavior was analyzed across different sentiment regimes

 Fear
 Neutral
 Greed

Comparisons were made to evaluate how sentiment influences trading patterns and performance.

 Key Insights

Higher Trading Activity During Greed
  Traders tend to execute more trades when the market sentiment is optimistic.

Increased Risk-Taking in Bullish Sentiment
  Average trade sizes increase during Greed periods, indicating higher risk appetite.

Higher Volatility During Fear Periods
  Losses tend to increase during Fear regimes, suggesting that market uncertainty amplifies downside risk.

 Strategy Implications

Based on the analysis, the following strategy insights emerge:

Risk Management During Fear
  Traders should reduce position sizes during Fear periods to protect capital.

Momentum Opportunities During Greed
  Increased participation during Greed sentiment may help capture momentum-driven gains.

Adaptive Trading Strategies
  Adjusting trading behavior based on sentiment signals may improve overall performance.

Tools & Technologies
 Python
 Pandas
 Matplotlib
 Seaborn
 Google Colab


How to Run the Project

1. Clone the repository
2. Install required libraries

pip install pandas matplotlib seaborn

3. Open the notebook

analysis.ipynb

Run the notebook to reproduce the analysis and visualizations.

Future Improvements

 Incorporate additional market indicators such as volatility and funding rates
 Apply machine learning models to predict trader performance under different sentiment regimes
 Extend analysis to other crypto exchanges for broader insights



 Author

Saumya Singh

