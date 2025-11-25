# Speech Processing

> Analyzing and processing audio signals for speech recognition

---

## What You'll Learn

| Topic | Description |
|-------|-------------|
| **Librosa** | Audio analysis library |
| **Audio Features** | MFCCs, spectrograms, mel-frequency |
| **Speech Recognition** | Converting speech to text |
| **Signal Processing** | Audio manipulation and filtering |

---

## Notebooks

| Notebook | Description |
|----------|-------------|
| `SPEECH_Recognition_Librosa.ipynb` | Speech recognition implementation with librosa |

---

## Quick Start

```python
import librosa
import librosa.display
import matplotlib.pyplot as plt

# Load audio file
y, sr = librosa.load('audio.wav')

# Extract MFCCs
mfccs = librosa.feature.mfcc(y=y, sr=sr, n_mfcc=13)

# Visualize
plt.figure(figsize=(10, 4))
librosa.display.specshow(mfccs, x_axis='time')
plt.colorbar()
plt.title('MFCC')
plt.show()
```

---

## Audio Features

| Feature | Description |
|---------|-------------|
| **MFCC** | Mel-frequency cepstral coefficients |
| **Spectrogram** | Frequency over time visualization |
| **Chroma** | Pitch class profiles |
| **Zero Crossing Rate** | Signal sign changes per frame |

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

