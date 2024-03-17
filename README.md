# nosql-challenge
Module 12 Challenge - No SQL
## Overview
- In this project, I analyzed data from the UK Food Standards Agency to evaluate various food establishments across the United Kingdom. The aim was to assist the editors of a food magazine, Eat Safe, Love, in making informed decisions regarding future articles and food critiques. The analysis involved database setup, data updates, and exploratory analysis using MongoDB and Jupyter Notebooks.
 
## Part 1: Jupyter Notebook Setup
### Filename: NoSQL_setup.ipymb
- Imported establishments.json into MongoDB and named the database uk_food with the collection establishments.
- Confirmed the database and collection setup.
- Created an instance of the MongoDB client.
- Displayed one document from the establishments collection.
- Assigned the establishments collection to a variable for further use.

## Part 2: Database Updates
### Filename: NoSQL_setup.ipymb
- Added information for the new restaurant "Penang Flavours" to the database.
- Found and updated the BusinessTypeID for "Restaurant/Cafe/Canteen".
- Removed establishments within the Dover Local Authority.
- Converted string values to numbers for latitude, longitude, and RatingValue fields.

## Part 3: Exploratory Analysis
### Filename: NoSQL_analysis.ipymb
- Explored the database to answer specific questions.
- Identified establishments with a hygiene score of 20.
- Determined establishments in London with a RatingValue greater than or equal to 4.
- Found the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to "Penang Flavours".
- Calculated the number of establishments in each Local Authority area with a hygiene score of 0, sorted from highest to lowest.

## Requirements/Technologies Used:
- Python
- MongoDB
- PyMongo
- Jupyter Notebook

## Contact
For any questions, suggestions, or feedback, please feel free to contact Anna Ramer.
