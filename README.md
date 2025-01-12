# **Long-Short Strategy  on European Stocks**

## **Project Overview**
This project aims to replicate a Long/Short  Strategy on European stocks, as described in the provided data and methodology. The strategy combines two well-known factors - momentum score and value score — to select stocks for long and short positions in the European equity market.

The strategy is rebalanced monthly and utilizes historical return and Price-to-Book (P/B) ratios for stock selection.

---

## **Methodology**
The project follows a three-step approach to implement the strategy:

### 1. Stock Scoring
- **Momentum Score**: Calculated as the centered standard deviation of the average monthly returns over the past 12 months, excluding the most recent month.
- **Value Score**: Calculated as the centered standard deviation of the Price-to-Book (P/B) ratio, measured at the end of the previous month.
- **Global Score**: Each stock's global score is the arithmetic mean of its momentum and value scores.

### 2. Portfolio Formation
- **Long Portfolio**: Composed of the top 15 stocks with the highest global scores.
- **Short Portfolio**: Composed of the bottom 15 stocks with the lowest global scores.

### 3. Portfolio Construction
Both the long and short portfolios are weighted proportionally to the absolute values of their respective global scores. The strategy invests 100% in both the long and short portfolios.

---

## **Results**
- By investing €100,000 in the strategy in March 2008, the investment would grow to approximately €270,500 by March 2023, resulting in a profit of €170,500.
- The annualized return (CAGR) for an investment starting at €100,000 and growing to €270,000 over 25 years is approximately 4.89% per year. This means that, on average, the capital grew by this percentage annually over the 25-year period.
- The performance of the strategy is compared with the benchmark (e.g., CAC 40, S&P 500).
- The strategy outperforms the CAC 40 index over the 25 years, as demonstrated by the capital evolution graph.

---

## **License**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## **Files Included**
1.  The data for this strategy comes from the '**DATA.xlsx**' file, which contains:
- Monthly returns for European stocks.
- Price-to-Book ratios for each stock.
- Monthly returns for the benchmark.
  
---

## **Contact**
For any questions or feedback, feel free to reach out to me via email or LinkedIn:
- **Email**: [ahmed.mili@edu.devinci.fr](mailto:ahmed.mili@edu.devinci.fr)
- **LinkedIn**: [Ahmed Mili](https://www.linkedin.com/in/ahmedmili/)
- **GitHub**: [Ahmed Mili's GitHub](https://github.com/AhmedMIL)
