# Fuzzy Logic

> Implementing fuzzy logic systems for approximate reasoning

---

## What You'll Learn

| Topic | Description |
|-------|-------------|
| **Fuzzy Sets** | Membership functions and fuzzy variables |
| **Fuzzy Rules** | If-then rules for fuzzy inference |
| **Defuzzification** | Converting fuzzy output to crisp values |
| **Control Systems** | Fuzzy logic controllers |

---

## Notebooks

| Notebook | Description |
|----------|-------------|
| `FUZZY_Scikit_Fuzzy_Control.ipynb` | Fuzzy control system with scikit-fuzzy |

---

## Quick Start

```python
import numpy as np
import skfuzzy as fuzz
from skfuzzy import control as ctrl

# Define fuzzy variables
temperature = ctrl.Antecedent(np.arange(0, 101, 1), 'temperature')
fan_speed = ctrl.Consequent(np.arange(0, 101, 1), 'fan_speed')

# Define membership functions
temperature['cold'] = fuzz.trimf(temperature.universe, [0, 0, 50])
temperature['warm'] = fuzz.trimf(temperature.universe, [25, 50, 75])
temperature['hot'] = fuzz.trimf(temperature.universe, [50, 100, 100])

fan_speed['low'] = fuzz.trimf(fan_speed.universe, [0, 0, 50])
fan_speed['medium'] = fuzz.trimf(fan_speed.universe, [25, 50, 75])
fan_speed['high'] = fuzz.trimf(fan_speed.universe, [50, 100, 100])

# Define rules
rule1 = ctrl.Rule(temperature['cold'], fan_speed['low'])
rule2 = ctrl.Rule(temperature['warm'], fan_speed['medium'])
rule3 = ctrl.Rule(temperature['hot'], fan_speed['high'])
```

---

## Applications

- Temperature control systems
- Washing machine controllers
- Autonomous vehicle navigation
- Decision support systems

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

