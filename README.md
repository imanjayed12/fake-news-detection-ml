# Fake News Detection System

This project is a **News Detection system** that analyzes online news titles using **Natural Language Processing (NLP)**, **RSS feed analysis**, and **TF‑IDF similarity** combined with **rule‑based decision logic** to identify whether a news item is **Fake**, **Neutral**, or **Well‑sourced**.

---

## Project Overview

With the rapid spread of misinformation online, verifying the authenticity of news has become increasingly important.  
This project compares a given news title against real-time RSS news feeds and applies similarity scoring and heuristic rules to determine credibility.

The system does **not rely on a trained ML classifier**, instead it focuses on **content similarity, source presence, and recency** for transparent and explainable results.

---

## Features

- RSS feed based real-time news fetching  
- Text preprocessing using NLP techniques  
- TF‑IDF vectorization for similarity measurement  
- Rule‑based decision logic for classification  
- Outputs Fake / Neutral / Well‑sourced label  
- Displays matched source, similarity score, and recency  

---

## Technologies Used

- Python  
- Pandas & NumPy  
- Scikit‑learn (TF‑IDF Vectorizer)  
- NLTK  
- Feedparser  
- Google Colab / Jupyter Notebook  

---

## How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/Fake-News-Detection-With-Machine-Learning.git
