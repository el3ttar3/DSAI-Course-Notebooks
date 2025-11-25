# Machine Learning Labs

> Hands-on practice with fundamental machine learning concepts and algorithms

---

## What You'll Learn

| Topic | Description |
|-------|-------------|
| **Classification** | Predicting categorical outcomes |
| **Regression** | Predicting continuous values |
| **Model Evaluation** | Accuracy, precision, recall, F1 |
| **Cross-Validation** | Robust model assessment |
| **Feature Selection** | Identifying important variables |

---

## Notebooks

| Notebook | Description |
|----------|-------------|
| `ML_Assignment1_Basics.ipynb` | Introduction to ML fundamentals |
| `ML_Assignment2_Advanced.ipynb` | Advanced ML techniques |
| `ML_Lab1_Introduction.ipynb` | Lab 1: Getting started |
| `ML_General_Practice.ipynb` | General practice exercises |
| `ML_Lab_Practice.ipynb` | Hands-on lab practice |
| `ML_Assignment1_Classification.ipynb` | Classification algorithms |
| `ML_Assignment1c_Variant.ipynb` | Assignment variant |
| `ML_Lab_Practice_General.ipynb` | General practice session |
| `ML_Lab_Practice_1.ipynb` | Practice session 1 |
| `ML_Lab_Practice_3.ipynb` | Practice session 3 |

---

## Quick Start

```python
from sklearn.model_selection import train_test_split
from sklearn.ensemble import RandomForestClassifier
from sklearn.metrics import classification_report

# Split data
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2)

# Train model
clf = RandomForestClassifier(n_estimators=100)
clf.fit(X_train, y_train)

# Evaluate
y_pred = clf.predict(X_test)
print(classification_report(y_test, y_pred))
```

---

## ML Workflow

```
Data → Preprocessing → Feature Engineering → Model Selection → Training → Evaluation
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
