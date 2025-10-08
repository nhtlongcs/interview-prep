# Stacks & Queues

## Overview
Stacks (LIFO - Last In First Out) and Queues (FIFO - First In First Out) are fundamental linear data structures with restricted access patterns.

## Key Concepts
- Stack operations: push, pop, peek
- Queue operations: enqueue, dequeue, front
- Monotonic stack/queue
- Deque (double-ended queue)
- Priority queue (heap-based)

## Common Problems

### Easy
- [ ] Valid Parentheses
- [ ] Implement Queue using Stacks
- [ ] Implement Stack using Queues
- [ ] Min Stack
- [ ] Backspace String Compare

### Medium
- [ ] Evaluate Reverse Polish Notation
- [ ] Daily Temperatures
- [ ] Next Greater Element II
- [ ] Decode String
- [ ] Asteroid Collision
- [ ] Sliding Window Maximum

### Hard
- [ ] Largest Rectangle in Histogram
- [ ] Maximal Rectangle
- [ ] Trapping Rain Water
- [ ] Basic Calculator

## Time & Space Complexity Patterns
- Basic operations: O(1) time
- Monotonic stack: O(n) time for n elements
- Priority queue: O(log n) for insert/remove

## Tips
- Use stack for matching/validation problems (parentheses, tags)
- Monotonic stack for "next greater/smaller element" problems
- DFS can be implemented with explicit stack
- BFS typically uses queue
- Consider deque when you need access to both ends
