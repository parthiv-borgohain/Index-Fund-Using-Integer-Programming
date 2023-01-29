# Index Fund Using Integer Programming
Project as part of Optimization-I coursework in UT Austin's MS Business Analytics Program.

## Introduction:

Equity money management strategies are largely classified as either 'active' or 'passive'. The most common passive strategy is that of "indexing" where the goal is to choose a portfolio that mirrors the movements of the broad market population or a market index. Such a portfolio is called an index fund. For example, the QQQ Index fund tracks the NASDAQ-100 index.

## Problem Statement:

Constructing an index fund that tracks a specific broad market index could be done by simply purchasing all n stocks in the index, with the same weights as in the index. However, this approach is impractical (many small positions) and expensive (rebalancing costs may frequently be incurred, price response to trading). An index fund with m stocks, where m is substantially smaller than the size of the target population, n, seems desirable.

Approach:

1. Formulate an integer program that picks exactly m out of n stocks for our portfolio. This integer program will take as input a 'similarity matrix', which we will call 𝜀. The individual elements of this matrix, 𝜀(i,j), represent similarity between stock i and j. An example of this is the correlation between the returns of stocks i and j. But one could choose other similarity metrics 𝜀(i,j).

2. Solve a linear program to decide how many of each chosen stock to buy for your portfolio.

3. Evaluate how well your index fund does as compared to the NASDAQ-100 index, out of sample. Examine the performance for several values of m.

Conclusion:

In this project, we created an Index fund with m stocks to track the NASDAQ-100 index. We used an integer program to pick exactly m out of n stocks for our portfolio and then tried an alternate strategy of formulating a linear program to decide how many of each chosen stock to buy for our portfolio. We also evaluated the performance of the index fund for several values of m and compared it to the NASDAQ-100 index.

#### Note ####

All codes, reports and findings are available in this repository
