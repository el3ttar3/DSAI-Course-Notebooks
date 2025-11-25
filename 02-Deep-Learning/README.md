# Deep Learning

> Exploring neural network architectures for complex pattern recognition

---

## What You'll Learn

| Topic | Description |
|-------|-------------|
| **CNNs** | Convolutional Neural Networks for image analysis |
| **Autoencoders** | Unsupervised learning for compression and denoising |
| **Medical Imaging** | AI-powered diagnosis from medical scans |
| **Signal Processing** | Neural networks for signal denoising |
| **Object Detection** | Locating and classifying objects in images |

---

## Notebooks

| Notebook | Description |
|----------|-------------|
| `DL_Autoencoder_Signal_Denoising.ipynb` | TCN autoencoder for signal reconstruction |
| `DL_Brain_Tumor_CNN_Classification.ipynb` | CNN for brain tumor detection with XAI |
| `DL_Underwater_Object_Detection.ipynb` | Object detection in underwater imagery |

---

## Quick Start

```python
import tensorflow as tf
from tensorflow.keras import layers, Model

# Build a simple CNN
model = tf.keras.Sequential([
    layers.Conv2D(32, (3, 3), activation='relu', input_shape=(256, 256, 3)),
    layers.MaxPooling2D((2, 2)),
    layers.Conv2D(64, (3, 3), activation='relu'),
    layers.Flatten(),
    layers.Dense(10, activation='softmax')
])
```

---

## Highlighted Project: Brain Tumor Classification

This notebook implements:
- Custom CNN architecture for MRI classification
- Data augmentation for medical images
- LIME and GradCAM for model interpretability
- Performance metrics: **97% F1-Score**

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
