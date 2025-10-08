# Market Making

## Overview
Market making involves providing liquidity by quoting both bid and ask prices. Understanding market microstructure is crucial for trading roles.

## Key Concepts

### Basics
- [ ] Bid-ask spread
- [ ] Order book dynamics
- [ ] Inventory management
- [ ] Adverse selection
- [ ] Market impact

### Pricing
- [ ] Fair value estimation
- [ ] Spread determination
- [ ] Edge and adverse selection
- [ ] Tick size and price increments

### Risk Management
- [ ] Inventory risk
- [ ] Position limits
- [ ] Hedging strategies
- [ ] Risk-reward tradeoffs

### Market Microstructure
- [ ] Order types (market, limit, stop)
- [ ] Time priority
- [ ] Hidden liquidity
- [ ] Latency and speed

## Common Interview Questions

### Conceptual
1. What is the bid-ask spread and why does it exist?
2. Explain adverse selection in market making
3. How would you price a market making spread?
4. What factors affect the profitability of market making?

### Quantitative
1. Given inventory limits, how wide should your spread be?
2. Calculate expected profit per trade with given parameters
3. Optimal quote placement with inventory constraints
4. Risk of being adversely selected

### Scenario-Based
1. Your inventory is at limit. What do you do?
2. You notice sudden volume increase. Adjust strategy?
3. Competitor narrows spread. Your response?
4. News event expected. How to manage risk?

## Example Problems

### Easy
1. **Basic Spread**: Fair value is $100. What bid/ask would you quote with $0.10 edge?
2. **P&L Calculation**: Bought 100 at $50, sold 100 at $51. Calculate profit.
3. **Fill Probability**: Higher spread means what for fill probability?

### Medium
1. **Inventory Management**: Currently long 500 shares (limit 1000). How to adjust quotes?
2. **Edge Calculation**: Win rate 52%, average profit $1, average loss $1. Expected profit?
3. **Volume Analysis**: How does volume affect optimal spread?

### Hard
1. **Optimal Spread**: Given fill rate function and adverse selection, find optimal spread
2. **Multi-asset**: Market make 2 correlated assets. Hedging strategy?
3. **Dynamic Pricing**: Adjust quotes based on inventory and volatility

## Key Formulas

### Profit and Loss
```
P&L = (Sell Price - Buy Price) × Quantity - Transaction Costs
```

### Expected Profit
```
E[Profit] = P(Fill) × (Spread/2 - Adverse Selection Cost)
```

### Inventory-adjusted Spread
```
Adjusted Spread = Base Spread + Inventory Risk Premium
```

### Fill Probability (simplified)
```
P(Fill) decreases as Spread increases
Often modeled as: P(Fill) = e^(-k × Spread)
```

## Practical Considerations

### Technology
- Low latency systems
- Co-location
- Smart order routing
- Real-time risk management

### Regulations
- Market maker obligations
- Quote requirements
- Position reporting
- Best execution

### Competition
- HFT firms
- Algorithmic trading
- Price improvement
- Rebate structures

## Tips for Interviews
- Understand trade-offs (spread vs fill rate)
- Consider inventory effects
- Think about adverse selection
- Know market microstructure basics
- Be prepared for mental math
- Discuss risk management proactively
