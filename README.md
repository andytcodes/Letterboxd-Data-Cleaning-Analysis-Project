# Letterboxd Data Cleaning & Analysis Project
Data retrieved [here.](https://www.kaggle.com/datasets/gsimonx37/letterboxd)

I have always loved & appreciated movies, so I have decided to dedicate one of my data analysis projects to movies!

## Cleaning the data
1. Filtering the data to find irregularities and fix tbem (where possible) / Removing unneeded data.
    -   Removing data with no ratings, year of release, or minute (runtime duration) data (this is usually because they are unreleased movies) For example, these two movies have yet to release and currently have no rating (Spider-Man: Beyond the Spider-Verse has no year of release, rating, or runtime duration):
      ![image](https://github.com/andytcodes/Letterboxd-Data-Cleaning-Analysis-Project/assets/66580474/32739422-efd7-48b4-bfec-d66bc935906d)
    - Reoving Tagline & Description Columns as these will not be needed.
2. TRIM name column.
3. Fix any spelling errors in name column.

