# 🎵 Spotify Tracks EDA

This project is an exploratory data analysis (EDA) of a dataset containing information about the top 2000 Spotify tracks from 2000 to 2019. The dataset includes track metadata and audio features such as danceability, energy, tempo, and more.

## 📂 Dataset Overview
- **Rows:** ~2000 songs
- **Columns:** artist, song, year, popularity, danceability, energy, tempo, genre, and other audio features.
- Source: Spotify Charts / Audio Features

## 🛠️ Steps Performed

### 1. Data Cleaning
- Removed duplicates based on `song` and `artist`.
- Handled missing or unknown genres.
- Standardized text columns (e.g., lowercase, stripping spaces).
- Separated multi-genre columns into individual genres.

### 2. Univariate Analysis
- Boxplots for numeric features to inspect distributions and outliers.

### 3. Bivariate Analysis
- Scatter plots between `popularity` and key features like `danceability`, `energy`, and `tempo`.

### 4. Correlation Matrix
- Heatmap of numerical features to explore correlations.

### 5. Genre Insights
- Bar plot to visualize the frequency of each individual genre.

### 6. Trends Over Time
- Line plots showing how popularity, danceability, and energy evolved over the years.

## 📊 Libraries Used
- pandas
- numpy
- seaborn
- matplotlib
- plotly
