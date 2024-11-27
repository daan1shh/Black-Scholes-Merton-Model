# Black-Scholes-Merton-Model
Daanish Muzaffar
This project explores the Black-Scholes Model (BSM) for option pricing, a cornerstone of modern quantitative finance. This project uses Yahoo finance to fetch real-time data for user defined stocks, strike prices and expiration dates. In addition to pricing American and European-style options, the project delves into:

1.   Using Black Scholes Merton model to calculate theoretical prices of both call and put options
2.   Finding the percentage error between theoretical and actual market prices for option derivatives.
3.   Performing stress test on Black Scholes Model to study variation in option price due to each variable in extreme market conditions
4.   Calculation and analysis of option Greeks—key sensitivity measures that quantify the risk and responsiveness of an option's price to market variables.
5.   Plotting option prices as a function of greeks to prresent real-time data and as a function of probable range of volatility to predict option price movement.

By combining financial theory with Python-based numerical techniques, this project provides both a conceptual understanding and a hands-on implementation of the BSM and Greeks. The code is modular, with functions designed to compute individual components of the BSM formula and Greeks, making it easy to understand and adapt for various use cases.

## Installation
Use local Jupyter notebook for best experience
Clone the repository:
```bash
https://github.com/daan1shh/Black-Scholes-Merton-Model.git
```
following external libraries are required for the project to be operational. Kindly install via console:
```bash
pip install yfinance
pip install numpy
pip install scipy
```

This model requires three inputs from the user:
1.  Stock symbol
2.  Expiration date
3.  Strike price

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

