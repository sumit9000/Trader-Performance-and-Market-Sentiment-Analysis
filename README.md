# Trader-Performance-and-Market-Sentiment-Analysis
This project explores the relationship between trader performance and market sentiment using two primary datasets:

### 1. Bitcoin Market Sentiment Dataset (fear_greed_index.csv): Contains daily sentiment classifications (e.g., "Fear," "Neutral," "Greed").

### 2.Historical Trader Data (historical_data.csv): Includes details on individual trades, such as execution price, size, side (Buy/Sell), and Closed PnL (Profit and Loss).

The objective is to uncover patterns and deliver insights that can help in developing smarter trading strategies. The Python script performs data cleaning, merges the two datasets, and generates visualizations to analyze performance against market sentiment.

# Getting Started

Prerequisites
To run the analysis, you will need a Python environment with the following libraries installed:

### pandas

### matplotlib

### seaborn

### numpy

You can install these using pip:

pip install pandas matplotlib seaborn numpy

# How to Run the Code
Ensure the historical_data.csv and fear_greed_index.csv files are in the same directory as the Python script.

Run the script in a Google collab environment. The code will load the data, perform the analysis, print key findings to the console, and generate the visualizations.

# Analysis and Visualizations

### The script generates two key visualizations, saved as PNG files, that show the core findings of the analysis:

pnl_by_sentiment.png: A bar chart that displays the average Closed PnL for each market sentiment classification (e.g., Extreme Fear, Fear, Neutral, Greed, Extreme Greed). This plot helps to quickly identify if traders are, on average, more profitable during specific market sentiment periods.

pnl_by_sentiment_and_trade_side.png: A grouped bar chart that breaks down the average Closed PnL by both market sentiment and trade side (Buy or Sell). This visualization provides a more granular view, revealing whether buying or selling is more profitable during periods of "Fear" versus "Greed."

# Next Steps
The generated insights can serve as a starting point for developing sentiment-based trading strategies. Further analysis could include examining the performance of specific assets, the impact of leverage on returns, or creating a predictive model.
