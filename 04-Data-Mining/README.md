# Data Mining

> Discovering patterns and insights from large datasets

---

## What You'll Learn

| Topic | Description |
|-------|-------------|
| **Word Embeddings** | Dense vector representations of words |
| **Word2Vec** | Skip-gram and CBOW architectures |
| **GloVe** | Global vectors for word representation |
| **Text Mining** | Extracting insights from text data |
| **Sentiment Analysis** | Classifying text by sentiment |

---

## Notebooks

| Notebook | Description |
|----------|-------------|
| `DM_Assignment3_Word_Embeddings.ipynb` | Word2Vec, CBOW, Skip-gram, GloVe comparison |
| `DM_Assignment4_Advanced_Mining.ipynb` | Advanced data mining techniques |
| `DM_Project_Text_Retrieval.ipynb` | Text retrieval with BERT and MonoT5 |
| `DM_IMDB_Sentiment_Analysis.ipynb` | Movie review sentiment classification |

---

## Quick Start

```python
from gensim.models import Word2Vec

# Train Word2Vec model
model = Word2Vec(
    sentences=corpus,
    vector_size=100,
    window=5,
    min_count=1,
    sg=1  # Skip-gram
)

# Find similar words
similar = model.wv.most_similar("python")
```

---

## Word Embedding Comparison

| Model | Approach | Strengths |
|-------|----------|-----------|
| **Word2Vec** | Local context | Fast training, good for small data |
| **GloVe** | Global statistics | Captures global patterns |
| **BERT** | Contextual | State-of-the-art, context-aware |

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
