![](https://www.scheperfinancial.com/sites/scheperfinancial.com/files/styles/large/public/portfolio-analysis_0.jpg?itok=BTUnBqPW)

# Background
You need to create a tool (an analysis notebook) that analyzes and visualizes the major metrics of the portfolios across all of these areas, and determine which portfolio outperformed the others. You will be given the historical daily returns of several portfolios: some from the firm's algorithmic portfolios, some that represent the portfolios of famous "whale" investors like Warren Buffett, and some from the big hedge and mutual funds. You will then use this analysis to create a custom portfolio of stocks and compare its performance to that of the other portfolios, as well as the larger market (S&P 500 Index).

# Instructions
Use Pandas to read the following CSV files as a DataFrame. Be sure to convert the dates to a DateTimeIndex.

Detect and remove null values.

If any columns have dollar signs or characters other than numeric values, remove those characters and convert the data types as needed.


The whale portfolios and algorithmic portfolio CSV files contain daily returns, but the S&P 500 CSV file contains closing prices. Convert the S&P 500 closing prices to daily returns.


Join Whale Returns, Algorithmic Returns, and the S&P 500 Returns into a single DataFrame with columns for each portfolio's returns.

Visit Google Sheets and use the built-in Google Finance function to choose 3-5 stocks for your portfolio.

Download the data as CSV files and calculate the portfolio returns.


Calculate the weighted returns for your portfolio, assuming equal number of shares per stock.


Add your portfolio returns to the DataFrame with the other portfolios.


Run the following analyses:

Calculate the Annualized Standard Deviation.
Calculate and plot rolling std with a 21-day window.
Calculate and plot the correlation.
Calculate and plot beta for your portfolio compared to the S&P 60 TSX.
Calculate the Sharpe ratios and generate a bar plot.



How does your portfolio do?