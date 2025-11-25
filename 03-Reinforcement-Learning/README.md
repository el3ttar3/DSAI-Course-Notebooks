# Reinforcement Learning

> Training agents to make optimal decisions through trial and error

---

## What You'll Learn

| Topic | Description |
|-------|-------------|
| **Markov Decision Processes** | Mathematical framework for sequential decisions |
| **Policy Evaluation** | Computing value functions for policies |
| **Value Iteration** | Finding optimal policies iteratively |
| **Gridworld** | Classic RL environment for learning |
| **Reward Shaping** | Understanding reward structure effects |

---

## Notebooks

| Notebook | Description |
|----------|-------------|
| `RL_Assignment1_Markov_Chains.ipynb` | Markov chain simulation and analysis |
| `RL_Assignment2_Gridworld_MDP.ipynb` | Gridworld MDP with iterative policy evaluation |

---

## Quick Start

```python
import numpy as np

# Define transition matrix
T = np.array([
    [0.25, 0.35, 0.40, 0.00],
    [0.55, 0.00, 0.00, 0.45],
    [0.00, 0.20, 0.60, 0.20],
    [0.30, 0.30, 0.20, 0.20]
])

# Simulate transitions
current_state = 0
for _ in range(100):
    next_state = np.random.choice(4, p=T[current_state])
    current_state = next_state
```

---

## Key Equations

**Bellman Equation:**
$$V(s) = \sum_a \pi(a|s) \sum_{s'} P(s'|s,a)[R(s,a,s') + \gamma V(s')]$$

**Value Function Update:**
$$V_{k+1}(s) = \max_a \sum_{s'} P(s'|s,a)[R + \gamma V_k(s')]$$

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
