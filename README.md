# FromHeadlinesToHeadphones
This project is a multidimensional analysis of economic success, thematic trends, and cultural impact for song between 1990 - 2024

# 🧠 Song & Event Semantic Overlap

This project is a multidimensional analysis of economic success, thematic trends, and cultural impact for songs between 1990 and 2024. In particular, it investigates whether there is any semantic overlap between popular song lyrics and historical global events, using modern Natural Language Processing (NLP) techniques.

---

## 🎯 Project Goals

- Explore the dominant topics in song lyrics across different decades.
- Compare those topics to the thematic content of global events recorded in the GDELT database.
- Apply tokenization and embedding models to transform texts into comparable vectors.
- Reflect critically on the expected low overlap between cultural and political narratives.

---

## 📚 Datasets Used

- Lyrics dataset taken from Kaggle: [🎧 500K+ Spotify Songs with Lyrics,Emotions & More](https://www.kaggle.com/datasets/notshrirang/spotify-million-song-dataset)

- Historical global events taken from [GDELT](https://www.gdeltproject.org/data.html): [Events GDELT 1.0](http://data.gdeltproject.org/events/index.html)

- Popularity part of the study taken from [Media Traffic](http://www.mediatraffic.de/)
  
---

## 🧪 Methodology

The project is divided into the following stages:

1. **Data Collection**
   - Lyrics dataset containing thousands of songs with metadata (title, artist, release year, lyrics).
   - GDELT dataset filtered to include major political, social, and economic events.

2. **Preprocessing**
   - Cleaning and tokenization of both datasets.
   - Removing stopwords and punctuation signs.

3. **Embedding**
   - Generating semantic vector representations using BERT.
   - One vector per song / event.

4. **Similarity Analysis**
   - Comparing vectors using cosine similarity.
   - Aggregated comparisons by year and decade.

5. **Topic Exploration**
   - Identifying most frequent tokens and patterns in both datasets.
   - Qualitative interpretation of overlaps and differences.

---

## 📁 Project Structure

project-root/

├── notebooks/        # Main procedures and analysis in Colab Notebooks

├── src/              # Helper functions for preprocessing and embeddings

├── data/             # Raw and processed data (not tracked in Git)

├── outputs/          # Visualizations and result tables

├── .gitignore

└── README.md


---

## 🛠 Technologies

- Python (Pandas, NumPy, Scikit-learn)
- Google Colab
- NLP: Tokenization (nltk) and Embeddings (BERT)
- GDELT Event Database
- Visualization: Matplotlib, Seaborn
