# Graphs

## Overview
Graphs are non-linear data structures consisting of vertices (nodes) and edges connecting them. Essential for modeling relationships and networks.

## Key Concepts
- Graph representations (adjacency list, adjacency matrix)
- DFS (Depth-First Search)
- BFS (Breadth-First Search)
- Shortest path algorithms (Dijkstra, Bellman-Ford)
- Minimum Spanning Tree (Prim's, Kruskal's)
- Topological sorting
- Union-Find (Disjoint Set)

## Common Problems

### Easy
- [ ] Find Center of Star Graph
- [ ] Find if Path Exists in Graph
- [ ] Number of Provinces
- [ ] Clone Graph

### Medium
- [ ] Number of Islands
- [ ] Course Schedule
- [ ] Course Schedule II
- [ ] Pacific Atlantic Water Flow
- [ ] Network Delay Time
- [ ] All Paths From Source to Target
- [ ] Redundant Connection

### Hard
- [ ] Word Ladder
- [ ] Word Ladder II
- [ ] Alien Dictionary
- [ ] Critical Connections in a Network
- [ ] Shortest Path Visiting All Nodes

## Time & Space Complexity Patterns
- DFS/BFS: O(V + E) time, O(V) space
- Dijkstra: O((V + E) log V) with heap
- Bellman-Ford: O(VE) time
- Floyd-Warshall: O(V³) time

## Tips
- Choose DFS for path finding, BFS for shortest path in unweighted graphs
- Use visited set to avoid cycles
- Consider both adjacency list and matrix representations
- Union-Find is efficient for connectivity problems
- Topological sort for dependency ordering
