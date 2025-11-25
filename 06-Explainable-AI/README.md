# Explainable AI

> Making machine learning models transparent and interpretable

---

## What You'll Learn

| Topic | Description |
|-------|-------------|
| **LIME** | Local Interpretable Model-agnostic Explanations |
| **SHAP** | SHapley Additive exPlanations |
| **GradCAM** | Gradient-weighted Class Activation Mapping |
| **Feature Importance** | Understanding model decisions |
| **Model Transparency** | Building trustworthy AI systems |

---

## Notebooks

| Notebook | Description |
|----------|-------------|
| `XAI_LabExam1_Interpretability.ipynb` | Model interpretability techniques |
| `XAI_Exploratory_Data_Analysis.ipynb` | EDA with explainability focus |
| `XAI_LabExam2_Model_B.ipynb` | Advanced XAI implementations |

---

## Quick Start

```python
import shap
import lime
from lime import lime_image

# SHAP explanation
explainer = shap.GradientExplainer(model, background_data)
shap_values = explainer.shap_values(test_data)
shap.image_plot(shap_values, test_images)

# LIME explanation
explainer = lime_image.LimeImageExplainer()
explanation = explainer.explain_instance(image, predict_fn, top_labels=2)
```

---

## XAI Methods Comparison

| Method | Type | Best For |
|--------|------|----------|
| **LIME** | Local | Single prediction explanation |
| **SHAP** | Both | Feature importance ranking |
| **GradCAM** | Visual | CNN image explanations |

---

## Why Explainable AI Matters

- **Trust**: Users can understand and trust model decisions
- **Debugging**: Identify model biases and errors
- **Compliance**: Meet regulatory requirements (GDPR, etc.)
- **Improvement**: Guide model refinement

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
