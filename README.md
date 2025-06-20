# Pre-market Singaling Model - Deep Learning

# Assumnption
H1: Assumption on pre-market performance correlated to open market 30-minute volatility AND open market 30-minute performance show patterns

# Modeling
Learn the pattern on the Input variables to output trading signals

# Strategy rules
    1. 7 signals generated per trading day - any legal risk? providing brokerage opinion ?
    2. split your bets in 10 equal bets
    3. assume execute all trade signals every day 
    4. assume close all positions everyday
    5. optimise the return over [period]

# customisable parameters (giving different results depends on choices)
    1. Invest horizon (period for optimise return) - show the expected return for each horizon
    2. market sentiment

# Back-test
    1. Probability distribution for each optimisation period
    2. whether model failed to predict under certain period?
