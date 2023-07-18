# nosql-challenge
Background: The UK Food Standards Agency evaluates various establishments across the United Kingdom, and assigns them a food hygiene rating.  This project focuses on evaluating UK Food Standards Agency ratings data for editors of a food magazine, Eat Safe, Love, which will assist journalists and food critics on deciding where to focus future articles. 

A repository labeled nosql-challenge contains the following files:
*    NoSQL_setup_starter.ipynb
*    NoSQL_setup_starter.ipynb
*   Resources folder
*  establishments.json
  
This project consists of several parts.
The first part requires the use of terminal or windows command line to import the establishments json file via mongoimport, which creates the database uk_food as well as the collection establishments.
Use terminal or windows command line to locate the directory with the folder labeled Resources.  Paste the following into terminal: mongoimport --type json -d uk_food  -c establishments --drop --jsonArray establishments.json

The second part uses file NoSQL_setup_starter.ipynb to import dependencies, create Mongo Client, import the uk_food database, and verify the collection named establishments is listed. The code includes the addition of a new restaurant, the removal of establishments in the Dover Local Authority, converts latitude and longitude from strings to decimal numbers, and converts the rating value from strings to integers.
The third part uses file NoSQL_setup_starter.ipynb to answer specific questions pertaining to the rating values, which will assist journalists and food critics on deciding where to focus future articles. Please note, the Rating Value refers to the overall rating decided by the Food Authority and ranges from one to five. The higher the value, the better the rating; however, the scores for Hygiene, Structural, and Confidence In Management work in reverse. This means, the higher the value, the worse the establishment is in these areas.

Resources used for this project include, Instructor assistance during Office Hours, course material, course provided starter-code, Study Group, MongoDB reference documents, Stack Overflow, Creative Commons, Towards Data Science, Tutorials Point, Geeks for Geeks, GitHub, and MongoDB Compass.
