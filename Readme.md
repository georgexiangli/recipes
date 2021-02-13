# Predicting Cuisines Using Ingredient List

## Study Description
Use recipe data from the [What Cooking? data set](https://www.kaggle.com/c/whats-cooking/overview) from Yummly and Kaggle to predict the cuisine of a recipe
* Data is arranged in JSON format with keys for recipe id, type of cuisine, and a variable list of ingredients
* An example data point looks like this
```JSON
 {
 "id": 24717,
 "cuisine": "indian",
 "ingredients": [
     "tumeric",
     "vegetable stock",
     "tomatoes",
     "garam masala",
     "naan",
     "red lentils",
     "red chili peppers",
     "onions",
     "spinach",
     "sweet potatoes"
 ]
 },
```
* Use CountVectorizer and TF-IDF to convert list of textual data to numeric features