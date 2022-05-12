# Movies-ETL

## Objective

To create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. This will require refactoring the code from the module to create one function that takes in three files: Wikipedia data, Kaggle metadata, and MovieLens rating data and perform ETL processes by adding the data to a PostgreSQL database.

## Deliverables

* Deliverable 1: Write an ETL Function to Read Three Data Files
* Deliverable 2: Extract and Transform the Wikipedia Data
* Deliverable 3: Extract and Transform the Kaggle data
* Deliverable 4: Create the Movie Database

## Results

All code for the above deliverables is located in one file, step by step.
[Click here to review Python Script](WikiMovieKaggleDataCombined.ipynb)

### Database Output
![Movie Data Imported](/Resources/movies_query.PNG)

![Movie Ratings Imported](/Resources/ratings_query.PNG)

## Resources

Two large resource files were omitted from this project because of size limitations. The original data sources can be downloaded from:
* [The Movie Database (TMDb)](https://www.themoviedb.org/) ... movies_metadata.csv
* [Kaggle zip file](https://www.kaggle.com/rounakbanik/the-movies-dataset/download) contains ratings.csv
