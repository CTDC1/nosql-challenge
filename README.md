# NOSQL-Challenge

This repository contains an analysis of the rating data that the UK Food Standards Agency uses to evaluate establishments in the UK. They mainly consider them on hygiene and give them a rating. 

This repository contains Multiple stages:

1)	Setting up a database and Jupiter notebook. 
  
    a.	The database is called ‘uk_food,’ and the collection is called ‘establishments. 

  	b.	Using Mongo, we created an instance and then confirmed the names of the database and collection and one document.

3)	Updating the database with a new establishment called ‘Penang Flavors.’ 

  	  a.	Once Penang Flavors is assigned a ‘BusinessTypeId,’ then establishments in Dover are removed.

5)	Analyzing the data based on the following prompts. 

  	a.	display the number of documents contained in the result.

  	b.	Which establishments have a hygiene score equal to 20?

  	c.	What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavors"?

  	d.	How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest and print out the top ten local authority        areas.

