# Biochemistry and Chemistry

> Computational approaches to chemistry and biochemistry problems

---

## What You'll Learn

| Topic | Description |
|-------|-------------|
| **Calibration Curves** | Standard curve generation and analysis |
| **Protein Assays** | Lowry and Bradford methods |
| **Stoichiometry** | Chemical reaction calculations |
| **Thermodynamics** | Heat and energy calculations |

---

## Notebooks

| Notebook | Description |
|----------|-------------|
| `BIO_Lowry_Assay_Calibration.ipynb` | Protein quantification using Lowry assay |
| `BIO_BSA_Protein_Determination.ipynb` | BSA standard curve for protein determination |
| `CHEM_Methane_Combustion_Analysis.ipynb` | Methane combustion stoichiometry and energy |

---

## Quick Start

```python
import numpy as np
from scipy.stats import linregress
import matplotlib.pyplot as plt

# Standard concentrations and absorbance
concentrations = np.array([0.0, 0.25, 0.50, 0.75, 1.0])
absorbance = np.array([0.00, 0.18, 0.37, 0.55, 0.73])

# Linear regression
slope, intercept, r_value, p_value, std_err = linregress(concentrations, absorbance)

# Calculate unknown concentration
unknown_abs = 0.45
unknown_conc = (unknown_abs - intercept) / slope
print(f"Unknown concentration: {unknown_conc:.3f} mg/ml")
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

