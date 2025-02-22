# nosql-challenge

The NoSQL_setup.ipynb sets up and updates the database. The NoSQL_analysis.ipynb queries relevant information for analyses and converts results into Pandas DataFrame. The data provided in the establishments.json file was imported using Terminal with mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json.

**Exploratory Analysis**:

Which establishments have a hygiene score equal to 20?
There are 41 establishments with a hygiene score of 20 from the uk_food dataset.

Which establishments in London have a RatingValue greater than or equal to 4?
There are 33 establishments in London that have a RatingValue greater than or equal to 4 from the uk_food dataset.

What are the top 5 establishments with a RatingValue rating value of '5', sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
The top 5 establishments with a RatingValue of '5' sorted by lowest hygiene score nearest to "Penang Flavours" are: "Volunteer", "Plumstead Manor Nursery", "Atlantic Fish Bar", "Iceland", and "Howe and Co Fish and Chips - Van 17".

How many establishments in each Local Authority area have a hygiene score of 0?
There are 55 rows in the DataFrame.
