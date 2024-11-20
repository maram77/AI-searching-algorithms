# Sliding Puzzle Solver

This project implements various search algorithms to solve an 8-puzzle game. The sliding puzzle involves moving tiles to arrange them into a predefined goal state. The program uses Python and implements the following algorithms:

- **A* Search** (Heuristic-based optimal path search)
- **Depth-First Search (DFS)** (Explores as far as possible along each branch before backtracking)
- **Breadth-First Search (BFS)** (Explores all possible moves layer by layer)

## Features

- **Customizable Initial and Goal States**: Users can set their own initial and goal configurations of the 8-puzzle.
- **Visualization**: Each step of the solving process is printed in a human-readable format.
- **Performance Metrics**: Tracks the number of steps and time taken to reach the solution.

---

## Algorithms Overview

1. **A* Search**:
   - Combines the cost to reach a node (`g`) and the heuristic estimate to the goal (`h`).
   - Heuristic used: Count of tiles not in their goal position (excluding the empty tile).

2. **Depth-First Search (DFS)**:
   - Explores as far as possible along each branch before backtracking.
   - May not guarantee the shortest path but is simple to implement.

3. **Breadth-First Search (BFS)**:
   - Explores all possible moves at the current depth before going deeper.
   - Guarantees finding the shortest path in terms of moves.

---

## Requirements

- Python 3.x

No additional libraries are required as the code uses only Python's built-in modules like `time` and `copy`.

---


