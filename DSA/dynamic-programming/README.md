# Dynamic Programming

## Overview
Dynamic Programming (DP) is an optimization technique that solves complex problems by breaking them down into simpler subproblems and storing their solutions.

## Key Concepts
- Overlapping subproblems
- Optimal substructure
- Memoization (top-down)
- Tabulation (bottom-up)
- State definition
- State transition

## Common DP Patterns
- Linear DP (1D array)
- 2D DP (grid/matrix)
- Knapsack problems
- Subsequence problems
- String matching
- Game theory

## Common Problems

### Easy
- [ ] Climbing Stairs
- [ ] House Robber
- [ ] Best Time to Buy and Sell Stock
- [ ] Maximum Subarray
- [ ] Min Cost Climbing Stairs

### Medium
- [ ] Longest Increasing Subsequence
- [ ] Coin Change
- [ ] Unique Paths
- [ ] Longest Common Subsequence
- [ ] Word Break
- [ ] Decode Ways
- [ ] House Robber II
- [ ] Partition Equal Subset Sum

### Hard
- [ ] Edit Distance
- [ ] Regular Expression Matching
- [ ] Wildcard Matching
- [ ] Longest Valid Parentheses
- [ ] Best Time to Buy and Sell Stock III
- [ ] Burst Balloons

## Approach
1. Define the state: What does dp[i] represent?
2. Find the recurrence relation: How to compute dp[i] from previous states?
3. Initialize base cases
4. Determine the order of computation
5. Extract the final answer

## Tips
- Start with recursive solution, then add memoization
- Convert to bottom-up if needed for better space complexity
- Draw state transition diagrams
- Practice identifying DP problems (optimal solution, overlapping subproblems)
- Consider space optimization (rolling array)
