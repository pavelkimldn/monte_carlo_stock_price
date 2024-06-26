### Project Description: Monte Carlo Simulation for Stock Price Prediction

**Purpose**:

The purpose of this project is to simulate future stock prices using the Monte Carlo method. By leveraging historical stock price data, the project aims to estimate the potential future price distributions of a given stock. This simulation helps in understanding the range of possible future outcomes and the associated risks, which is valuable for financial analysis and decision-making.

**Method**:

The method begins with data collection, where historical stock price data is fetched using the 'yfinance' library. In this example, the stock used is JPMorgan Chase & Co. (JPM), but the method can be applied to any stock by changing the ticker symbol. The Monte Carlo simulation involves calculating daily returns from the historical stock prices. From these returns, the mean return, variance, drift, and standard deviation are computed. Multiple simulations (e.g., 20 in this example) are then performed to generate a distribution of possible future prices. Each simulation represents a potential future price path over a specified number of trading days, typically 252, representing one trading year.

**Visualizations**:

The project includes several visualizations to effectively communicate the results of the simulations. The line plot of simulations visualizes the simulated paths of the stock price over 252 trading days, with each line representing a possible future price path and illustrating the range of potential outcomes.

![github](https://github.com/pavelkimldn/monte_carlo_stock_price/blob/main/image%201.png)

The final price distribution is shown using a histogram, which displays the distribution of final stock prices after all simulations, helping to understand the frequency and spread of the predicted prices. 

![github](https://github.com/pavelkimldn/monte_carlo_stock_price/blob/main/image%202.png)

Additionally, a confidence interval plot is provided, showing the mean stock price with confidence intervals (1 and 2 standard deviations), which helps in understanding the central tendency and variability of the simulated stock prices. These visualizations make the data more accessible and understandable, demonstrating advanced skills in data analysis and visualization.

![github](https://github.com/pavelkimldn/monte_carlo_stock_price/blob/main/image%203.png)



