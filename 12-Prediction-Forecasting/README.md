# Prediction and Forecasting

> Building models to predict future values and detect anomalies in time series data

---

## What You'll Learn

| Topic | Description |
|-------|-------------|
| **Time Series** | Analyzing sequential data patterns |
| **Forecasting** | Predicting future values |
| **Anomaly Detection** | Identifying unusual patterns |
| **Regression Models** | Continuous value prediction |
| **Feature Engineering** | Creating time-based features |

---

## Notebooks

| Notebook | Description |
|----------|-------------|
| `PRED_Water_Tank_Prediction.ipynb` | Water level prediction model |
| `PRED_Water_Tank_Prediction_V2.ipynb` | Improved prediction pipeline |
| `PRED_Water_Tank_Final.ipynb` | Final optimized model |
| `PRED_Anomaly_Detection.ipynb` | Anomaly detection techniques |

---

## Quick Start

```python
import pandas as pd
from sklearn.ensemble import IsolationForest

# Load time series data
df = pd.read_csv('sensor_data.csv', parse_dates=['timestamp'])

# Create time features
df['hour'] = df['timestamp'].dt.hour
df['day_of_week'] = df['timestamp'].dt.dayofweek

# Anomaly detection
clf = IsolationForest(contamination=0.1)
df['anomaly'] = clf.fit_predict(df[['value']])
```

---

## Project: Water Tank Prediction

This project predicts water tank levels using:
- Historical sensor data
- Time-based features
- Machine learning regression
- Real-time anomaly detection

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
