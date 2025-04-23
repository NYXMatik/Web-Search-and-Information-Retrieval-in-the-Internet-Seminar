# Web Search and Information Retrieval in the Internet

This repository contains the seminar paper titled **"Web Search and Information Retrieval in the Internet"** by Mateusz Janowski, Louis Scherpereel, Luka Ćavar, and Filip Orlikowski. The document is a comprehensive study that explores the foundational and advanced components of information retrieval (IR) systems used by modern search engines.

## Abstract

The paper discusses the architecture and functionality of web search engines, focusing on the mechanisms behind crawling, indexing, and ranking. It elaborates on classical IR models like BM25 and the Vector Space Model (VSM), as well as neural-based methods like Dense Passage Retrieval (DPR) and hybrid approaches that combine lexical and semantic matching techniques.

The seminar aims to provide both theoretical grounding and technical insight into how large-scale web search infrastructures operate and how modern developments in machine learning and deep learning are shaping the future of information retrieval.

## Structure

The seminar is organized into the following major sections:

### 1. Introduction
- Motivates the need for efficient information retrieval in a digital world saturated with web data.
- Outlines the scope and goals of the paper.

### 2. Search Engine Architecture
- Overview of query processing pipelines.
- Description of search engine components: parsing, crawling, indexing, and ranking.

### 3. Crawling
- Technical breakdown of the crawling process including:
  - DNS resolution
  - HTTP requests/responses
  - URL frontier management
  - Filtering and politeness policies
  - Robots.txt and meta tag directives

### 4. Indexing
- Discussion on the construction of inverted indexes.
- Methods such as tokenization, stop-word removal, stemming, and lemmatization.
- TF-IDF and its role in improving document relevance.
- Practical indexing example with a travel website dataset.

### 5. Ranking Models
- In-depth coverage of:
  - **BM25**: A probabilistic ranking function based on TF, IDF, and document length normalization.
  - **Dense Passage Retrieval (DPR)**: A neural model using bi-encoder architectures and ANN search.
  - **BERT**: Deep contextual model for semantic understanding.
  - **Hybrid Models**: Fusion of lexical (BM25) and semantic (DPR/BERT) approaches.

### 6. Comparative Evaluation
- Comparative analysis of precision, recall, and F1-score using TREC datasets.
- Performance plots and tabular summaries.
- Key trade-offs between speed, semantic power, and explainability.

### 7. Conclusion
- Synthesis of insights on modern IR systems.
- Reflection on the technical, ethical, and societal dimensions of search engine design.

## Repository Contents

```
📁 seminar_B2.pdf       - Full seminar document (PDF)
📄 README.md            - Overview and structure description
```

## Usage

To read the seminar paper:

1. Download the `seminar_B2.pdf` file.
2. Use any PDF viewer to open and navigate through the document.

## License

This repository is intended for academic and educational purposes. Redistribution of the paper must be done with proper citation of the authors.

© 2025 Mateusz Janowski, Louis Scherpereel, Luka Ćavar, Filip Orlikowski. All rights reserved.
