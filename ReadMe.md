
# Solving Frozen Lake Environment Using Search Algorithms

## Overview

This project implements various search algorithms to solve the **Frozen Lake** environment, a classic reinforcement learning problem from OpenAI Gym. The goal is to navigate an agent across a grid to reach a target while avoiding traps (holes). The environment's dynamics are stochastic, adding complexity to the navigation task.

The following search algorithms have been implemented in **Python**:
1. **Depth-First Search (DFS)**
2. **Breadth-First Search (BFS)**
3. **Greedy Best-First Search**
4. **A*** (A-Star) Search

---

## Features

- **Algorithms:**
  - **DFS:** Explores as deep as possible before backtracking.
  - **BFS:** Explores all nodes at the present depth level before moving to the next.
  - **Greedy Search:** Uses a heuristic to prioritize exploration of the most promising nodes.
  - **A*** Search:** Combines cost from the start with a heuristic to find the shortest path efficiently.

- **Environment:**
  - The Frozen Lake gridworld, customizable for size (e.g., 4x4, 8x8).
  - Stochastic transitions: Actions may not always lead to the intended outcomes.

- **Visualization:**
  - Displays the path found by each algorithm.
  - Optionally logs steps taken during execution.

- **Metrics:**
  - Tracks the number of explored nodes.
  - Measures the total cost of the path.
  - Reports the time taken for each algorithm.

---

## Future Enhancements

1. **Heuristic Improvements:** Optimize heuristics for A* and Greedy algorithms.
2. **Dynamic Environment:** Introduce dynamic obstacles or moving hazards.
3. **Algorithm Comparison:** Generate visual graphs comparing performance metrics.

---

## References

1. [OpenAI Gymnasium Documentation](https://gymnasium.farama.org/)
2. [A* Search Algorithm](https://en.wikipedia.org/wiki/A*_search_algorithm)

---

## Authors
- Names: Emre Can Yologlu


---

## License
This project is developed for educational purposes and is licensed under the MIT License.

