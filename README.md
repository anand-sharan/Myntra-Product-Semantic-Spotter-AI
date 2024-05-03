
# Myntra Product Search App: Semantic Search and Question Answering for Fashion Products

## Overview

### Problem Statement
Customers often struggle to find specific fashion products they are looking for on e-commerce sites like Myntra due to limitations of keyword search.

### Solution
The Myntra Product Search App combines semantic search with AI to provide accurate and contextual results for user queries on the Myntra fashion product dataset.

### Core Features
- Data preprocessing from CSV files
- Semantic search to retrieve relevant product information
- AI-powered question answering to directly show relevant product details

### Benefits
- Enhances product discovery
- Saves time for customers
- Potentially increases sales by showing more relevant products

## Introduction

### Limitations of Keyword Search
Keyword search fails to capture user intent and struggles with synonym matching for fashion product attributes due to:

1. **Inability to Handle Synonyms and Paraphrasing**
2. **Lack of Context Understanding**
3. **Challenges with Multiword Phrases**
4. **No Query Expansion**
5. **No Handling of Misspellings or Typographic Errors**

### Objectives
- Preprocess the Myntra product dataset into an optimized format
- Implement semantic search for accurate product retrieval
- Develop natural language query capabilities with question answering

### Target Audience
Customers shopping for fashion products on Myntra or similar e-commerce platforms.

## Scope and Requirements

### Features
- **Data Preprocessing:** CSV parsing, text cleaning, column combining
- **Semantic Search:** LangChain, OpenAI embeddings, vector stores
- **Question Answering:** Integration with OpenAI language models
- **Web UI:** Gradio-based user interface

### Technology Stack
- **Python**
- **pandas, NumPy:** Data preprocessing
- **OpenAI:** Text embeddings, language models
- **LangChain:** Framework for semantic search & QA
- **Gradio:** Web UI creation
- **Other Libraries:** ast, pathlib, BeautifulSoup, PIL

## Challenges & Lessons Learned

### Challenges
- **Product Data Structure:** Handling varied product attributes
- **Query Understanding:** Mapping natural language to product specs
- **Result Ranking:** Providing most relevant products first
- **Performance:** Fast retrieval from large dataset

### Lessons Learned
- **Data Preprocessing:** Critical for usable vector embeddings
- **Query Adaptation:** Adjusting models to e-commerce domain
- **Embedding Storage:** Vector stores enable fast similarity search
- **UI/UX Design:** Intuitive display of text and visuals


## Conclusion

### Summary
- The Myntra Product Search App showcases the power of combining semantic search and natural language processing to enhance e-commerce product discovery.
- Key innovations include data preprocessing, embedding-based retrieval, and intuitive UI.

### Future Work
- Deep product attribute filtering
- Multimodal search with images
- Recommendations based on user history

