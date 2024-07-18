# Piotroski-Score
This project is about how to compute the Piotroski Score using the Python to find value stocks.

![a](/images/fscore.png)


The Piotroski Score is a financial scoring system used to evaluate the financial strength of a company based on its financial statements. It was developed by Joseph Piotroski, an accounting professor at Stanford University. The score ranges from 0 to 9, with higher scores indicating a stronger financial position and potential for higher returns.

The Piotroski Score is based on nine criteria, grouped into three main categories: profitability, leverage/liquidity, and operating efficiency. Here are the nine criteria:

**Profitability:**
1) Net Income: Positive net income (1 point if positive, 0 if negative).
2) Operating Cash Flow: Positive cash flow from operations (1 point if positive, 0 if negative).
3) Return on Assets (ROA): Positive return on assets in the current year (1 point if positive, 0 if negative).
4) Quality of Earnings: Operating cash flow exceeds net income (1 point if true, 0 if false).

**Leverage, Liquidity, and Source of Funds:**

5) Decrease in Leverage: Lower ratio of long-term debt to total assets compared to the previous year (1 point if lower, 0 if higher or same).
6) Increase in Liquidity: Higher current ratio (current assets divided by current liabilities) compared to the previous year (1 point if higher, 0 if lower or same).
7) Absence of Dilution: No issuance of new shares in the past year (1 point if no new shares issued, 0 if new shares issued).

**Operating Efficiency:**

8) Gross Margin: Higher gross margin compared to the previous year (1 point if higher, 0 if lower or same).
9) Asset Turnover: Higher asset turnover ratio (revenue divided by total assets) compared to the previous year (1 point if higher, 0 if lower or same).

Investors can use the Piotroski Score to identify potentially undervalued stocks with strong financial positions. The Piotroski Score is particularly useful for value investors looking for strong fundamentals in companies that may be overlooked by the market. It can also help in reducing the risk of investing in financially weak companies.

### Additional Resources

* [Related Article by Joseph D. Piotroski](https://www.ivey.uwo.ca/media/3775523/value_investing_the_use_of_historical_financial_statement_information.pdf)

* [Investopedia](https://www.investopedia.com/terms/p/piotroski-score.asp#:~:text=The%20Piotroski%20score%20is%20a,and%20zero%20being%20the%20worst.)

* [Financial Wisdom - Youtube](https://www.youtube.com/watch?v=F33A6XZkdDA&t=17s)

### Environment


```BASH
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

### Disclaimer

The information provided here is for educational purposes only and does not constitute financial or investment advice. Always consult with a qualified financial advisor or conduct your own thorough research before making any investment. Past performance is not indicative of future results, and all investments carry risks, including the loss of principal.