# Recipe Finder

A simple app which allows you to look for recipes. For the search you can either input main ingredient or dish. 

## You can customize your search with different parameters:

* Max number of ingredients
* Type of diet: “balanced”, “high-protein”, “high-fiber”, “low-fat”, “low-carb”, “low-sodium”
* Cusine type, such as "Indian", "Thai", "Italian"...
* Calories: you can set a range for the desired amount of calories. 
* Exclude any recipe which includes one or more ingredients
* Filter the search through one or more dietary requirements, such as "gluten-free", "sesame-free" or "kosher"
* Calories range per serving, for instance between "300" and "600". (calories are calculated according to each ingredient weight for each recipe)

## The search result with provide several recipes. For each recipe will be provided:
* ingredients list,
* ingredients images,
* total calories per serving
* recipe url link

## Updating ingredients amount
* You can decrease or increase the food quantity according to the servings. Since for each ingredient is provided its weight in grams and in its unit with a Regex it's possible to update the quantity accordingly.

## API
* Edamam API: [Documentation](https://developer.edamam.com/edamam-docs-recipe-api 'Edamam')

## You can sign up and retrieve your search history
* Authentication ???
* MongoDB or local DB ???

## Front-end
* React with context and hooks
* A main recipe context and a small one for alerts (no input, no recipe found, ecc)

## Testing
* Jest for unit test
* Enzyme for components




