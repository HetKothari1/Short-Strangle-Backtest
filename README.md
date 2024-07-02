# Short Strangle Strategy Backtesting

## Project Overview
This project involves the development and implementation of a backtesting system for the short strangle options strategy. The strategy was tested by entering trades every day over a one-year period with a 50% stop loss on both legs. The primary goal was to evaluate the strategy's performance through key metrics and visualizations.

![Eqc](https://github.com/HetKothari1/Short-Strangle-Backtest/assets/167286650/00006d59-f1ac-496a-bd17-6db93572223c)

## Data Sources
- Historical options data for one year.
- Data includes option prices, strike prices, expiry dates, and other relevant information.

## Tools
- **Python**: The main programming language used for developing the backtesting system.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical calculations.
- **Matplotlib/Seaborn**: For data visualization.
- **Jupyter Notebook**: For developing and documenting the analysis process.

## Approach
1. **Data Preparation**:
   - Collected and cleaned historical options data.
   - Prepared the data for analysis by filtering and organizing it into a suitable format.

2. **Strategy Implementation**:
   - Implemented the short strangle strategy by simultaneously selling a call and put option closest to Rs. 50 at 09:20 a.m.
   - Applied a 50% stop loss on both legs of the trade to manage risk.
   - Exited the trades when stop loss was hit or at 03:20 p.m.

3. **Backtesting**:
   - Developed a backtesting framework to simulate daily trades over the one-year period.
   - Vectorized the whole process to increase speed and efficiency.
   - Evaluated the strategy’s performance using various metrics such as total profit/loss, average daily return, maximum drawdown, and win rate.

4. **Data Visualization**:
   - Created visualizations to illustrate the performance of the strategy, including equity curves, drawdown charts, and distribution of daily returns.
   - Analyzed the effectiveness of the stop loss mechanism and explored optimization opportunities.

## Results
- Successfully implemented and backtested the short strangle strategy for an entire year.
- Achieved comprehensive performance analysis through key metrics and visualizations.
- Identified the impact of the 50% stop loss on risk management and overall profitability.
- Provided insights into potential strategy optimizations and highlighted conditions under which the strategy performed best.
