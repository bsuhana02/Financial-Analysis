# Financial-Analysis

**Overview:** This assignment involves a quantitative finance task designed to assess your proficiency in data analysis, quantitative methodologies, and algorithm development. The project also requires basic knowledge of statistical testing and risk assessment.

**Assignment Objectives:**

1. Data Retrieval: Begin by setting up a robust Python environment within a Jupyter Notebook. Download financial data from Google Drive, specifically the EOD Hover Data and EOD ESV Data, for analysis.
2. Stock Selection: Determine the number of stocks to purchase based on the investing amount, considering the following conditions:
If the investment amount is between ₹500 and ₹50,000, purchase 3 stocks.
If the investment amount is between ₹50,001 and ₹1,000,000, purchase 4 stocks.
Otherwise, purchase 5 stocks(max)
3.Investment Amount Capping: Calculate the maximum amount of money that can be invested in each stock based on the number of stocks determined in Step 2 to mitigate risk.
4. Stock Filtering: Implement a comprehensive set of filtering conditions, including statistical tests, to select stocks meeting specific criteria. These conditions encompass: (conditions detailed at end)
Daily Moving Average Price (MP200) matching a specified value.
Daily Moving Average Price (MP50) matching another specified value.
Daily Relative Strength Index (RSI) falling within a range.
Monthly RSI and Weekly RSI exceeding certain thresholds.
Hourly Moving Price (MP50) and other conditions.
5. Stock Sorting: Sort the filtered stocks based on Daily PDEMA20 and Daily RSI.
6. Top Stock Selection: Select the top-performing stocks from the filtered list on a given date.
7. Portfolio Churning: Implement the logic for churning stocks on a monthly basis, calculating profit and loss for the current basket. Handle exceptions when the number of filtered stocks is insufficient.
8. Volatility Calculation: Calculate daily portfolio volatility on an aggregate level (sum of all stocks) and plot it against the Nifty index. Utilize statistical tests to analyze portfolio performance.  Plot this volatility against the Nifty index to assess portfolio risk.
9. Final Portfolio Evaluation: Track the portfolio's value over time, and provide the final value of the portfolio as of the current date.
10. Professional Jupyter Notebook: Create a well-documented Jupyter Notebook that includes clear explanations, comments, and markdown cells. Highlight the statistical tests, assumptions, and challenges faced during the assignment.
11. Testing and Visualization: Rigorously test your code with sample data and provide visualizations, graphs, or charts to demonstrate the portfolio's performance, including statistical analysis results.
Statistical Testing: To enhance the robustness of your analysis, consider incorporating statistical tests such as hypothesis testing, regression analysis, or Monte Carlo simulations where relevant. Statistical tests can provide deeper insights into stock selection and portfolio performance.
Conclusion: This assignment is designed to assess your ability to apply quantitative finance concepts and programming skills to real-world financial data. It also evaluates your proficiency in statistical testing, a crucial aspect of quantitative finance analysis. We look forward to your comprehensive and professional approach to this challenging assignment.

Filtering Conditions
Daily MP200 = “DPA200”
Daily MP50 = “DPA50”
Daily RSI >60
Daily RSI < 85
Month RSI > 40
Weekly RSI > 40
Hourly MP50 = HPA50
Hourly MCo = “HBUCO”
Daily PDEMA20 > -2
Daily PDEMA20 < 2



