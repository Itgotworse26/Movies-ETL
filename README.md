# Movies-ETL
Practice and Challenge Assignment for Module 8

## Background
Amazing Prime loves the dataset and wants to keep it updated on a daily basis. Britta needs your help to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. You’ll need to refactor the code from this module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

## Personal Comments on Database
While the code has been successfully refactored, once again, the time it takes to perform the actual ETL process is a large commitment. While it has little bearing on the actual process, it does make troubleshooting the ETL process a large undertaking. The biggest part of this project was making sure that not only was the data sorted and cleaned correctly, it was also exported at with the appropiate amount of data that the client had asked for. The last part was especially difficult, as I had to upload, drop the databases, and upload again to trouble shoot the database and make sure I had the appropiate number of datapoints from the movies and ratings tables.

Uploading to the repository was also difficult. The movies_metadata.csv and ratings.csv files were large files that were imposible to push to the Github repository conventionally, and the ratings.csv file could not be added at all. In order to sidestep this issue, I had to create a sample file for ratings.csv called ratings_sample.csv and compress movies_metadata.csv.