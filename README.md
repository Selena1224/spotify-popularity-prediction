# spotify-popularity-prediction
Predicting Spotify track popularity using machine learning and marketing analytics techniques.

# Spotify Popularity Prediction and Music Segmentation Analysis

Predicting Spotify track popularity using machine learning and marketing analytics techniques.

## Project Overview

This project examines how Spotify audio features influence song popularity and demonstrates how predictive analytics can support marketing and promotional decision-making in the music streaming industry.

Using more than 230,000 Spotify tracks, this project:

- Identifies key drivers of song popularity
- Predicts whether a song is likely to become a hit
- Segments tracks into meaningful audience groups
- Generates actionable marketing insights for streaming platforms and record labels

## Business Objectives

- Predict song popularity using audio characteristics
- Classify songs as Hit or Non-Hit
- Identify audience segments through clustering
- Support playlist placement and promotional decisions

## Dataset

Dataset: Ultimate Spotify Tracks DB (Kaggle)

- 232,725 Spotify tracks
- 18 variables
- Final cleaned dataset: 176,773 tracks

Features include:

- Danceability
- Energy
- Loudness
- Acousticness
- Valence
- Speechiness
- Tempo
- Popularity

## Technologies

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Methodology

### Exploratory Data Analysis
- Popularity distribution analysis
- Correlation analysis
- Feature relationship exploration

### Multiple Linear Regression
Predict continuous popularity scores and identify the strongest popularity drivers.

### Logistic Regression
Classify songs as Hit or Non-Hit to support promotion and release decisions.

### K-Means Clustering
Segment tracks based on shared audio characteristics for targeted marketing strategies.

## Key Findings

- Danceability, energy, and loudness consistently emerged as the strongest positive indicators of popularity.
- Song popularity is influenced by combinations of audio features rather than a single variable.
- Distinct song segments were identified that may support targeted marketing strategies.

## Repository Structure

```text
spotify-popularity-prediction/
│
├── Spotify_Analysis.ipynb
├── Predicting Spotify Track Popularity Using Marketing Analytics and Machine Learning.pdf
├── Marketing Analytics Final Presentation - Spotify.pdf
├── README.md
└── images/
```

## Future Enhancements

Potential improvements include incorporating:

- Playlist inclusion data
- Artist popularity metrics
- Social media engagement
- Release timing information
- Listener demographic data
