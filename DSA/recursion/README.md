# Recursion

## Overview
Recursion is a technique where a function calls itself to solve a problem by breaking it into smaller subproblems.

## Key Concepts
- Base case(s)
- Recursive case
- Call stack
- Tail recursion
- Memoization
- Recursion tree

## Common Problems

### Easy
- [ ] Fibonacci Number
- [ ] Power of Two/Three/Four
- [ ] Reverse String
- [ ] Merge Two Sorted Lists

### Medium
- [ ] Generate Parentheses
- [ ] K-th Symbol in Grammar
- [ ] Different Ways to Add Parentheses
- [ ] Flatten Nested List Iterator

### Hard
- [ ] Regular Expression Matching
- [ ] Wildcard Matching

## Time & Space Complexity Patterns
- Space complexity: O(n) for call stack depth
- Time depends on branching factor and depth
- With memoization: often O(n) time, O(n) space

## Tips
- Always define clear base case(s)
- Ensure progress toward base case
- Draw recursion tree for understanding
- Consider iterative alternative
- Use memoization to avoid redundant calculations
- Tail recursion can be optimized by compiler
