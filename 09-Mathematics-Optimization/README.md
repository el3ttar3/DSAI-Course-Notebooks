# Mathematics and Optimization

> Applying mathematical principles to solve real-world navigation and planning problems

---

## What You'll Learn

| Topic | Description |
|-------|-------------|
| **3D Navigation** | Autonomous drone movement in 3D space |
| **Path Planning** | Finding optimal routes in environments |
| **A* Algorithm** | Informed search for shortest paths |
| **Search Algorithms** | BFS, DFS, and heuristic search |
| **Problem Formulation** | Modeling real-world problems mathematically |

---

## Notebooks

| Notebook | Description |
|----------|-------------|
| `MATH_Drone_3D_Navigation.ipynb` | 3D drone navigation with search algorithms |
| `MATH_Drone_Project_D1.ipynb` | Drone project implementation phase 1 |

---

## Quick Start

```python
class DroneNavigationProblem:
    def __init__(self, grid_size, initial_state, goal_state):
        self.grid_size = grid_size
        self.initial_state = initial_state
        self.goal_state = goal_state
    
    def get_actions(self, state):
        actions = []
        x, y, z = state
        if x > 0: actions.append("left")
        if x < self.grid_size[0] - 1: actions.append("right")
        if y > 0: actions.append("backward")
        if y < self.grid_size[1] - 1: actions.append("forward")
        if z > 0: actions.append("down")
        if z < self.grid_size[2] - 1: actions.append("up")
        return actions
```

---

## Visualization

The notebooks include 3D visualizations of:
- Drone flight paths
- Obstacle avoidance
- Algorithm convergence

---

## Institution

<p align="center">
  <a href="https://www.zewailcity.edu.eg/">
    <strong>Zewail City of Science and Technology</strong>
  </a>
  <br/>
  <em>University of Science and Technology</em>
</p>

---

**Author**: Abdelrahman Elattar | DSAI Program
