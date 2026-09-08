# Spotify Music Analysis

Exploratory data analysis of 30,000+ Spotify songs, examining audio features, genre differences, and trends over time.

## Dataset

The dataset contains 32,833 tracks with 23 features, including audio characteristics (danceability, energy, loudness, acousticness, valence, tempo) and metadata (genre, playlist, popularity, release date).

Source: [TidyTuesday Spotify Songs Dataset](https://github.com/rfordatascience/tidytuesday/blob/master/data/2020/2020-01-21/readme.md)

## Project Structure

- `spotify_music_analysis.ipynb` — Main notebook with data wrangling, EDA, and visualizations
- `.gitignore` — Excludes Jupyter checkpoint files

## Analysis Steps

1. **Data Wrangling**: Handled missing values, converted dates, removed duplicate tracks
2. **Correlation Analysis**: Examined relationships between audio features
3. **Genre Comparison**: Compared average audio features across genres
4. **Trend Analysis**: Tracked how audio features changed from 1980-2020
5. **Popularity Analysis**: Explored the relationship between audio features and track popularity

## Key Findings

- Energy and loudness are strongly positively correlated, while energy and acousticness are strongly negatively correlated.
- EDM has the highest average energy; rap has the highest average danceability.
- Audio features like energy and acousticness show opposing trends over time.
- Pop tracks tend to have the highest popularity among genres.

## Tools Used

Python, Pandas, Matplotlib, Seaborn