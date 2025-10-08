# Trees

## Overview
Trees are hierarchical data structures with a root node and children forming a parent-child relationship. Binary trees and binary search trees are particularly common in interviews.

## Key Concepts
- Tree traversals (inorder, preorder, postorder, level-order)
- Binary Search Trees (BST)
- Balanced trees (AVL, Red-Black)
- Tree depth and height
- Lowest Common Ancestor (LCA)
- Serialization and deserialization

## Common Problems

### Easy
- [ ] Maximum Depth of Binary Tree
- [ ] Same Tree
- [ ] Invert Binary Tree
- [ ] Symmetric Tree
- [ ] Binary Tree Paths
- [ ] Balanced Binary Tree

### Medium
- [ ] Validate Binary Search Tree
- [ ] Binary Tree Level Order Traversal
- [ ] Construct Binary Tree from Preorder and Inorder Traversal
- [ ] Lowest Common Ancestor of a Binary Tree
- [ ] Binary Tree Right Side View
- [ ] Kth Smallest Element in a BST

### Hard
- [ ] Binary Tree Maximum Path Sum
- [ ] Serialize and Deserialize Binary Tree
- [ ] Binary Tree Cameras
- [ ] Vertical Order Traversal of a Binary Tree

## Time & Space Complexity Patterns
- DFS traversal: O(n) time, O(h) space (h = height)
- BFS traversal: O(n) time, O(w) space (w = max width)
- BST operations: O(log n) average, O(n) worst case

## Tips
- Recursion is natural for tree problems
- Consider DFS vs BFS based on the problem
- BST inorder traversal gives sorted order
- Use helper functions for complex recursion
- Practice drawing trees to visualize solutions
