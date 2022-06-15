# Portfolio analysis.
## looking at the whales!
![This is a alt text.]("Code/Resouces/pics/whales.jpg")

For this project, we decided to analyze the risk and return of some of the whales of Wallstreet.
We analyze the following portfolios SP-500, Soros Fund Management LLC, Paulson & Co.INC, Tiger Global Management LLC and Berkshire Hataway INC.
We also added the data from two algobots.

We start with the initial imports
![This is a alt text.]("Code/Resources/pics/imports.jpg")


All the data analyzed is from 2015 to 2019, we will update the data when we find a new source.
We started by conducting a Quantitative analysis, looking at the 5-year risk(The Standard Deviation) and the cumulative annualized return data for each portfolio.


__________________________________________
SP-500:

Risk (std): 15.73

Return: 13.51

________________________________________
Soros Fund Management LLC:

Risk (std): 27.79

Return: 33.42
________________________________________
Paulson & Co.INC:

Risk (std): 20.37

Return: 28.57
________________________________________
Tiger Global Management LLC:

Risk (std): 25.56

Return: 37.13
_______________________________________
Berkshire Hataway INC:

Risk (std): 19.87

Return: 20.67
_________________________________________
Algobot 1:

Risk (std): 2.77

Return: 4.31
_______________________________________
Algobot 2:

Risk (std): 0.93

Return: 1.96
________________________________________


From this data, we can see that the Soros Fund Management LLC has the highest risk and return, while the Algobot 2 has the lowest risk and return.
![This is a alt text.]("Code/Resouces/pics/risk_annualized_std")

Next, we decided to look at the rolling 21 days risk and return for each portfolio.
We wanted to look at the correlation between the portfolios and adding a correlation map of this data when we clearly see that the lowest correlation happens between sp_500 and Berkshire.
![This is a alt text.]("Code/Resouces/pics/sharp_ratios")

Sharpe Ratios
In reality, investment managers and their institutional investors look at the ratio of return-to-risk, and not just returns alone. After all, if you could invest in one of two portfolios, and each offered the same 10% return, yet one offered lower risk, you'd take that one, right?
Using the daily returns, calculate and visualize the Sharpe ratios using a bar plot


lastly, An alternative way to calculate a rolling window is to take the exponentially weighted moving average. This is like a moving window average, but it assigns greater importance to more recent observations. Try calculating the EWM with a 21-day half-life.
