Monte Carlo Option Pricing & Quantitative Analysis

A three-stage quantitative finance project exploring Monte Carlo simulation, European option pricing, statistical accuracy, risk sensitivities and automated financial market data integration using Python.

Project Overview

This project was developed in three stages, progressing from understanding the mathematical foundations of Monte Carlo simulation to implementing option pricing models and integrating live financial market data.

Project 1 – Understanding Monte Carlo Simulation

The first stage focused on understanding the mathematical foundations of Monte Carlo simulation and its application to financial modelling.

Key concepts explored:

Random variable generation and probability distributions.

Simulating possible future stock prices.

Understanding expected payoffs.

Discounting future payoffs to present value.

Using simulations to estimate option prices.

Project 2 – Monte Carlo Option Pricing Model

File: 02_Monte_Carlo_Project_Model.ipynb

Developed a Python-based model to price European Call and Put options using Geometric Brownian Motion (GBM).

Key implementations:

GBM-based terminal stock price simulation.

European Call and Put payoff calculations.

Monte Carlo option pricing.

Black–Scholes analytical pricing for comparison.

Standard Error and 95% Confidence Intervals.

Option Greeks: Delta, Gamma, Vega, Theta and Rho.

Simulated stock-price paths and payoff distributions.

Monte Carlo convergence visualisation.

Antithetic Variates for variance reduction.

The model explores the relationship between simulation accuracy, the number of simulations and analytical pricing benchmarks.

Project 3 – Live Monte Carlo Option Pricing

File: 03_Live_Monte_Carlo_Yahoo_Finance.py

Extended the pricing model by integrating Yahoo Finance market data through the yfinance Python library.

The model automatically refreshes its calculations at 60-second intervals using the latest available market data.

Key implementations:

Automated stock-price retrieval from Yahoo Finance.

Historical volatility estimation using daily log returns.

Live-input Monte Carlo Call and Put pricing.

Black–Scholes pricing comparison.

Numerical estimation of Option Greeks.

Standard Error and 95% Confidence Intervals.

Antithetic Variates and variance reduction.

Automated visualisation of simulated stock paths, payoff distributions and convergence.

Technologies Used

Python

NumPy

Pandas

SciPy

Matplotlib

yfinance

Jupyter Notebook
