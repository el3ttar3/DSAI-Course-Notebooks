# Information Retrieval

> Building intelligent search systems that understand and retrieve relevant information

---

## What You'll Learn

| Topic | Description |
|-------|-------------|
| **PyTerrier** | Python framework for information retrieval experiments |
| **TF-IDF** | Term frequency-inverse document frequency ranking |
| **Document Indexing** | Creating searchable document collections |
| **Text Preprocessing** | Tokenization, stemming, stopword removal |
| **BERT Ranking** | Neural ranking with transformer models |

---

## Notebooks

| Notebook | Description |
|----------|-------------|
| `IR_Lab3_PyTerrier_Text_Indexing.ipynb` | Document indexing and retrieval with PyTerrier |
| `IR_BERT_CV_Ranking_System.ipynb` | CV/Resume ranking using BERT embeddings |

---

## Quick Start

```python
# Install PyTerrier
!pip install python-terrier

# Initialize
import pyterrier as pt
pt.init()

# Index documents
indexer = pt.DFIndexer("./myIndex")
index_ref = indexer.index(docs_df['text'], docs_df['docno'])
```

---

## Key Concepts

- **Inverted Index**: Maps terms to documents containing them
- **BM25**: Probabilistic ranking function
- **Query Processing**: Transforming user queries for retrieval
- **Relevance Scoring**: Calculating document-query similarity

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
