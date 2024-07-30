# nosql-challenge for the magazine EatSaveLove

The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. They have been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles. I have decided to use use PyMongo, through a Mongo client, to analyze food establishments across the UK for Hygiene ratings. The process included updating a database and exploratory analysis.

## Contents of Repository
Resources folder:
  - establishments.json file
NoSQL_analysis_meaparisio.ipynb
NoSQL_EatSafeLove.ipynb

The database was updated by inserting a .json file document into the collection of data, and then cleaned up through the CRUD process. The rRating values were updated and certain field types were converted appropriately. Queries were performed to confirm updates as well as to query for certain criteria to answer the questions listed below. The results for each analysis used to answer the questions were converted to a Pandas DataFrame. The magazine editors have notified me that they are requesting some modifications for the database before I can perform any queries or analysis for them. An exciting new Halal restaurant just opened in Greenwich, but hasn't been rated yet. So the magazine has asked me to include it in my analysis, so I added restaurant to the database, and then updated it accordingly.

## Analysis answered the following questions:
1)  Which establishments have a hygiene score equal to 20?
2)  Which establishments in London have a RatingValue greater than or equal to 4?
3)  What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
4)  How many establishments in each Local Authority area have a hygiene score of 0? I sorted the results from highest to lowest, and then printed out the top ten local authority areas.

# References
UK Food Standards AgencyLinks to an external site. (2022). UK food hygiene rating data API. https://ratings.food.gov.uk/open-data/en-GBLinks to an external site.. Contains public sector information licensed under the Open Government Licence v3.0Links to an external site.
