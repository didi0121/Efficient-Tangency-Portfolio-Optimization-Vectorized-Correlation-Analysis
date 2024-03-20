# Efficient Tangency Portfolio Optimization: Vectorized Correlation Analysis

## Introduction

In this Python project, we further explore mean-variance portfolio optimization, a cornerstone concept in investment theory. 
Our focus is on understanding the impact of correlation between two assets on the tangency portfolio. 
To enhance efficiency by vectorizing the code, we compute tangency portfolio weights for a range of correlations, facilitating a comprehensive analysis of the efficient frontier and Capital Market Line (CML). 
By merging theory with practical implementation, this project provides valuable insights for portfolio management and investment decision-making.

In this example we will construct an efficient frontier of portfolios of two risky assets -- stocks of Intel and National Instruments.

## Logistics

Part A: Define Variables

We establish the foundational variables required for our analysis: expected returns and volatilities for Intel and National Instruments, a range of weights for Intel, and a spectrum of correlations between the two assets. These variables serve as the basis for subsequent calculations.

Part B: Calculate Tangency Portfolio Weights

Through vectorized operations and efficient broadcasting techniques, we compute the tangency portfolio weights for a diverse range of correlations. This involves determining the returns and volatilities of portfolios, calculating slopes for Capital Allocation Lines (CALs), approximating the slope of the efficient frontier, and ultimately identifying the optimal portfolio weights for each correlation.

Part C: Plot the Tangency Portfolio Weights

Utilizing the computed tangency portfolio weights, we visualize the relationship between correlation and portfolio allocation. By plotting correlation against weights for Intel and National Instruments, we gain insights into how changes in correlation affect the distribution of portfolio weights. Additionally, we consider the implications of short-selling on portfolio optimization and discuss potential adjustments to the analysis to accommodate this factor.
