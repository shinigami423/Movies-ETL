# Movies-ETL

## Purpose
Amazing Prime would like us to create an Extract-Transform-Load function that takes in our data from Wikipedia, Kaggles, and MovieLens rating and loads the data into out PostgrSQL database. The function takes in new data, transforms them, loads it into a table on PostgreSQL.


## Programs
### Resources
We are given 3 resource files:
- movies_metadata.csv
- wikipedia-movies.json
- ratings.csv

### Functions
There are four functions we wrote to accomplish our goal:

**ETL_function_test.ipynb** - An ETL function that reads our three data files

**ETL_clean_wiki_movies.ipynb** - Extracts and Transforms the Wikipedia Data

**ETL_clean_kaggle_data.ipynb** - Extracts and Transforms the Kaggle Data then merges it with the transformed wikipedia data into a Pandas DataFrame

**ETL_create_database.ipynb** - Imports the DataFrame into a PostgreSQL movie database