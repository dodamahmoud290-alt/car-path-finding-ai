🚗 Car Path Finding

📌 Project Overview
This project compares three AI approaches for pathfinding on a grid. 
BFS guarantees optimal solutions, A* improves efficiency using heuristic guidance, 
while the Genetic Algorithm provides a stochastic optimization approach without guaranteeing optimality.

🎯 Project Goal
We compare all algorithms based on:
⚡ Execution time
🧠 Memory usage (number of visited nodes)
✅ Ability to reach the goal
⭐ Optimality of the solution (shortest path)

🧩 Algorithm Details
- BFS: explores all nodes uniformly, guarantees shortest path, high memory usage
- A*: uses heuristic (Manhattan distance) to guide search, faster than BFS
- GA: evolves paths using selection, crossover, and mutation; may not find optimal path

🗺️ Example Grid
S = Start, G = Goal, X = Obstacle
[
 ['S', '.', '.', 'X', '.'],
 ['.', 'X', '.', 'X', '.'],
 ['.', '.', '.', '.', '.'],
 ['X', '.', 'X', '.', 'G'],
 ['.', '.', '.', '.', '.']
]

📂 How to Run
- Run in Python: `python main.py`
- Or run in Google Colab
- Output: paths for BFS, A*, GA and visualizations saved as PNG files

👥 Team Members
1. Mahmoud Abdallah Khattab Ragab
