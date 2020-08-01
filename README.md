# Recipe Finder

A simple app which allows you to look for recipes. For the search you can either input a main ingredient or a compglete dish

## You can customize your search with different parameters:

* Max number of ingredients
* Type of diet: “balanced”, “high-protein”, “high-fiber”, “low-fat”, “low-carb”, “low-sodium”.
* Cusine type, such as "Indian", "Thai", "Italian"...
* Calories: you can set a range for the desired amount of calories. 
* Exclude any recipe which includes one or more ingredients
* Filter the search through one or more dietary requirements, such as "gluten-free", "sesame-free" or "kosher".
* Calories range per serving, for instance between "300" and "600". (Each ingredient calories/unit value is provided by the API itself, therefore regardless from where the recipe is retrieved the amount of calories won't change)

## The search result with provide several recipes. For each recipe will be provided:
* ingredients list,
* ingredients images,
* total calories per serving
* recipe url link

## Updating ingredients amount
* You can decrease or increase the food quantity according to the servings. Regardless of the unit used each ingredient has gram weight: with a Regex it's possible to update the quantity accordingly

## API
* Edamam API:  [Documentation](https://developer.edamam.com/edamam-docs-recipe-api 'Edamam')

## You can sign up and retrieve your search history
* Authentication ???
* DB: MongoDB collection which will store user username email address,password and an array with the previous searches and its citeria. Previous searches will be available only if the user is logged in

## Front-end
* React with context and hooks
* A main recipe context and a small one for alerts (no input, no recipe found, ecc)

## Testing
* Jest for unit test
* Enzyme for components




