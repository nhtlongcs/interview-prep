# Hash Tables

## Overview
Hash tables provide fast insertion, deletion, and lookup through key-value mapping using hash functions.

## Key Concepts
- Hash functions
- Collision resolution (chaining, open addressing)
- Load factor
- Time complexity analysis
- Set vs Map
- Hash set for existence checking

## Common Use Cases
- Frequency counting
- Duplicate detection
- Caching/Memoization
- Index mapping
- Group/categorize elements

## Common Problems

### Easy
- [ ] Two Sum
- [ ] Contains Duplicate
- [ ] Valid Anagram
- [ ] Intersection of Two Arrays
- [ ] Happy Number
- [ ] Isomorphic Strings

### Medium
- [ ] Group Anagrams
- [ ] Top K Frequent Elements
- [ ] Subarray Sum Equals K
- [ ] Longest Consecutive Sequence
- [ ] Continuous Subarray Sum
- [ ] Design HashMap

### Hard
- [ ] Longest Substring with At Most K Distinct Characters
- [ ] Substring with Concatenation of All Words
- [ ] LRU Cache
- [ ] LFU Cache

## Time & Space Complexity Patterns
- Average case: O(1) for insert, delete, lookup
- Worst case: O(n) for poor hash function
- Space: O(n) for storing elements

## Tips
- Trade space for time complexity
- Use for O(1) lookup requirements
- Consider hash collision in complexity analysis
- Python: dict, set
- Java: HashMap, HashSet
- C++: unordered_map, unordered_set
