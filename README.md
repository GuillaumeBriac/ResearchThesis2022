# Research Thesis – 2022

## Calibration of Stochastic Volatility Models

This thesis is written in order to present different stochastic volatility models, to understand properly how each parameter impacts the output price and finally to calibrate those models on real market data (S&P500 options). The idea is to see which model has the best fit over time, making the calibration on different historical datasets and see how they all perform.

The models under review are the Heston model, the SABR model and the SVI model. The optimization of the parameters is done by minimizing the squared errors between prices given by the models and historical market data. The Sequential Quadratic Programming (SQP) algorithm is used to fit the curves. The Particle Swarm Optimization (PSO) algorithm was tested as well to try to fit more accurately the market prices.

Keywords: Heston model, SABR model, SVI model, Stochastic volatility, Option Pricing
