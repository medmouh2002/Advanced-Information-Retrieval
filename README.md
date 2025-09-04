# 🔎 Advanced Information Retrieval

This repository focuses on **search engines, ranking, and text similarity**, with a practical mini-project implemented in Python.  

---

## 📂 Contents

### 1. Mini Project (`notebooks/mini_project.ipynb`)  
- Implemented an **information retrieval pipeline** for text documents.  
- Key steps:
  - Text preprocessing (tokenization, stopword removal, stemming/lemmatization)  
  - Index construction (Bag-of-Words, TF-IDF)  
  - Query similarity computation (cosine similarity)  
  - Ranking of documents based on relevance  
- Tools: Python, NLTK, Scikit-learn  

Example Output:  
| Query | Top Matching Documents |
|-------|--------------------------|
| "machine learning applications" | Doc2, Doc7, Doc10 |

---
### 2. TF-IDF Analysis (notebooks/TF-IDF.ipynb)
- Explored and implemented **text analysis techniques** using TF-IDF for **English and French** documents.  
- Key steps:
  - Text preprocessing (tokenization, stopword removal with NLTK)  
  - Frequency analysis (word counts, unique terms, most common words)  
  - Comparative analysis of TF-IDF descriptions between English & French  
  - Use of Python `collections.Counter` for term frequency tasks  
- Tools: Python, NLTK, Collections  
- Example: identified frequent terms after preprocessing (e.g., *“document”, “recherche”* in French; *“idf”, “document”* in English).  



## 🛠️ Tools & Libraries
- Python  
- NLTK  
- Scikit-learn  
- Pandas, NumPy  

---

## 🚀 Next Steps
- Extend retrieval with **word embeddings (Word2Vec, GloVe)**  
- Compare TF-IDF with **BM25 ranking**  
- Build a simple **search engine interface** using Streamlit  



