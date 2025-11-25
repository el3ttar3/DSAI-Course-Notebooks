# Data Visualization

> Creating interactive and insightful visual representations of data

---

## What You'll Learn

| Topic | Description |
|-------|-------------|
| **Plotly** | Interactive charts and graphs |
| **Dash** | Building web dashboards in Python |
| **Seaborn** | Statistical data visualization |
| **Gapminder** | World development indicators analysis |

---

## Notebooks

| Notebook | Description |
|----------|-------------|
| `VIZ_Plotly_Gapminder_Analysis.ipynb` | Interactive visualizations with Plotly and Gapminder data |
| `VIZ_Dash_Interactive_Dashboard.ipynb` | Building interactive dashboards with Dash |

---

## Quick Start

```python
import plotly.express as px

# Load Gapminder data
df = px.data.gapminder()

# Create animated scatter plot
fig = px.scatter(
    df, x="gdpPercap", y="lifeExp",
    animation_frame="year", animation_group="country",
    size="pop", color="continent",
    hover_name="country", log_x=True
)
fig.show()
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

