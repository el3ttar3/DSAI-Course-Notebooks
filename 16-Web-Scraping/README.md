# Web Scraping

> Extracting data from websites using Python

---

## What You'll Learn

| Topic | Description |
|-------|-------------|
| **BeautifulSoup** | HTML/XML parsing library |
| **Requests** | HTTP library for Python |
| **Data Extraction** | Scraping structured data from web pages |
| **HTML Parsing** | Navigating DOM trees |

---

## Notebooks

| Notebook | Description |
|----------|-------------|
| `WEB_BeautifulSoup_BBC_Scraping.ipynb` | Web scraping BBC website with BeautifulSoup |

---

## Quick Start

```python
import requests
from bs4 import BeautifulSoup

# Fetch webpage
url = "https://example.com"
response = requests.get(url)

# Parse HTML
soup = BeautifulSoup(response.content, 'html.parser')

# Extract data
titles = soup.find_all('h1')
for title in titles:
    print(title.text)
```

---

## Ethical Considerations

- Always check `robots.txt` before scraping
- Respect rate limits and add delays
- Don't overload servers with requests
- Follow website terms of service

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

