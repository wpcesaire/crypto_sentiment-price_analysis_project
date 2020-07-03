# fintech-project-2
A repository for Columbia University FinTech Project 2

Our project is to determine the relationship between discourse of Bitcoin in mainstream news media and  Bitcoin price. Based upon this relationship we intend to create an algorithm that uses this signal to trade Bitcoin on price volatility.

## Layered Approach
1. The first step is to gather data of news articles that mention Bitcoin. Once articles are gathered we will use *keyword analysis* to determine whether there is a correlation between number of mentions of Bitcoin in news media and Bitcoin closing price.
2. Once we determine the number of mentions of Bitcoin we will use *sentiment analysis* to determine whether the statements made about Bitcoin were positive, negative or neutral and adjust our judgements based on the analysis.
3. Create a classification report/confusion matrix based on Bitcoin price data.
4. Based on the rate of creation of new Bitcoin wallets we will establish an adoption rate of Bitcoin. (Adoption rate = number of wallets created vs number of wallets already existing compared to population size).
5. Once an adoption rate is established we will make a judgement as to whether Bitcoin is a long term asset class or an opportunity to profit off of volatility.
6. Solve for rate of adoption needed for world-wide adoption based on amount of years it would take to mine all Bitcoins.
7. Determine whether world-wide adoption of Bitcoin by the date all Bitcoins are mined is feasible based on current adoption rate.

## Sources
1. News API
2. Reuters 
3. WebHose.io
4. New York Times API