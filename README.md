# spotify-song-popularity-analysis
Exploratory Data Analysis of Spotify tracks using Kaggle dataset, [30000 Spotify Songs](https://www.kaggle.com/datasets/joebeachcapital/30000-spotify-songs) by Joakim Arvidsson.

The goal of this project is to understand what makes songs popular on Spotify.
To do so, I performed exploratory data analysis (EDA), group comparisons, and a baseline regression model, using Python.

## Questions Answered
1. How are audio features distributed across songs?
2. Do audio features relate to popularity?
3. Are there differences in popularity across genres, keys, or modes?
4. What distinguishes the top 20% most popular songs?
5. Can popularity be predicted from audio features?

## Key Findings
- Popularity is heavily skewed towards low values.
- Popular songs are louder, slightly shorter, significantly less instrumental, and marginally more danceable and positive.
- Pop and Latin Genres have the highest average popularity.
- The average popularity was evenly spread for musical keys.
- Songs in Major keys are slightly more popular on average.
- Baseline regression explained only ~7% of variance, meaning audio features alone can't predict popularity.

## Technologies Used
- Python, pandas, matplotlib, seaborn, scikit-learn
- Jupyter Notebook

## Notebook
[Spotify_Data_Analysis.ipynb](Spotify_Data_Analysis.ipynb)
