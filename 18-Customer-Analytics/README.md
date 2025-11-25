# Customer Analytics

> Understanding customer behavior through data analysis and segmentation

---

## What You'll Learn

| Topic | Description |
|-------|-------------|
| **Customer Segmentation** | Grouping customers by behavior |
| **Synthetic Data** | Generating realistic test data |
| **RFM Analysis** | Recency, Frequency, Monetary analysis |
| **Clustering** | K-means and hierarchical clustering |

---

## Notebooks

| Notebook | Description |
|----------|-------------|
| `CUST_Vodafone_Customer_Segmentation.ipynb` | Customer segmentation with synthetic telecom data |

---

## Quick Start

```python
from faker import Faker
import pandas as pd

fake = Faker()

# Generate synthetic customer data
customers = []
for _ in range(1000):
    customers.append({
        'name': fake.name(),
        'email': fake.email(),
        'phone': fake.phone_number(),
        'plan': np.random.choice(['Basic', 'Premium', 'Elite']),
        'monthly_spend': np.random.uniform(50, 500)
    })

df = pd.DataFrame(customers)
```

---

## Business Applications

- Customer churn prediction
- Marketing campaign targeting
- Product recommendation
- Lifetime value estimation

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

