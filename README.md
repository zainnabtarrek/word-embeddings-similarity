# word-embeddings-similarity

This repository (`word-embeddings-similarity`) explores word embeddings and various document similarity measures using Python. It generates word embeddings for a set of documents and then calculates the similarity between these documents using Cosine Similarity, Jaccard Similarity, and Euclidean Distance.

## Overview

This project provides a practical introduction to word embeddings and document similarity measures, crucial concepts in Natural Language Processing (NLP). Word embeddings represent words as numerical vectors capturing semantic relationships. Document similarity measures quantify the similarity between documents based on these embeddings.

## Task Breakdown

The project is divided into two main tasks:

**Task 1: Word Embeddings**

1.  **Tokenization:** Text is broken down into individual words or tokens using the `nltk` library.
2.  **Word Embedding Generation:** Word embeddings are generated using `gensim`'s Word2Vec model.

**Task 2: Document Similarity Measures**

Document similarity is calculated using the following measures:

*   **Cosine Similarity:** Measures the cosine of the angle between document vectors.
*   **Jaccard Similarity:** Computes the intersection over the union of word sets.
*   **Euclidean Distance:** Measures the straight-line distance between document vectors.

## Dataset

This project works with text data. Place your text files (one document per file) in the `data/` directory. The included notebook uses `Liverpool.txt` and `Computer_Science.txt` as example data.

## Analysis

The Jupyter Notebook provides an analysis of the results obtained from different similarity measures, discussing the strengths and limitations of each. The analysis includes:

*   Comparison of similarity scores obtained by each method.
*   Discussion of the impact of preprocessing steps.
*   Interpretation of the visualizations (heatmaps and MDS plot).

## Bonus: Visualization

The project includes visualizations of document similarities using:

*   **Heatmaps:** To show pairwise similarity scores between sentences.
*   **Multidimensional Scaling (MDS):** To project document vectors into a 2D space for visualization.

## Team Members

*   Zainab Tarek
*   Abdelfattah Mohamed
