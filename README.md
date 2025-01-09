# Algorithmic Trading Analysis of S&P 500

This repository contains an algorithmic trading notebook designed to analyze companies listed in the S&P 500 index. The purpose of this analysis is to provide insights into business performance and market conditions.

## Overview

The trading system focuses on two main areas:

1. **Business Metrics Analysis**:

   - The system evaluates key financial metrics to assess the health and valuation of companies. Key metrics analyzed include:

     - **Price to Book (P/B)**
     - **Debt to Equity (D/E)**
     - **EBITDA Margin**
     - **Enterprise Value to EBITDA (EV/EBITDA)**
     - **Price to Earnings (P/E)**
     - **Price to Sales (P/S)**
     - **Return on Equity (ROE)**
     - **Revenue per Share**

   - **"Higher is Better" Metrics**: These metrics indicate that a higher value is associated with better financial performance or greater efficiency. For example, a higher EBITDA Margin suggests a company is effectively managing its operating expenses relative to its revenue.

   - **"Lower is Better" Metrics**: These metrics indicate that a lower value is preferable, suggesting better valuation or reduced risk. For instance, a lower Debt to Equity ratio indicates that a company is less reliant on borrowed funds, which typically suggests lower financial risk.

2. **Price Momentum Monitoring**:
   - The system tracks price return rates over various periods: 1 year, 6 months, 3 months, and 1 month. By analyzing price momentum, the system assesses the rate at which stock prices are changing over these time frames. This analysis helps identify trends, as sustained upward or downward movements in price can indicate strong market sentiment or potential reversals. By understanding these price movements, investors can make informed decisions about entering or exiting positions, thereby potentially capitalizing on short-term opportunities.

## Methodology

- **Percentile Calculation**:

  - The algorithm computes the percentiles of key metrics to understand how individual companies perform in relation to their peers.

- **Averaging and Ranking**:
  - Using the calculated percentiles, the system computes averages for both "higher is better" and "lower is better" metrics. This information is then used to rank companies, highlighting those that appear undervalued or have strong momentum.

## Getting Started

To run the notebook locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Bokang-ctrl/algo-trading-system.git
   cd algo-trading-system
   ```
