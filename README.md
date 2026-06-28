# rubiks-cube-solver

## ✨ Features

- Complete 3x3 Rubik's Cube simulation
- Object Oriented Design for modularity and maintainability
- Multiple search algorithms:
  - Breadth First Search (BFS)
  - Depth First Search (DFS)
  - Iterative Deepening DFS (IDDFS)
  - Korf's Iterative Deepening A* (IDA*)
- Pattern Database heuristic for fast optimal search
- Efficient cube state representation using STL containers
- Solves cubes scrambled up to **13 random moves in under 10 seconds

## 🧠 Algorithms Used

### Breadth First Search (BFS)

- Guarantees shortest solution
- Suitable only for small search depths
- Used primarily for verification and experimentation

### Depth First Search (DFS)

- Low memory usage
- Explores deep branches efficiently
- Not guaranteed to find the shortest solution

### Iterative Deepening DFS (IDDFS)

- Combines the advantages of BFS and DFS
- Complete while maintaining low memory requirements

### Korf's Iterative Deepening A* (IDA*)

- State-of-the-art search algorithm for Rubik's Cube
- Uses admissible heuristics from Pattern Databases
- Dramatically reduces the search space
