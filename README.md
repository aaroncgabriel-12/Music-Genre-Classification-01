# Music Genre Classification Using Machine Learning

## Project Overview

The goal of this project is to build a machine learning model capable of classifying songs into predefined genres based on their audio features. This project explores the use of data science and machine learning techniques to analyze and extract meaningful patterns from audio data, providing valuable insights into how distinct audio characteristics can define musical genres.

Music genre classification has significant applications in the real world, from improving music recommendation systems on streaming platforms to enhancing content organization in music libraries. By leveraging the GTZAN Music Genre Dataset and audio processing libraries like `librosa`, this project showcases the end-to-end process of data preprocessing, feature extraction, and predictive modeling.

The deliverables include a well-documented Jupyter Notebook, visualizations that highlight key insights, and a GitHub repository with all project files, making it accessible and replicable for further exploration.

## Key Objectives

- Analyze and preprocess audio data to extract relevant features such as tempo, spectral centroid, and MFCCs.
- Build and evaluate machine learning models to classify songs into genres with high accuracy.
- Visualize audio features and model performance to provide actionable insights.
- Demonstrate end-to-end data science workflow, from data collection to model deployment.

## Tools and Technologies

- **Programming Language:** Python
- **Libraries:** `librosa`, `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`
- **IDE/Environment:** Jupyter Notebook
- **Version Control:** GitHub

## Dataset Description

**Dataset:** GTZAN Music Genre Dataset

The dataset used for this project is the GTZAN Music Genre Dataset, a well-known benchmark dataset for music genre classification tasks. It contains a collection of audio tracks categorized into distinct musical genres, making it an excellent resource for analyzing audio features and building classification models.

**Link:** [GTZAN Music Genre Dataset](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification)

### Key Details

- **Source:** The dataset is publicly available and can be accessed via Kaggle or through other online repositories.
- **Size:** 1,000 audio tracks.
- **Format:** Each track is a 30-second audio file in `.wav` format.
- **Genres:** 10 genres, with 100 tracks each:
  - Blues
  - Classical
  - Country
  - Disco
  - Hip-Hop
  - Jazz
  - Metal
  - Pop
  - Reggae
  - Rock
- **Sample Rate:** 22,050 Hz (default for many audio processing libraries).

### Features

Raw audio data is used to extract features such as:

- **Tempo:** Measures the speed of the music.
- **Spectral Centroid:** Indicates the brightness of a sound.
- **Chroma Features:** Represents the energy distribution across 12 pitch classes.
- **Mel-Frequency Cepstral Coefficients (MFCCs):** Captures timbral aspects of audio.

### Challenges

- **Class Imbalance:** The dataset is evenly distributed across genres, making it easier to analyze but less representative of real-world distributions.
- **Noise:** Some tracks contain distortions or irrelevant sounds, which can affect model performance.
- **Dataset Age:** Created in 2002, the dataset may not fully represent modern music trends.

