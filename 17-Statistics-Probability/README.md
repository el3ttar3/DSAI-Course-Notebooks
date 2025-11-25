# Statistics and Probability

> Applying statistical methods and probability theory to analyze data

---

## What You'll Learn

| Topic | Description |
|-------|-------------|
| **Simulation** | Monte Carlo methods and random sampling |
| **Statistical Analysis** | Descriptive and inferential statistics |
| **Data Cleaning** | Handling missing values and outliers |
| **Hypothesis Testing** | T-tests, ANOVA, correlation analysis |

---

## Notebooks

| Notebook | Description |
|----------|-------------|
| `STAT_CMPS360_Dice_Simulation.ipynb` | Dice rolling simulation and probability |
| `STAT_COVID_Fear_Data_Analysis.ipynb` | Statistical analysis of COVID-19 fear survey data |
| `STAT_Amazon_Data_Cleaning.ipynb` | Data cleaning and preprocessing for Amazon dataset |

---

## Quick Start

```python
import numpy as np
from scipy import stats

# Simulate dice rolls
def simulate_dice(num_rolls):
    rolls = np.random.randint(1, 7, num_rolls)
    return np.sum(rolls)

# Run simulation
results = [simulate_dice(1000) for _ in range(10000)]

# Statistical analysis
mean = np.mean(results)
std = np.std(results)
print(f"Mean: {mean:.2f}, Std: {std:.2f}")
```

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

