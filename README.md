# Risk-Return-Analysis
## Module 4

### Packages Used

1. Pandas
2. NumPy
3. Matplotlib

### Datasets Used

1 dataset was used, an aggregate of the NAV prices of four portfolios and on the closing price of the S&P 500 Index.

**4 Portfolios**:
1. Soros Fund Management LLC
2. Paulson & Co. Inc
3. Tiger Global Management LLC
4. Berkshire Hathaway Inc

**Dataset Name**: whale_navs.csv

**Dataset Beginning and End Date**: October 1, 2014 - September 11, 2020

### Objective

The objective of this challenge was to evaluate four new investment options.

### Purpose

The purpose of this challenge was to determine the fund with the most investment potential based on key risk-management metrics: the daily returns, standard deviations, Sharpe ratios, and betas.

### General Findings

None of the four portfolios outperform the S&P 500 index.

<img src='Cumulative_Retuns_4_Funds_Plus_SP500.png' width='100' >

The most volatile of the four fund portfolios is Berkshire Hathaway. The least volatile is Tiger Global Management.

[insert image]

Based on the rolling metrics, to an extent, the risk of each portfolio increases at same time that the risk of the S&P 500. This does not always hold true, as we see the risk of the S&P 500 spikes spiratically while the 4 portfolios tend to stay more contstant. The biggest exception to this is in 2020, where there was the greatest increase in risk across the 4 funds and the S&P 500.

Initially, Soros Fund Management posed as the most risk. However, that changed in the middle fo 2016, where Berkshire Hathaway posed the most risk until the end of the dataset (September 11, 2020).

[insert image/s]

Berkshire Hathaway offers the best risk-return profile. Paulson & Co offers the worst risk-return profile.

[insert image]

Berkshire Hathaway is more sensitive to movements in the S&P 500 than Tiger Global Management.

I recommend Tiger Global Management for inclusion in my firm's suite of fund offerings because its rolling beta is closer to 0, meaning that regardless of the movement of the S&P 500, the portfolio's value will likely not change. It is a less risky portfolio than Berkshire Hathaway.

[insert custom overlayd chart image]
