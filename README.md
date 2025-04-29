# Spotify_EDA
Explore the 2024 most-streamed Spotify tracks through this data analysis project. The Jupyter notebook includes data cleaning, visualization, and insights into top artists, songs, and platform performance.
This project analyzes Spotify's most-streamed songs in 2024, alongside cross-platform performance metrics (YouTube, TikTok, Pandora, etc.). The goal is to uncover trends in music consumption, identify top-performing artists and tracks, and compare streaming platforms. Key insights include:
- **Top 10 most-streamed songs** (e.g., "Blinding Lights" by The Weeknd, "Shape of You" by Ed Sheeran).
- **Yearly streaming trends** (notable growth from 2015 onward, with anomalies in future years due to data errors).
- **Dominant artists** like Taylor Swift and Drake, who have the most songs in the dataset.
- **Platform dominance**: Spotify leads, followed by YouTube and TikTok.

## Dataset
The dataset, sourced from Kaggle, contains **4,600 tracks** with 29 features, including:
- Track metadata (artist, release date, track score).
- Streaming metrics (Spotify streams, YouTube views, TikTok engagement).
- Platform-specific stats.

## Key Features
- **Data Cleaning**: Handled missing values, converted date formats, and fixed numeric columns (e.g., commas in "Spotify Streams").
- **Exploratory Analysis**:
  - Top songs and artists by streams and track count.
  - Distribution of streams and track scores.
  - Yearly streaming trends (1997–2024).
- **Visualizations**:
  - Line plot for total streams per year.
  - Histogram of stream distribution.
  - Bar plots for top artists and platform comparisons.
  - Pair plots for feature correlations.
