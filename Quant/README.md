# Quantitative Interview Preparation

## Overview
This section provides comprehensive resources for preparing for quantitative finance and trading interviews. Topics cover probability, statistics, brainteasers, market making, option pricing, and mental math.

## Who This Is For
- Quantitative Trader roles
- Quantitative Researcher positions
- Market Making positions
- Derivatives Trading
- Risk Management roles
- Data Science in Finance

## Getting Started

### Prerequisites
- Strong mathematical foundation (calculus, linear algebra)
- Probability and statistics fundamentals
- Programming skills (Python, C++, or similar)
- Basic finance knowledge

### Recommended Study Order

#### Phase 1: Mathematical Foundation (Weeks 1-3)
1. **[Probability](./probability/)** - Core probability theory and problems
2. **[Statistics](./statistics/)** - Statistical methods and inference
3. **[Mental Math](./mental-math/)** - Quick calculation skills

#### Phase 2: Problem Solving (Weeks 4-5)
4. **[Brainteasers](./brainteasers/)** - Logic puzzles and reasoning
5. **[Math Puzzles](./math-puzzles/)** - Mathematical problem solving

#### Phase 3: Finance Applications (Weeks 6-8)
6. **[Option Pricing](./option-pricing/)** - Derivatives and Greeks
7. **[Market Making](./market-making/)** - Market microstructure and pricing

## Interview Format

### Phone/Video Screen (45-60 minutes)
- Probability and statistics questions
- Mental math calculations
- 1-2 brainteasers
- Basic finance concepts
- Behavioral questions

### On-site Interview (3-5 rounds)
- **Quant Round**: Advanced probability, stochastic calculus
- **Mental Math**: Speed and accuracy under pressure
- **Brainteasers**: Complex puzzles, think out loud
- **Trading/Market Making**: Pricing games, strategy
- **Programming**: Coding challenges, optimize algorithms
- **Behavioral**: Teamwork, decision making under pressure

## Key Topics by Role

### Quantitative Trader
**Focus Areas:**
- Quick mental math
- Market making concepts
- Probability (especially expected value)
- Game theory and optimal strategies
- Market microstructure

**Common Questions:**
- Pricing games (bid-ask spread problems)
- Probability of profit scenarios
- Optimal betting strategies
- Risk-reward calculations
- Market impact and slippage

### Quantitative Researcher
**Focus Areas:**
- Deep probability theory
- Statistical inference
- Option pricing models
- Time series analysis
- Machine learning

**Common Questions:**
- Prove mathematical theorems
- Derive option pricing formulas
- Statistical hypothesis testing
- Design trading strategies
- Risk metrics and portfolio optimization

### Market Maker
**Focus Areas:**
- Inventory management
- Spread pricing
- Order book dynamics
- Adverse selection
- Fast mental math

**Common Questions:**
- Quote bid-ask spreads
- Manage inventory risk
- React to market scenarios
- Calculate expected profit
- Position sizing

## Problem-Solving Framework

### For Probability Questions
1. **Define the sample space** - What are all possible outcomes?
2. **Identify the event** - What are we calculating probability for?
3. **Apply rules** - Use addition/multiplication rules, conditional probability
4. **Check** - Does answer make intuitive sense? Is it between 0 and 1?

### For Brainteasers
1. **Clarify** - Ask questions, state assumptions
2. **Simplify** - Try smaller numbers or special cases
3. **Pattern** - Look for patterns or symmetries
4. **Work backwards** - Sometimes easier from the end
5. **Verify** - Check your answer makes sense

### For Trading/Pricing Questions
1. **Fair value** - What is the expected value?
2. **Edge** - What advantage do you have?
3. **Risk** - What can go wrong?
4. **Strategy** - How to optimize risk-reward?
5. **Execution** - Practical considerations

## Essential Formulas

### Probability
```
P(A or B) = P(A) + P(B) - P(A and B)
P(A and B) = P(A) × P(B|A)
P(A|B) = P(B|A) × P(A) / P(B)  [Bayes' Theorem]
E[X] = Σ x × P(X=x)
Var(X) = E[X²] - (E[X])²
```

