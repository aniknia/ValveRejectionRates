# Prediction of Valve Rejection Rates
## Introduction

This project is a Julia-based analysis developed in a Jupyter Notebook that predicts valve rejection rates across different vendors and service mediums. The model leverages a Bayesian multilevel approach and employs the NUTS sampler (a type of Markov Chain Monte Carlo (MCMC) algorithm) to estimate the probability of valve failure. By accounting for vendor-specific variations and medium-specific characteristics (such as steam, air, liquid, and their combinations), the program provides a nuanced understanding of failure rates under varying operating conditions.

The code is structured to preprocess the valve data by service medium, construct hierarchical models for each medium, and generate predictive distributions and density plots. These visualizations help in comparing the estimated probabilities of failure across different vendors and mediums, offering valuable insights for quality control and process improvement.

<h1 align="center"><img src="Project Instructions and Deliverables/probability of failure.png" alt="Probability of Failure" height="100px"></h1>