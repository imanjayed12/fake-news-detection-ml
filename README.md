# Fake News Detection using TF-IDF and RSS Feeds

## Project Description
This project is a news verification system developed using Natural Language Processing techniques.  
It analyzes news titles using RSS feed data and TF-IDF similarity, combined with rule-based decision logic, to classify news as **Fake**, **Neutral**, or **Well-sourced**.

Unlike traditional machine learning classifiers, this system does not rely on model training. Instead, it verifies news credibility based on similarity with trusted news sources, source domain signals, and content recency.

---

## How It Works
1. Fetches recent news titles from trusted RSS feeds
2. Applies TF-IDF vectorization to compare similarity
3. Uses rule-based logic to determine credibility
4. Outputs a final label with explanation metrics

---

## How to Run the Project

### Option 1: Run using Google Colab (Recommended)
1. Open the notebook in Google Colab
2. Run all cells sequentially
3. Enter a news title when prompted
4. View the verification result

### Option 2: Run Locally
```bash
pip install -r requirements.txt
jupyter notebook
## Example Input & Output
**Input:Breaking: New policy announced affecting global markets

**Output:Label: Neutral
Similarity Score: 0.41
Matched Feed Title: Government discusses new economic measures

## Tools & Libraries Used
- Python
- Jupyter Notebook
- TF-IDF (scikit-learn)
- RSS Feed Parser (feedparser)
- Pandas
- NumPy
- NLTK

## Data Source
This project does not use a static dataset.  
It fetches real-time news titles from trusted RSS feeds to verify news authenticity dynamically.
