# Nature-Inspired Computing

> Solving complex optimization problems using algorithms inspired by nature

---

## What You'll Learn

| Topic | Description |
|-------|-------------|
| **Particle Swarm Optimization** | Swarm behavior-based optimization |
| **Bat Algorithm** | Echolocation-inspired metaheuristic |
| **Genetic Algorithms** | Evolution-based search and optimization |
| **Hyperparameter Tuning** | Automated model configuration |
| **Path Planning** | Robot navigation optimization |

---

## Notebooks

| Notebook | Description |
|----------|-------------|
| `NIC_PSO_Hyperparameter_Optimization.ipynb` | PSO for deep learning hyperparameter tuning |
| `NIC_Bat_Algorithm_Deep_Learning.ipynb` | Bat algorithm for CNN optimization |
| `NIC_Lab8_Swarm_Intelligence.ipynb` | Swarm intelligence fundamentals |
| `NIC_Genetic_Algorithm_Path_Planning.ipynb` | GA vs A* for robot path planning |
| `NIC_Robot_Scheduling_Optimization.ipynb` | Robot task scheduling optimization |
| `NIC_Robot_Scheduling_V2.ipynb` | Enhanced scheduling algorithms |

---

## Quick Start

```python
from pyswarm import pso

# Define objective function
def objective(params):
    lr, dropout = params
    # Train model and return loss
    return validation_loss

# Define bounds
lb = [0.0001, 0.1]  # Lower bounds
ub = [0.01, 0.5]    # Upper bounds

# Run PSO
best_params, best_score = pso(objective, lb, ub, swarmsize=10, maxiter=20)
```

---

## Algorithm Comparison

| Algorithm | Inspiration | Best For |
|-----------|-------------|----------|
| **PSO** | Bird flocking | Continuous optimization |
| **GA** | Natural selection | Discrete/combinatorial problems |
| **Bat** | Echolocation | Dynamic parameter adjustment |

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
