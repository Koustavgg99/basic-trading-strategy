

# Stock Trading Strategy Analysis

## Description

This project involves analyzing the performance of a simple trading strategy using historical stock price data. The strategy is based on two Simple Moving Averages (SMAs): a short-term SMA (20 days) and a long-term SMA (50 days). The goal is to evaluate the effectiveness of this strategy by calculating key metrics such as total returns, number of trades, winning trades percentage, losing trades percentage, and maximum drawdown.

## Approach

1. **Data Collection:**
   - Downloaded historical stock price data for TCS from Yahoo Finance for the period from August 10, 2022, to August 10, 2024.
   - The dataset includes daily open, high, low, close prices, and volume.

2. **Simple Moving Average (SMA) Calculation:**
   - Calculated the 20-day and 50-day SMAs for the closing prices.
   - Generated buy and sell signals based on the crossovers of these SMAs.

3. **Backtesting:**
   - Implemented a trading strategy where buy signals occur when the short-term SMA crosses above the long-term SMA, and sell signals occur when the short-term SMA crosses below the long-term SMA.
   - Evaluated the strategy's performance by calculating total returns, number of trades, winning trades percentage, losing trades percentage, and maximum drawdown.

4. **Performance Evaluation:**
   - Compared the strategy’s returns against the market returns.
   - Visualized the stock price, SMAs, and equity curves to assess strategy effectiveness.

## Key Insights


1. **Profitability**: The strategy is profitable but underperforms compared to the broader market. This shows it can make money, but not as effectively as just investing in the market itself.

2. **Trade Success Rate:** With only **31.22%** of trades being successful, the strategy has a relatively **low success rate**.This suggests there’s room for improvement in identifying profitable trades.

3. **Risk and Drawdown:** The large maximum drawdown indicates substantial risk.Investors might experience significant declines in their portfolio value, which could be 
concerning for those wary of big losses.

4. **Strategy vs. Market Returns:**

   Strategy Returns: **₹8,332.21** , 
   Market Returns: **₹34,785.18** 
**Interpretation:** The strategy's returns were much lower compared to a simpleinvestment in the market. This suggests that while the strategy is profitable, it hasn't performed as well as a passive market investment.
## Tech Stack

- **Python:** For data analysis and implementation of the trading strategy.
- **yfinance:** To download historical stock price data.
- **pandas:** For data manipulation and calculation of SMAs and strategy returns.
- **numpy:** For numerical operations.
- **matplotlib:** For visualizing the stock price, SMAs, and equity curves.

## Files

- `Stock_Trading_Strategy_Analysis.ipynb`: Jupyter Notebook containing the code and analysis.
- `TCS_data.csv`: CSV file with historical stock price data.


## 🚀 About Me
I'm a fourth-year Computer Science Engineering student with a deep passion for uncovering insights from
data. I'm on the lookout for opportunities in Data Science and Data Analysis where I can put my skills in
machine learning, statistical analysis, and data visualization to good use. I'm enthusiastic about applying
what I've learned to help drive data-driven decisions and make a real impact in the world.


## 🛠 Skills
Python , SQL , PowerBI , Tableau , Statistic , Machine Learning, Excel

