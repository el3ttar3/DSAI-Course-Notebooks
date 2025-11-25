# NLP and Chatbots

> Building intelligent conversational systems that understand and generate human language

---

## What You'll Learn

| Topic | Description |
|-------|-------------|
| **BERT** | Bidirectional Encoder Representations |
| **Siamese Networks** | Similarity learning for Q&A matching |
| **Chatbots** | Conversational AI systems |
| **Semantic Similarity** | Measuring text relatedness |
| **Arabic NLP** | Processing Arabic language text |

---

## Notebooks

| Notebook | Description |
|----------|-------------|
| `NLP_Chatbot_Siamese_Network.ipynb` | Q&A chatbot using Siamese networks |
| `NLP_Chatbot_Zewail_City_QA.ipynb` | University FAQ chatbot system |
| `NLP_YouTube_Video_Analysis.ipynb` | Video transcript NLP pipeline |
| `NLP_Arabic_Grading_System.ipynb` | Arabic text grading with NLP |
| `NLP_Arabic_Grading_System_V2.ipynb` | Enhanced Arabic grading system |

---

## Quick Start

```python
from sentence_transformers import SentenceTransformer
from sklearn.metrics.pairwise import cosine_similarity

# Load pre-trained model
model = SentenceTransformer('all-MiniLM-L6-v2')

# Encode sentences
embeddings = model.encode([
    "What is machine learning?",
    "How does ML work?"
])

# Calculate similarity
similarity = cosine_similarity([embeddings[0]], [embeddings[1]])
```

---

## Chatbot Architecture

```
User Query → Preprocessing → Embedding → Similarity Matching → Response
                                              ↓
                                    Knowledge Base
```

---

## Featured Project: Zewail City Q&A Bot

A chatbot that answers questions about:
- Admission requirements
- Available programs
- Tuition fees
- Campus facilities

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
