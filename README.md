# Creating-A-Movies-Database

# Business Problem
To produce a MySQL database on Movies from a subset of IMDB's publicly available dataset. Ultimately, the database will be used to analyze what makes a movie successful and provide recommendations to the stakeholder on how to make a successful movie.

The stakeholder only wants to include information for movies based on the following specifications:

- Include only movies that were released in the United States.
- Include only movies that were released 2000 - 2022 (startYear >=2000 and startYear<=2022)
- Include only full-length movies (titleType = "movie").
- Exclude movies that are missing genre or runtime.
- Include only fictional genres (where Genres does not include "Documentary".)

# Files Description
1) Create-Movies-Database.sql - SQL codes that create the Movies database and the corresponding tables: 'genres', 'ratings', 'title_basics', and 'title_genre'. This should be run first to create the database before uploading the data entries using Python (sqlalchemy).
2) ERD-Movies.mwb - the database model
3) Creating_Movie_Database.ipynb - Python notebook containing lines of code that pre-processes/transforms the dataset and inserts the dataset entries into the respective MySQL database tables.
4) Exploratory Data Analysis.ipynb - another Python code that contains lines of code that perform Exploratory Data Analysis on the dataset. Run this after 'Creating_Movie_Database.ipynb'
