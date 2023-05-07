# brennan-schwartz
Study of Brennan-Schwartz interest rate model. 

Observing the behavior of time-continuous interest rate $r(t)$ in respect to the stochastic differential equation,
$dr(t) = \alpha(\mu-r(t))dt + \sigma r(t)dW(t)$
with 
* $\alpha$, drift speed factor
* $\mu$, long term mean
* $\sigma$, volatility term
* $W(t)$, Brownian motion

This study also presents the following:
* sensitivity analysis of $r(t)$ for the parameters $\mu, \sigma, \alpha$,
* pricing of zero-coupon bonds (ZCB) $P(t, r)$ based off the Brennan-Schwartz interest rate model, and
* numerical method to solve $P(t, r)$. 

