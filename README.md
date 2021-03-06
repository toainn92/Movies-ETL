# Movies-ETL

## Purpose 
The purpose of this analysis is to create an automated pipeline that takes in new data, performs the appropraite transformations, and loads the data into existing tables. 

### Results
In this module, the code was refactored to take in three files -Wikpedia data, Kaggle metadata, and the MovieLens rating data- and performs the ETL process by adding the data to a PostgreSQL database.

Below are the number of movies query and numbers of ratings query found when added to PostgreSQL:


![](Resources/movies_query.PNG)

![](Resources/ratings_query.PNG)


### Conclusion
In this analysis, an ETL function was written to read the three data files. Then, the data was extracted and transformed from the Wikipedia data and Kaggle Data. Lastly, a movie data base was created on PostgreSQL.
