# Bit Manipulation

## Overview
Bit manipulation involves direct manipulation of bits for efficient operations and elegant solutions.

## Key Concepts
- Basic operations: AND, OR, XOR, NOT
- Bit shifts: left shift (<<), right shift (>>)
- Common tricks and patterns
- Bit masking
- Two's complement

## Common Bit Tricks
- `x & (x-1)`: Clear lowest set bit
- `x & -x`: Isolate lowest set bit
- `x ^ x = 0`: XOR with self is 0
- `x ^ 0 = x`: XOR with 0 is identity
- `x & 1`: Check if odd
- `x >> 1`: Divide by 2
- `x << 1`: Multiply by 2

## Common Problems

### Easy
- [ ] Single Number
- [ ] Number of 1 Bits
- [ ] Reverse Bits
- [ ] Power of Two
- [ ] Missing Number
- [ ] Counting Bits

### Medium
- [ ] Single Number II
- [ ] Single Number III
- [ ] Bitwise AND of Numbers Range
- [ ] Sum of Two Integers (without +/-)
- [ ] Divide Two Integers
- [ ] UTF-8 Validation

### Hard
- [ ] Maximum XOR of Two Numbers in an Array
- [ ] Concatenated Words

## Time & Space Complexity Patterns
- Bit operations: O(1) time
- Iterating bits: O(log n) or O(32) for 32-bit integers
- Very space efficient: O(1)

## Tips
- XOR has useful properties for finding unique elements
- Bit manipulation often leads to O(1) space solutions
- Practice common bit tricks
- Use bit masks for subset generation
- Consider bits individually for complex operations
