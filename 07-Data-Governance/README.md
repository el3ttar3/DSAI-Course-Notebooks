# Data Governance

> Ensuring data quality, consistency, and integrity throughout the data lifecycle

---

## What You'll Learn

| Topic | Description |
|-------|-------------|
| **Data Cleaning** | Handling missing, incorrect, and duplicate data |
| **Missing Values** | Imputation strategies and best practices |
| **Data Encoding** | Converting categorical to numerical data |
| **Normalization** | Scaling features for ML models |
| **Data Quality** | Validation and quality assurance |

---

## Notebooks

| Notebook | Description |
|----------|-------------|
| `DG_Lab5_Data_Cleaning_Preprocessing.ipynb` | Comprehensive data cleaning pipeline |

---

## Quick Start

```python
import pandas as pd
from sklearn.preprocessing import StandardScaler, LabelEncoder

# Handle missing values
df['column'].fillna(df['column'].mean(), inplace=True)

# Remove duplicates
df.drop_duplicates(inplace=True)

# Encode categorical variables
le = LabelEncoder()
df['category'] = le.fit_transform(df['category'])

# Normalize numerical features
scaler = StandardScaler()
df[['feature1', 'feature2']] = scaler.fit_transform(df[['feature1', 'feature2']])
```

---

## Data Quality Checklist

- [ ] Check for missing values
- [ ] Identify and handle duplicates
- [ ] Validate data types
- [ ] Check for outliers
- [ ] Ensure consistent formatting
- [ ] Verify data ranges

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
