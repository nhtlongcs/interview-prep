# Data Structures & Algorithms (DSA)

## Overview
This section contains comprehensive resources for preparing for technical interviews focusing on data structures and algorithms. Topics are organized by category with problem sets ranging from easy to hard difficulty.

## Getting Started

### Prerequisites
- Basic programming knowledge in at least one language (Python, Java, C++, JavaScript)
- Understanding of basic complexity analysis (Big O notation)
- Familiarity with common data types and operations

### Recommended Study Order

#### Phase 1: Foundations (Weeks 1-2)
1. **[Arrays](./arrays/)** - Master basic array operations and two-pointer technique
2. **[Strings](./strings/)** - String manipulation and pattern matching
3. **[Hash Tables](./hash-tables/)** - Fast lookup and frequency counting

#### Phase 2: Linear Structures (Weeks 3-4)
4. **[Linked Lists](./linked-lists/)** - Pointer manipulation and traversal
5. **[Stacks & Queues](./stacks-queues/)** - LIFO and FIFO operations
6. **[Recursion](./recursion/)** - Recursive thinking and problem decomposition

#### Phase 3: Non-Linear Structures (Weeks 5-6)
7. **[Trees](./trees/)** - Binary trees, BST, and tree traversals
8. **[Heaps](./heaps/)** - Priority queues and heap operations
9. **[Graphs](./graphs/)** - Graph algorithms and traversals

#### Phase 4: Algorithms (Weeks 7-8)
10. **[Sorting & Searching](./sorting-searching/)** - Various sorting algorithms and binary search
11. **[Bit Manipulation](./bit-manipulation/)** - Efficient bit-level operations
12. **[Greedy](./greedy/)** - Greedy choice and optimization

#### Phase 5: Advanced (Weeks 9-12)
13. **[Dynamic Programming](./dynamic-programming/)** - Memoization and tabulation
14. **[Backtracking](./backtracking/)** - Constraint satisfaction and search space exploration

## Problem-Solving Framework

### Step 1: Understand the Problem
- Read carefully and identify inputs/outputs
- Ask clarifying questions
- Consider edge cases
- Work through examples manually

### Step 2: Plan Your Approach
- Identify the problem pattern
- Consider multiple approaches
- Analyze time and space complexity
- Choose the most efficient solution

### Step 3: Implement
- Write clean, readable code
- Use meaningful variable names
- Add comments for complex logic
- Handle edge cases

### Step 4: Test
- Test with provided examples
- Test edge cases (empty, single element, duplicates)
- Test with large inputs
- Verify complexity

### Step 5: Optimize
- Can you improve time complexity?
- Can you reduce space complexity?
- Are there any redundant operations?

## Common Patterns to Master

### 1. Two Pointers
- Used in: Arrays, Strings, Linked Lists
- Examples: Two Sum (sorted), Remove Duplicates

### 2. Sliding Window
- Used in: Arrays, Strings
- Examples: Longest Substring, Maximum Subarray

### 3. Fast & Slow Pointers
- Used in: Linked Lists, Cycles
- Examples: Cycle Detection, Find Middle

### 4. Merge Intervals
- Used in: Arrays, Intervals
- Examples: Merge Intervals, Meeting Rooms

### 5. Cyclic Sort
- Used in: Arrays with numbers in range
- Examples: Find Missing Number, Find Duplicates

### 6. In-place Reversal
- Used in: Linked Lists
- Examples: Reverse Linked List, Reverse in Groups

### 7. Tree BFS
- Used in: Trees
- Examples: Level Order Traversal, Zigzag Traversal

### 8. Tree DFS
- Used in: Trees
- Examples: Sum of Paths, All Paths

### 9. Graph BFS/DFS
- Used in: Graphs
- Examples: Number of Islands, Clone Graph

### 10. Dynamic Programming
- Used in: Optimization problems
- Examples: Longest Common Subsequence, Knapsack

## Complexity Cheat Sheet

### Data Structure Operations
| Data Structure | Access | Search | Insert | Delete |
|---------------|--------|--------|--------|--------|
| Array | O(1) | O(n) | O(n) | O(n) |
| Stack | O(n) | O(n) | O(1) | O(1) |
| Queue | O(n) | O(n) | O(1) | O(1) |
| Linked List | O(n) | O(n) | O(1)* | O(1)* |
| Hash Table | - | O(1)† | O(1)† | O(1)† |
| Binary Search Tree | O(log n)† | O(log n)† | O(log n)† | O(log n)† |
| Heap | - | O(n) | O(log n) | O(log n) |

*With pointer to position  
†Average case, worst case can be O(n)

### Sorting Algorithms
| Algorithm | Best | Average | Worst | Space | Stable |
|-----------|------|---------|-------|-------|--------|
| Bubble Sort | O(n) | O(n²) | O(n²) | O(1) | Yes |
| Selection Sort | O(n²) | O(n²) | O(n²) | O(1) | No |
| Insertion Sort | O(n) | O(n²) | O(n²) | O(1) | Yes |
| Merge Sort | O(n log n) | O(n log n) | O(n log n) | O(n) | Yes |
| Quick Sort | O(n log n) | O(n log n) | O(n²) | O(log n) | No |
| Heap Sort | O(n log n) | O(n log n) | O(n log n) | O(1) | No |

## Interview Tips

### Before the Interview
- Review fundamental data structures and algorithms
- Practice coding without IDE assistance
- Time yourself on problems
- Practice explaining your thought process out loud

### During the Interview
- Ask clarifying questions
- Communicate your thought process
- Start with a brute force solution
- Optimize step by step
- Write clean, readable code
- Test your solution thoroughly
- Be open to hints and feedback

### Common Pitfalls to Avoid
- Jumping into coding without planning
- Not considering edge cases
- Poor variable naming
- Not testing the solution
- Giving up too quickly
- Not asking for help when stuck

## Resources

### Online Platforms
- LeetCode
- HackerRank
- CodeForces
- TopCoder

### Books
- "Cracking the Coding Interview" by Gayle Laakmann McDowell
- "Introduction to Algorithms" by CLRS
- "Algorithm Design Manual" by Steven Skiena
- "Elements of Programming Interviews"

### Courses
- MIT OpenCourseWare: Introduction to Algorithms
- Princeton: Algorithms Part I & II (Coursera)
- Stanford: Algorithms Specialization

## Progress Tracking

Keep track of your progress by checking off problems as you complete them in each topic's README. Aim to solve:
- All Easy problems
- Most Medium problems
- Key Hard problems

Good luck with your interview preparation! 🚀
