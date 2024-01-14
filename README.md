# 12.NoSQL-challenge

Module 12 Challenge - Evaluation of food ratings data

The following Jupyter Notebooks were used in this Challenge:
- NoSQL_setup_starter.ipynb
- NoSQL_analysis_starter.ipynb

The task was split into 3 parts:
1. Database and Jupyter Notebook Set Up
I began by importing the data provided in the establishments.json file from the terminal. 
Then I imported the necessary libraries, created an instance of Mongo Client, and assigned variables to the database and collection. 

2. Part 2: Update the Database
This included adding a new restaurant "Penang Flavours" to the collection, as well as removing any establishments within the Dover Local Authority from the database.
Finally, I converted the latitude and longitude values to decimal numbers and the rating values to integers.

3. Part 3: Exploratory Analysis
In this section, I carried out analysis to answer the following 4 questions:
 a. Which establishments have a hygiene score equal to 20?
 b. Which establishments in London have a rating value greater than or equal to 4?
 c. What are the top 5 establishments with a rating value of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
 d. How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.


