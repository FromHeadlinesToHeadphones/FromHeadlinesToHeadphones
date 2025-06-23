# From Headlines to Headphones 🎧📰

**From Headlines to Headphones** investigates the interplay between global events and musical success by integrating and analyzing data from the [GDELT Project](https://www.gdeltproject.org/) and Spotify. This project leverages large-scale event data and music datasets to uncover patterns and correlations between news events and trends in popular music between 1990 and 2024.

Using modern data processing, natural language processing (NLP), and embedding techniques, the project extracts insights on how real-world events influence music popularity, genres, and artists over time.

![Jupyter Notebook Badge](https://img.shields.io/badge/Made_with-Jupyter-orange?logo=Jupyter)
![Python](https://img.shields.io/badge/python-3.9%20%7C%203.10-blue)
![Pandas Badge](https://img.shields.io/badge/Analysis-Pandas-yellowgreen)
[![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?logo=googlecolab&logoColor=white)](https://colab.research.google.com)
[![matplotlib](https://img.shields.io/badge/matplotlib-11557C?logo=matplotlib&logoColor=white)](https://matplotlib.org/)
[![seaborn](https://img.shields.io/badge/seaborn-1A5276?logo=seaborn&logoColor=white)](https://seaborn.pydata.org/)
[![BERT](https://img.shields.io/badge/BERT-FF6F61?logo=google&logoColor=white)](https://github.com/google-research/bert)
[![NLTK](https://img.shields.io/badge/NLTK-4B8BBE?logo=python&logoColor=white)](https://www.nltk.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)](https://numpy.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?logo=scikitlearn&logoColor=white)](https://scikit-learn.org/)

---

## Repository Structure

```
FromHeadlinesToHeadphones/
│
├── Jupyter Notebooks/               # Step-by-step analysis and data processing notebooks
│   ├── 0_Gdelt.ipynb               # Downloading and exploring GDELT data
│   ├── 0_HitsScraping.ipynb        # Scraping musical hits data
│   ├── 1_SpotifyDatasetCleaning.ipynb # Cleaning Spotify dataset
│   ├── 2_GDELT-Tokenization.ipynb  # Tokenizing and preprocessing GDELT events
│   ├── 2_LyricsPreprocessing.ipynb # Lyrics preprocessing
│   ├── 3_Embeddings.ipynb          # Generating and analyzing embeddings
│   ├── 3_Hits_df.ipynb             # Analysis of hit songs data
│   ├── 4_UniteEmbeddingBatches.ipynb # Combining embedding batches
│   ├── 5_Cosine_Similarity_*.ipynb # Cosine similarity calculations for clustering
│   ├── 6_EventsPerDate.ipynb       # Event counts by date
│   ├── 6_SongsPerDate.ipynb        # Songs counts by date
│   ├── 7_Events_Artists_Genres.ipynb # Linking events with artists and genres
│   ├── 7_Success_Events.ipynb      # Analysis of successful events
│   └── Experiment/                 # Additional experiments
│       ├── Experiment.ipynb
│       └── Untitled0.ipynb
│
├── LICENSE                        # Project license
├── Project Presentation.pdf      # Project presentation slides
└── README.md                     # This file
```

---

## Technologies Used

- 🐍 **Python 3.8+**: Core programming language for data processing and analysis.
- 📓 **Jupyter Notebooks**: Interactive environment for data exploration and visualization.
- 🐼 **Pandas**: Data manipulation and analysis.
- 🔗 **Requests**: HTTP requests for downloading datasets.
- 📦 **Zipfile & io**: Handling compressed data files.
- ☁️ **Google Colab**: Cloud-based execution environment (optional).
- 🧠 **NLP and Embeddings Libraries**: For text preprocessing and semantic analysis.

---

## Key Features

- Automated download and exploration of GDELT global event data.
- Cleaning and tokenization of large-scale textual data from both news events and song lyrics.
- Generation of embeddings to capture semantic relationships between events and music.
- Calculation of cosine similarity for clustering and pattern discovery.
- Temporal analysis linking events and musical trends by date.
- Comprehensive visualization and reporting via Jupyter notebooks and PDF.

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

## Getting Started

### Running the Project

Open the notebooks in Jupyter or upload them to Google Colab to execute step-by-step analyses.

---

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests to improve data processing, analysis, or documentation.

