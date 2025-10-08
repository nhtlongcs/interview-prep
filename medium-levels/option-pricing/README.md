# Option Pricing

## Overview
Options are derivatives that give the right (but not obligation) to buy or sell an asset. Understanding option pricing and Greeks is fundamental for quantitative finance.

## Key Concepts

### Option Basics
- [ ] Call vs Put options
- [ ] European vs American options
- [ ] Strike price and expiration
- [ ] Intrinsic value vs Time value
- [ ] Moneyness (ITM, ATM, OTM)

### Pricing Models
- [ ] Black-Scholes-Merton model
- [ ] Binomial tree model
- [ ] Monte Carlo simulation
- [ ] Put-Call parity

### The Greeks
- [ ] Delta (Δ): Price sensitivity
- [ ] Gamma (Γ): Delta sensitivity
- [ ] Theta (Θ): Time decay
- [ ] Vega (ν): Volatility sensitivity
- [ ] Rho (ρ): Interest rate sensitivity

### Volatility
- [ ] Historical volatility
- [ ] Implied volatility
- [ ] Volatility smile/skew
- [ ] VIX index

## Black-Scholes Formula

### Call Option
```
C = S₀N(d₁) - Ke^(-rT)N(d₂)

d₁ = [ln(S₀/K) + (r + σ²/2)T] / (σ√T)
d₂ = d₁ - σ√T
```

### Put Option
```
P = Ke^(-rT)N(-d₂) - S₀N(-d₁)
```

Where:
- S₀ = Current stock price
- K = Strike price
- r = Risk-free rate
- T = Time to expiration
- σ = Volatility
- N(x) = Cumulative normal distribution

## Common Interview Questions

### Conceptual
1. Explain put-call parity
2. Why can't American options be worth less than European?
3. What is implied volatility?
4. Explain the volatility smile

### Greeks
1. What does delta represent?
2. Why is gamma highest for ATM options?
3. How does theta behave as expiration approaches?
4. What happens to vega near expiration?

### Practical
1. How would you hedge a long call position?
2. Price an ATM call option with given parameters
3. What happens to option value if volatility doubles?
4. Construct a risk-free portfolio using options

## Example Problems

### Easy
1. **Intrinsic Value**: Stock at $105, call strike $100. Intrinsic value?
2. **Moneyness**: Stock at $50, put strike $55. ITM, ATM, or OTM?
3. **Put-Call Parity**: Verify parity for given prices

### Medium
1. **Delta Hedging**: You're long 100 calls with delta 0.6. How many shares to hedge?
2. **Black-Scholes**: Calculate call price with S=$100, K=$100, r=5%, T=1yr, σ=20%
3. **Greeks**: How does delta change from ATM to deep ITM?

### Hard
1. **Volatility Trading**: Construct delta-neutral position to profit from volatility
2. **American Options**: Why might you exercise American call early? (dividends)
3. **Implied Vol**: Given option price, find implied volatility (iterative)

## Option Strategies

### Single Options
- Long Call/Put
- Short Call/Put
- Covered Call

### Spreads
- Bull/Bear Spread
- Butterfly Spread
- Calendar Spread

### Combinations
- Straddle
- Strangle
- Iron Condor

### Greeks Management
- Delta-neutral
- Gamma-scalping
- Vega-neutral

## Advanced Topics

### Exotic Options
- Asian options
- Barrier options
- Lookback options
- Digital/Binary options

### Numerical Methods
- Finite difference methods
- Binomial/Trinomial trees
- Monte Carlo simulation
- Greeks calculation

## Tips for Interviews
- Know Black-Scholes assumptions and limitations
- Understand Greeks intuitively, not just formulas
- Practice mental approximations
- Be able to explain to non-technical audience
- Understand relationship between Greeks
- Know when models break down (extreme events)
- Be prepared for numerical examples
