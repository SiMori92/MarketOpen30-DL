# Market Open 30mins Algo - Deep Learning

# Assumption
    1. H1: probabilities of either (1) 30-minutes return is positive or (2) high - open price > [1.5] %  > 60%
    2. H1: Assumption on (1) T-1 return and volume and (2) pre-market performance correlated to assumption 1 probabilities 

# Strategy rules
    1. assume each day start with 0 position
    2. assume close all positions every day at 10:00
    3. a must, net position cannot below 0
    4. Signal at market open: Buy or Not buy

# Modeling
    Optimisation
        1. probabilities
        2. return

# Customisable parameters (giving different results depends on choices)
    1. Invest horizon (period for optimise return) - show the expected return for each horizon
    2. market sentiment

# Back-test
    1. Probability distribution of assumption 1
    2. validation and testing on model trained based on assumtpion 2

# Documents
    1. Data Scehema - https://docs.google.com/spreadsheets/d/1VVRJ0_q_iqt4BhN5bDrgCl6_kCcSziLifmmPGbSlApc/edit?gid=1828399017#gid=1828399017
    2. 
