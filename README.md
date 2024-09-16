# Stochastic Volatility Models

This repository contains Python implementations of various stochastic volatility models for financial time series analysis. These models are designed to capture the randomness in volatility observed in asset prices over time, and are widely used in quantitative finance, risk management, and option pricing.

## Table of Contents

[Overview](#Overview)   
[Distributions](#Distributions)  
[To-Do](#To-Do)  


## Overview


## Models Implemented

The following stochastic volatility models are currently available in this repository:

- **Merton Jump Diffusion:** This model states that the underlying assets have occasional large discontinuous jumps in price while still following the geometric brownian motion. This is achieved through a compound poisson process. The discontinous jumps change the overall implied volatility of the model.

- **Continous-Time Markov Chains:**

- **Heston Model:** In this model the volatility has its own stochastic differential equation, creating a smoother yet still random transition between times of high volatility an low volatility. An important characteristic of this model is tha t



## Distributions
The distributions of each model are also investigated to ensure that that the stochastic models are performing as expected.

## To-Do

- Calculate the terminal times of stock paths of the models to decrease the computation time of the implied volatility.
- Apply the models to real-world data.
- Combine multiple models together and determine its effectiveness.
