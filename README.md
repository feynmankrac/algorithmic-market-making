## Overview
This project analyzes the behavior of leveraged ETFs (SPXL / SPXS) and proposes a replication framework based on realized variance dynamics.

## Objective
- Understand the sources of tracking error in leveraged ETFs
- Model the impact of volatility drag
- Compare replicated strategies with market ETFs

## Methodology
- Variance-based analysis of leveraged ETF dynamics
- Internal replication of leveraged exposure
- Analysis of path dependency through return compounding effects
- Performance and risk comparison against SPXL / SPXS

## Key Insights
- Leveraged ETF performance strongly depends on the path of returns, not only on cumulative returns.
- Volatility drag significantly erodes performance in high variance regimes, even when the underlying trend is favorable.
- Simple variance-based replication captures part of the dynamics but fails to fully reproduce real ETF behavior due to rebalancing effects and transaction costs.
- Tracking error increases during volatile periods, highlighting the limitations of static replication approaches.

## Implementation
- Python
- Time series analysis
- Backtesting framework

## Results
- Tracking error analysis
- Volatility drag effects
- Performance comparison with benchmark ETFs

## Files
- `Projet_ATFM_final.ipynb`: implementation and simulations