### Statistics
```
Sample Mean: x̄ = (Σ xᵢ) / n
Sample Variance: s² = Σ(xᵢ - x̄)² / (n-1)
Standard Error: SE = s / √n
Confidence Interval: x̄ ± z × SE
Correlation: ρ = Cov(X,Y) / (σₓ × σᵧ)
```

### Options (Black-Scholes)
```
Call: C = S₀N(d₁) - Ke^(-rT)N(d₂)
Put: P = Ke^(-rT)N(-d₂) - S₀N(-d₁)
Put-Call Parity: C - P = S₀ - Ke^(-rT)

Greeks:
Delta_call ≈ N(d₁)
Gamma = φ(d₁) / (S₀σ√T)
Vega = S₀φ(d₁)√T
Theta_call = -S₀φ(d₁)σ/(2√T) - rKe^(-rT)N(d₂)
```

### Market Making
```
Expected Profit = P(Fill) × (Spread/2 - Adverse Selection Cost)
Sharpe Ratio = (Return - Risk-free Rate) / Volatility
```

## Mental Math Practice

### Daily Routine (15 minutes)
- 5 min: Multiplication drills (2-digit × 2-digit)
- 5 min: Percentage calculations
- 5 min: Square and square root estimation

### Weekly Goals
- Week 1-2: Basic operations, multiplication tables to 20×20
- Week 3-4: Percentages, fractions, decimals
- Week 5-6: Squares up to 100², square roots, powers
- Week 7-8: Compound calculations, quick approximations

## Common Pitfalls to Avoid

### Probability
- Forgetting to account for all cases
- Confusing independence with mutual exclusivity
- Not considering order when it matters
- Calculation errors in complex problems

### Brainteasers
- Making unstated assumptions
- Giving up too quickly
- Not thinking systematically
- Forgetting edge cases

### Trading Questions
- Ignoring transaction costs
- Not considering risk
- Overlooking adverse selection
- Poor risk-reward analysis

## Interview Tips

### Preparation
- Practice mental math daily
- Do timed problem sets
- Explain solutions out loud
- Review mistakes thoroughly
- Read financial news

### During Interview
- Think out loud - show your reasoning
- Ask clarifying questions
- Start with simple cases
- Check your arithmetic
- Be honest if you don't know
- Stay calm under pressure

### Technical Skills
- Know probability cold
- Be fast with mental math
- Understand basic derivatives
- Familiar with statistical tests
- Comfortable with programming

### Soft Skills
- Communication of technical concepts
- Handling pressure gracefully
- Showing intellectual curiosity
- Team collaboration examples
- Ethical decision making

## Resources

### Books
**Probability & Math:**
- "A Practical Guide to Quantitative Finance Interviews" by Xinfeng Zhou
- "Heard on the Street" by Timothy Crack
- "Fifty Challenging Problems in Probability" by Mosteller

**Options & Finance:**
- "Options, Futures, and Other Derivatives" by John Hull
- "The Concepts and Practice of Mathematical Finance" by Mark Joshi
- "Paul Wilmott on Quantitative Finance"

**Brainteasers:**
- "How Would You Move Mount Fuji?" by William Poundstone
- "Are You Smart Enough to Work at Google?" by William Poundstone

### Online Resources
- QuantNet Forums
- Wilmott Forums
- Street Of Walls
- Quantopian (algorithmic trading)

### Practice Platforms
- Brilliant.org (math and probability)
- Project Euler (mathematical problems)
- Khan Academy (fundamentals)

## Progress Tracking

Track your progress through each section:
- Complete all fundamental problems
- Time yourself on mental math
- Practice explaining solutions
- Do mock interviews
- Review and retry difficult problems

## Next Steps

After completing this preparation:
1. Review fundamental concepts regularly
2. Do mock interviews with peers
3. Read recent quant interview experiences
4. Stay updated on market developments
5. Practice under timed conditions
6. Build a portfolio of projects

Remember: Consistency is key. Daily practice, even if just 30 minutes, is better than cramming.

Good luck with your interviews! 📈
