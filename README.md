# Circular Maze Solver using Breadth-First Search
Introduction
Maze Solving:
Maze solving is a classic problem in computer science and robotics, involving finding a path from a starting point to a destination in a maze-like environment. Various algorithms, including depth-first search (DFS), A* search, and BFS, have been employed to address this problem.

Breadth-First Search (BFS)
Overview:
BFS is an algorithmic technique used for traversing or searching tree or graph data structures. It explores all the vertices at the current depth before moving on to the vertices at the next depth level. BFS guarantees finding the shortest path in an unweighted graph.

Key Concepts:

Queue-based Exploration: BFS uses a queue data structure to explore nodes in a level-wise manner.
Visited Nodes: To avoid revisiting nodes, a mechanism is employed to mark nodes as visited.
Optimality: BFS guarantees finding the shortest path due to its level-wise exploration.
Applications:

Pathfinding: BFS is widely used in pathfinding algorithms to find the shortest path between two nodes.
Connected Components: BFS can be used to find connected components in a graph.
Circular Maze Solving
Representation:
Circular mazes pose unique challenges due to their circular structure. Representing them effectively is crucial for applying maze-solving algorithms.

Preprocessing:

Image Thresholding: Converting maze images to binary representations for algorithmic processing.
Skeletonization: Reducing maze structures to their essential paths using techniques like skeletonization.
Related Work
Pathfinding Algorithms:

A Search Algorithm:* A heuristic-based algorithm that combines elements of Dijkstra's algorithm and BFS, often used for finding the shortest path.
Depth-First Search (DFS): Explores as far as possible along one branch before backtracking, less suitable for finding the shortest path.
Circular Maze Navigation:

Research on circular maze solving has applications in robotics, where circular environments may be encountered.
Challenges and Considerations
Complexity:

Circular mazes may introduce additional complexities in terms of representation and traversal.
Optimization:

Balancing the computational cost with optimization is crucial for real-time applications.
Real-World Applications:

Applying circular maze solving to robotic navigation in environments with circular structures

## Introduction

Maze solving is a classic problem in computer science and robotics. This report outlines the implementation of a circular maze solver using the breadth-first search (BFS) algorithm. The maze is represented as a binary image, and the BFS algorithm is employed to find the optimum path from a starting point to an ending point in the circular maze.

## Implementation

### Libraries Used

- `matplotlib`: For image visualization.
- `numpy`: For numerical operations.
- `skimage.morphology`: For skeletonization.

```python
import matplotlib.pylab as plt
import numpy as np
from skimage.morphology import skeletonize
```
STEPS 

1. Loading and Displaying the Circular Maze
2. Preprocessing: Thresholding and Skeletonization
3. Breadth-First Search for Path finding python

Results


The implementation successfully skeletonizes the circular maze and utilizes the BFS algorithm to find the optimal path from the starting point to the ending point.

Conclusion

A theoretical survey on circular maze solving using BFS highlights the significance of BFS in pathfinding, its unique application to circular mazes, and challenges associated with representing and navigating circular environments.
This survey provides a foundation for further research and practical implementations in various domains.
The circular maze solver using BFS provides a robust solution for navigating through circular mazes.
The implementation can be further extended for real-world applications, such as robotic navigation or game development.
This report serves as a concise overview of the implementation, and the provided code snippets can be used as a starting point for further exploration and customization.


