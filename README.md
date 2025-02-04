# Letterboxd Data Cleaning & Analysis Project
Data retrieved [here.](https://www.kaggle.com/datasets/gsimonx37/letterboxd)

I have always loved & appreciated movies & television, so I have decided to dedicate one of my data analysis projects to one of my favorite hobbies!

## Dashboard
![letterboxd-dashboard](https://github.com/andytcodes/Letterboxd-Data-Cleaning-Analysis-Project/assets/66580474/3488ef7c-f9f6-412f-babc-1e17e098c5b1)

## Cleaning the data
1. Import data using UTF-8 Encoding so that name data won't be messy.
   ![image](https://github.com/andytcodes/Letterboxd-Data-Cleaning-Analysis-Project/assets/66580474/89058e78-915f-4d62-bc97-e5cfea70e83d)
2. Create a seperate working sheet for rating, year of release, and minute data (separate sheets as we want to maximize the data for each category).
3. Filtering the data to find irregularities and fix tbem (where possible) / Removing unneeded data.
    -   Removing data with no ratings, year of release, or minute (runtime duration) data (this is usually because they are unreleased movies, and if they're not, we will remove them anyway as it is incomplete data) For example, these two movies have yet to release and currently have no rating (Spider-Man: Beyond the Spider-Verse has no year of release, rating, or runtime duration):
      ![image](https://github.com/andytcodes/Letterboxd-Data-Cleaning-Analysis-Project/assets/66580474/32739422-efd7-48b4-bfec-d66bc935906d)
    - Removing Tagline & Description Columns as these will not be needed for our purposes.
4. Used the following Excel function to get the decade the films released in: `=CONCATENATE(LEFT(C2, 3), "0s")` ![image](https://github.com/andytcodes/Letterboxd-Data-Cleaning-Analysis-Project/assets/66580474/e9c089b8-0c5c-42fe-913b-cd8d10454706)

## Pivot Tables
- Average Movie/Show Length By Decade. ![image](https://github.com/andytcodes/Letterboxd-Data-Cleaning-Analysis-Project/assets/66580474/36283fa8-daf2-4688-ba17-8dedaab9ce64) 
- Number of Movies/Shows Released By Decade ![image](https://github.com/andytcodes/Letterboxd-Data-Cleaning-Analysis-Project/assets/66580474/482e1088-d550-40c6-8585-f1a1bdc99011)
- Average Rating By Decade <br>
  ![image](https://github.com/andytcodes/Letterboxd-Data-Cleaning-Analysis-Project/assets/66580474/412f48c2-d933-4492-be63-c20b4d032994)
- Top 10 Movies/Shows By Rating ![image](https://github.com/andytcodes/Letterboxd-Data-Cleaning-Analysis-Project/assets/66580474/b680bdfa-0301-406d-aa6c-44d7c96f36b7)


