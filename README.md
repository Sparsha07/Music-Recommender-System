# 🎵 Music Recommendation System

A content-based music recommendation system built using Python. This project suggests similar songs based on a given track using cosine similarity of song features.

## 🔧 Features

- Content-based filtering using `sklearn`'s cosine similarity
- Fast song recommendations with precomputed similarity matrix
- Easy-to-understand codebase with clear separation of concerns

## 🧠 How It Works

1. Loads song metadata from `spotify_millsongdata`.
2. Extracts key textual features (e.g., genre, artist, mood, lyrics, tags).
3. Converts text data into numerical vectors using `CountVectorizer`.
4. Computes cosine similarity and stores it in `cosine_sim.pkl`.
5. When a song is input, returns the most similar songs.

## 🚀 Getting Started

### Prerequisites

- Python 3.10+
- Install dependencies:
```bash
pip install pandas scikit-learn joblib


Run the App::
python main.py
streamlit run main.py

![image](https://github.com/user-attachments/assets/6335d004-f40f-4389-8fea-e1977ce51042)






