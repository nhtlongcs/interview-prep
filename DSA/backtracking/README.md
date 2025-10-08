# Backtracking

## Overview
Backtracking is an algorithmic technique for solving problems recursively by trying to build a solution incrementally and abandoning solutions that fail to satisfy constraints.

## Key Concepts
- Decision tree exploration
- Pruning invalid branches
- State restoration
- Combinations vs permutations
- Constraint satisfaction

## Common Patterns
- Generate all subsets/combinations
- Generate all permutations
- N-Queens problem
- Sudoku solver
- Word search

## Common Problems

### Easy
- [ ] Generate Parentheses (simple case)
- [ ] Letter Case Permutation
- [ ] Binary Watch

### Medium
- [ ] Permutations
- [ ] Permutations II
- [ ] Combinations
- [ ] Combination Sum
- [ ] Combination Sum II
- [ ] Subsets
- [ ] Subsets II
- [ ] Word Search
- [ ] Generate Parentheses
- [ ] Letter Combinations of a Phone Number

### Hard
- [ ] N-Queens
- [ ] N-Queens II
- [ ] Sudoku Solver
- [ ] Word Search II
- [ ] Palindrome Partitioning II
- [ ] Expression Add Operators

## Time & Space Complexity Patterns
- Subsets: O(2ⁿ) time
- Permutations: O(n!) time
- Combinations: O(C(n,k) * k) time
- Space: O(n) for recursion depth

## Tips
- Use helper function with state parameters
- Remember to backtrack (restore state)
- Use visited array/set to avoid duplicates
- Prune branches early when possible
- Sort input for easier duplicate handling
- Draw decision tree to visualize recursion
