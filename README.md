![food critics](https://imgc.artprintimages.com/img/print/i-ll-have-the-vegan-new-yorker-cartoon_u-l-pgqpcj0.jpg?artHeight=900&artPerspective=n&artWidth=900&background=fbfbfb)
# Discovering the UK's Hidden Gems and Meh-dium Eateries: A Scrumptious Adventure!
Hey foodies! Join us on an exciting mission for Eat Safe, Love magazine, Performing ETL, creating MongoDB NoSQL database, and analyzing data to uncover the most intriguing and not-so-impressive restaurants across the  UK. Let's dig in! 🍔🍕🍰 11111111111111111

## Project Overview
This project involves two main parts: setting up a clean MongoDB database and conducting data analysis.


### Part 1: Set up the database
This part is about making a Mongo database from a [JSON file](https://github.com/MahsaBakhtiari/nosql-challenge/tree/main/Resources) and  ensuring it is cleaned, updated, and ready for further exploration. The code is available at [EatSafeLoveSetup.ipynb](https://github.com/MahsaBakhtiari/nosql-challenge/blob/main/EatSafeLoveSetup.ipynb).

### Part 2: Database Analysis, Your Culinary Treasure Map
The second part is about answering four questions that help to analyze the data. 

$𝑁𝑜𝑡𝑒$ :
  RatingValue refers to the overall rating the Food Authority decides and ranges from 1-5. The higher the value, the better the rating. The scores for Hygiene, Structural, and ConfidenceInManagement work in reverse. This means the higher the value, the worse the establishment is in these areas.
* Question one: Which establishments have a hygiene score equal to 20?
* Question two: Which establishments in London have a RatingValue greater than or equal to 4?
* Question three: What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the newly opened  trendy restaurant, "Penang Flavours"?
* How many establishments in each Local Authority area have a hygiene score 0? Sort the results from highest to lowest, and print out the top ten local authority areas.

The code, example documents from each answer, Pandas data frame of the results, and more are available at [EatSafeLoveAnalysis.ipynb](https://github.com/MahsaBakhtiari/nosql-challenge/blob/main/EatSafeLoveAnalysis.ipynb)

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvement, please submit a pull  request or open an issue on the GitHub repository.

## Resources
* [PyMongo Documentation](https://pymongo.readthedocs.io/en/stable/)
* [MongoDB Documentation](https://www.mongodb.com/docs/)








