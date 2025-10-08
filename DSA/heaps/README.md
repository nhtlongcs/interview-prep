# Heaps

## Overview
Heaps are complete binary trees that maintain heap property (parent vs children ordering). Primary implementation of priority queues.

## Key Concepts
- Min heap and max heap
- Heapify operations
- Heap insertion and deletion
- Top k elements
- Merge k sorted streams
- Running median

## Common Problems

### Easy
- [ ] Kth Largest Element in a Stream
- [ ] Last Stone Weight
- [ ] Relative Ranks

### Medium
- [ ] Kth Largest Element in an Array
- [ ] Top K Frequent Elements
- [ ] K Closest Points to Origin
- [ ] Find K Pairs with Smallest Sums
- [ ] Reorganize String
- [ ] Task Scheduler

### Hard
- [ ] Merge k Sorted Lists
- [ ] Find Median from Data Stream
- [ ] Sliding Window Median
- [ ] IPO
- [ ] Minimum Cost to Hire K Workers

## Time & Space Complexity Patterns
- Insert: O(log n) time
- Remove max/min: O(log n) time
- Peek: O(1) time
- Build heap: O(n) time
- Heap sort: O(n log n) time

## Tips
- Use heap for "top k" or "k smallest/largest" problems
- Two heaps (min and max) for running median
- Consider heap when need to repeatedly access min/max
- Heapify is more efficient than repeated insertions
- Python: heapq (min heap), use negative values for max heap
