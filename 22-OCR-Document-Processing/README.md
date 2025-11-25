# OCR and Document Processing

> Extracting text from images and documents using optical character recognition

---

## What You'll Learn

| Topic | Description |
|-------|-------------|
| **Tesseract OCR** | Open-source OCR engine |
| **Arabic OCR** | Processing Arabic text |
| **PDF Processing** | Extracting text from PDFs |
| **Image Preprocessing** | Improving OCR accuracy |

---

## Notebooks

| Notebook | Description |
|----------|-------------|
| `OCR_Arabic_Tesseract_PDF.ipynb` | Arabic text extraction from PDFs using Tesseract |

---

## Quick Start

```python
import pytesseract
from PIL import Image

# Install Arabic language pack
# !sudo apt install tesseract-ocr-ara

# Read image
image = Image.open('document.png')

# Extract text (Arabic)
text = pytesseract.image_to_string(image, lang='ara')
print(text)

# For better results, preprocess the image
import cv2
img = cv2.imread('document.png')
gray = cv2.cvtColor(img, cv2.COLOR_BGR2GRAY)
thresh = cv2.threshold(gray, 0, 255, cv2.THRESH_BINARY + cv2.THRESH_OTSU)[1]
```

---

## Supported Languages

- English (eng)
- Arabic (ara)
- French (fra)
- German (deu)
- And many more...

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

