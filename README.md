# TradeWise

## Overview

TradeWise is a powerful options calculator designed to help investors gain a deep understanding of options and make informed decisions when trading them. This versatile calculator incorporates both the Black-Scholes Model and the Binomial Model for option pricing, catering to the needs of traders with varying preferences and strategies.

## Why Use TradeWise?

Options can be complex financial instruments, and trading them without a thorough understanding can lead to significant losses. TradeWise aims to bridge the knowledge gap by providing valuable insights into option pricing and strategies. Whether you are an experienced trader or just starting, TradeWise can be your guide to success in the options market.

## Key Features

### 1. Black-Scholes Model

TradeWise utilizes the Black-Scholes Model, a cornerstone of options pricing, to offer:

- Call and put option pricing
- Calculation of d1 and d2 values
- Analysis of Greek letters (delta, gamma, vega, rho, and theta)

The Black-Scholes Model operates under certain assumptions:

- European-style options
- No dividends during the option's life
- Efficient stock markets with continuous trading
- No transaction or commission costs
- Known and constant risk-free rate and volatility
- Returns on the underlying asset follow a normal distribution

#### Input Variables:

- Underlying price (per share)
- Strike price of the option (per share)
- Time to maturity (years)
- Continuously compounding risk-free interest rate (%)
- Volatility (%)

#### Output Variables:

- d1 and d2 values
- Greek letters: delta, gamma, vega, rho, and theta

### 2. Binomial Model

TradeWise also incorporates the Binomial Model, known for its simplicity, offering two distinct binomial-tree methods: Cox-Ross-Rubinstein and Jarrow-Rudd (the equal-probability model). These methods can be used for pricing various types of options and follow a similar three-step process. Assumptions for the Binomial Model include:

- Two possible prices for the underlying asset on the next day (up and down)
- No dividends during the option's life
- Constant risk-free rate throughout the option's life
- No transaction or commission costs
- Investors are risk-neutral

#### Key Parameters:

All trees in the Binomial Model are built from four essential parameters: u, d, p, and q.

- u and d represent the magnitude of price changes in each time step.
- p and q are the probabilities of price going up and down, with p + q equal to 1.

Note: The model assumes that the underlying asset's price follows a random walk.

## Python Resources

To facilitate the calculations and enhance the user experience, TradeWise leverages several Python libraries:

- Pandas: For data analysis and manipulation
- Numpy: Supporting multi-dimensional arrays and matrices
- Math: Providing access to essential mathematical functions
- Statistics: Offering statistical functions
- matplotlib.pyplot: Enabling data visualization
- datetime: Managing date and time-related operations

## Get Started

Gain a deeper understanding of options and enhance your trading strategies with TradeWise. Whether you prefer the precision of the Black-Scholes Model or the simplicity of the Binomial Model, TradeWise has you covered. Make informed decisions and maximize your potential in the options market.