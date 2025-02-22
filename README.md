# MSc_Thesis
This repository contains multiple Jupyter notebooks that hold the code for a master thesis in data science in which we investigate if reinforcement learning algorithm can beat benchmark approaches when contructing an investment portfolio. The benchmarks to beat are: 
First a portfolio of equities, Gold and a money market account constructed using Modern Portfolio Theory (i.e., following Markovitz).
Second a portfolio based on the former which uses Thompson Sampling to incorporate newly incoming price data.

The reinforcement learning algorithm applies q-learning using a deep neural network to estimate with target network and experience reply to learn from four context variables: non-farm payroll, CPI, price of oil and unemplyoment rate. The RL+ algorithm as able to beat the two benchmark portfolios on a test data set by roughly 1% in absolute terms.

The repository contains the most important lines of code grouped by topics in addition the main figures shown in thesis.
