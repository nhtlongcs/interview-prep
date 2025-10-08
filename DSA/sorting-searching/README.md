# Sorting & Searching

## Overview
Sorting and searching are fundamental algorithms. Understanding various sorting algorithms and binary search is crucial.

## Key Concepts
- Comparison-based sorting
- Non-comparison sorting (counting, radix, bucket)
- Binary search and variants
- Two pointers with sorting
- QuickSelect

## Sorting Algorithms
- Bubble Sort: O(n²)
- Selection Sort: O(n²)
- Insertion Sort: O(n²)
- Merge Sort: O(n log n)
- Quick Sort: O(n log n) average, O(n²) worst
- Heap Sort: O(n log n)
- Counting Sort: O(n + k)
- Radix Sort: O(d(n + k))

## Common Problems

### Easy
- [ ] Binary Search
- [ ] First Bad Version
- [ ] Search Insert Position
- [ ] Valid Perfect Square
- [ ] Sqrt(x)

### Medium
- [ ] Search in Rotated Sorted Array
- [ ] Find First and Last Position of Element in Sorted Array
- [ ] Search a 2D Matrix
- [ ] Find Peak Element
- [ ] Kth Largest Element in an Array
- [ ] Sort Colors (Dutch National Flag)

### Hard
- [ ] Median of Two Sorted Arrays
- [ ] Find Minimum in Rotated Sorted Array II
- [ ] Count of Range Sum
- [ ] Split Array Largest Sum

## Time & Space Complexity Patterns
- Binary search: O(log n) time, O(1) space
- Comparison sorts: O(n log n) time
- QuickSelect: O(n) average for kth element

## Tips
- Binary search: pay attention to boundary conditions
- Consider if sorting helps simplify the problem
- Use appropriate sorting based on constraints
- Binary search works on monotonic functions, not just sorted arrays
- QuickSelect for finding kth element without full sort
