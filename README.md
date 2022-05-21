# Movies-ETL

## Objective

To create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. This will require refactoring the code from the module to create one function that takes in three files: Wikipedia data, Kaggle metadata, and MovieLens rating data and perform ETL processes by adding the data to a PostgreSQL database.

## Deliverables

* Deliverable 1: [Write an ETL Function to Read Three Data Files](ETL_function_test.ipynb)
* Deliverable 2: [Extract and Transform the Wikipedia Data](ETL_clean_wiki_movies.ipynb)
* Deliverable 3: [Extract and Transform the Kaggle data](ETL_clean_kaggle_data.ipynb)
* Deliverable 4: [Create the Movie Database](ETL_create_database.ipynb)

## Results
![Movies with Ratings Dataframe Screenshot](/images/movies_with_ratings.PNG)

![Movies Dataframe Screenshot](/images/movies_df.PNG)

[Database import statistics](/images/db_import_stats.PNG)

### Database Output
![Movie Data Imported](/Resources/movies_query.PNG)

![Movie Ratings Imported](/Resources/ratings_query.PNG)

## Resources

Two large resource files were omitted from this project because of size limitations. The original data sources can be downloaded from:
* [The Movie Database (TMDb)](https://www.themoviedb.org/) ... movies_metadata.csv
* [Kaggle zip file](https://www.kaggle.com/rounakbanik/the-movies-dataset/download) contains ratings.csv
