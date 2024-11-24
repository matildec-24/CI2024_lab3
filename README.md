# CI2024_lab3

# Solving the N²-1 Puzzle Problem

This repository implements two algorithms to solve the N²-1 puzzle:
- A* Algorithm: An algorithm that combines the cost to reach a state (g-score) with a heuristic estimate (h-score) of the cost to the goal. This implementation uses the Manhattan Distance as the heuristic, ensuring efficient exploration of the solution space.
- Bidirectional A*: An optimized version of A* that searches simultaneously from both the start state and the goal state. By meeting in the middle, this approach reduces the number of explored states and improves performance for large puzzles.
