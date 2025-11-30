# Bio-Nomial Tree
---

**Binomial trees** are frequently used for the purpose of pricing Options by modelling price paths of the underlying assets. The underlying asset parameters frequently take the form of the initial stock price, risk-free interest rates (under the risk-neutral valuation assumption), asset volatility, dividend yield (when applicable), etc. 

Of particular interest to us are the risk-free interest rates (which is denoted by $r$) and the volatility (which is denoted by $sigma$). In traditional binomial trees, these two parameters are kept constant throughout the time interval (from time $t = 0$ until the time the option expires/reaches maturity). We want to modify this scheme by considering these parameters to be time-varying parameters, i.e., $r = r(t)$ and $\sigma = \sigma(t)$. To that end, we turn to the modelling of epidemics in mathematical biology.

It is well known that disease outbreaks can lead to economic downturns, hence significantly impacting the stock market. The purpose of this project is to incorporate the use of **SIR** (Susceptible-Infectious-Recovered) models from mathematical biology/epidemiology for the purpose of modelling the change in interest rates and volatility over the course of the outbreak of a viral disease. 

Since we are incorporating these biologically-inspired mathematical models for the purpose of option pricing, we hence refer to this model as the **BIO-NOMIAL TREE** model.

---

## References

> Hull, J. C. (1997). *Options, futures. and Other Derivative Securities*.

> Weiss, H. H. (2013). *The SIR model and the foundations of public health. Materials matematics, 0001-17*.