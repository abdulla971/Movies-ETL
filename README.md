# Movies-ETL
This project introduced us to the concepts of Extract, Transform and Load process, known as ETL. The data from Wikipedia, Kaggle and aggregated ratings were utilized to create a movie database from a clean dataset for fictional Hackathon. To perform this, the ETL process is used to extract the Wikipedia and Kaggle data from the files, and next transform the dataset via cleaning the rows and formatting datatypes, performing joins, and lastly loading the cleaned dataset into PostgreSQL database.

## Overview
In this project we created an automated pipeline that inputs new data, from Wikipedia data, Kaggle metadata and the MovieLens rating data, for the Amazing Prime Hackathon. Then we transformed the data and loaded the data into an existing PostgreSQL database.

For this analysis we performed the following:
1. Write an ETL function to read three data files,
2. Extract and transform the Wikipedia data,
3. Extract and transform the Kaggle and rating data,
4. Load the data to a PostgreSQL Movie Database.
	
The ETL process is performed using four Jupiter notebook and details are provided below:

## Results

### First, the ETL function is written to read three data files

