# Greedy Algorithms

## Overview
Greedy algorithms make locally optimal choices at each step hoping to find a global optimum. Key is proving that local choices lead to global solution.

## Key Concepts
- Greedy choice property
- Optimal substructure
- Activity selection
- Interval scheduling
- Huffman coding

## Common Problems

### Easy
- [ ] Assign Cookies
- [ ] Lemonade Change
- [ ] Best Time to Buy and Sell Stock II
- [ ] Minimum Cost to Move Chips

### Medium
- [ ] Jump Game
- [ ] Jump Game II
- [ ] Gas Station
- [ ] Partition Labels
- [ ] Non-overlapping Intervals
- [ ] Minimum Number of Arrows to Burst Balloons
- [ ] Task Scheduler

### Hard
- [ ] Candy
- [ ] Merge Intervals
- [ ] Insert Interval
- [ ] Meeting Rooms II
- [ ] Patching Array

## Time & Space Complexity Patterns
- Often O(n log n) due to sorting
- Greedy choice: O(1) per decision
- Better than DP when applicable

## Tips
- Sorting often helps identify greedy choice
- Prove greedy choice leads to optimal solution
- Consider counterexamples
- Intervals problems often use greedy approach
- Greedy doesn't always work - know when it applies
