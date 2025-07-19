# 🎵 Lyrics-Based Music Recommendation System

This project builds a content-based music recommendation system using lyrics analysis. It leverages natural language processing and machine learning to suggest similar tracks based on the lyrics of a given song.

## 🔧 Tech Stack
- Python
- Pandas
- Scikit-learn
- Matplotlib
- TF-IDF Vectorizer
- Cosine Similarity

## 📂 Dataset
- [Music Dataset (1950-2019)](https://www.kaggle.com/datasets/music-dataset-1950-to-2019)

## 🚀 Features
- Loads and processes a large music dataset with lyrics.
- Uses TF-IDF to convert lyrics into numerical features.
- Calculates cosine similarity between songs.
- Recommends similar tracks based on lyrical similarity.
- Visualizes the top 10 recommended tracks using `matplotlib`.

## 📊 How It Works
1. **Preprocessing**: Missing lyrics are filled with empty strings.
2. **Vectorization**: Lyrics are transformed using TF-IDF.
3. **Similarity Matrix**: Cosine similarity computes pairwise similarity.
4. **Recommendation**:
   - Pass any song title into the `music_recommendation(title)` function.
   - It prints and visualizes the top similar tracks.

## 🖼️ Sample Visualization

![Top 10 recommended songs](path_or_url_to_image)

## 💡 Usage

```python
# Recommend similar tracks to 'patricia'
music_recommendation('patricia')
