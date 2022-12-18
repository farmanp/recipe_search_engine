# Recipe Search Engine
Recipe Search Engine built by me, pairing assistance by ChatGPT!


### TODO: MOVE THIS 
## Data points 

These fields are from the "Weekly Basket" payload: 

`id`: This could be a unique identifier for each recipe.
`servings`: This field indicates the number of servings for each recipe, which could be useful for determining portion sizes.
`display_status`: This field indicates the current status of the recipe (e.g. "scheduled", "shipped"). This information could be used to filter recipes based on their availability.
`skipped`: This field indicates whether the recipe has been skipped. This could be useful for filtering out recipes that users no longer want to receive.
`skippable`: This field indicates whether a recipe can be skipped. This could be useful for indicating whether a recipe is optional or mandatory.
`meal_plan`: This field indicates whether the recipe is part of a meal plan. This information could be used to filter recipes by meal plan type.
`scheduled`: This field indicates whether the recipe is scheduled for delivery. This could be used to filter recipes by delivery status.
`shipped`: This field indicates whether the recipe has been shipped. This could be used to filter recipes by shipping status.
menu: This field contains information about the menu for the recipe, including the recipe's name and description. This information could be used to search for specific recipes based on their name or ingredients.
`meals`: This field contains information about the individual meals included in the recipe. This could be useful for displaying information about the ingredients and instructions for each recipe.

id: This could be a unique identifier for each recipe.
title: This field contains the name of the recipe. This could be used to search for specific recipes or to display the name of the recipe in search results.
subtitle: This field contains a short description of the recipe. This could be used to provide additional context about the recipe or to help users decide whether to select the recipe.
description: This field contains a longer description of the recipe. This could be used to provide more detailed information about the recipe or to highlight special features of the recipe.
photo: This field contains a URL for a photo of the recipe. This could be used to display an image of the recipe in search results or on the recipe page.
url: This field contains a URL for the recipe. This could be used to link to the recipe page or to display a link to the recipe in search results.
tags: This field contains tags or keywords associated with the recipe. This information could be used to filter recipes based on specific ingredients or characteristics.
serving_size: This field indicates the recommended serving size for the recipe. This could be useful for determining portion sizes.
menu_category: This field indicates the category that the recipe belongs to (e.g. "dinner", "lunch"). This could be used to filter recipes by category or to display the category of the recipe in search results.
base_servings: This field indicates the default number of servings for the recipe. This could be useful for determining portion sizes or for allowing users to adjust the serving size of the recipe.
unit_amount: This field indicates the amount of a particular ingredient in the recipe (e.g. "1 cup"). This could be used to display the ingredients list for the recipe.
unit_name: This field indicates the unit of measurement for the ingredient (e.g. "cup"). This could be used to display the ingredients list for the recipe.
display_unit: This field indicates the unit of measurement for the recipe (e.g. "serving"). This could be used to display the serving size for the recipe.
calories, carbs, fat, protein, sodium: These fields contain information about the nutritional content of the recipe. This information could be used to filter recipes based on nutritional content or to display nutritional information for the recipe.
nutrition_facts: This field contains a list of nutrition facts for the recipe. This could be used to display detailed nutritional information for the recipe.
prep_minutes: This field indicates the estimated preparation time for the recipe. This could be used to filter recipes based on preparation time or to display the preparation time for the recipe.
max_cook_time: This field indicates the maximum cooking time for the recipe. This could be used to filter recipes based on cooking time or to display the cooking time for the recipe.
difficulty_level, difficulty_level_number, spice_level, spice_level_number: These fields indicate the difficulty or spiciness level of the recipe. This information could be used to filter recipes based on difficulty or spiciness level, or to display this information for the recipe.
days_cook_by: This field indicates the recommended date for cooking the recipe. This could be used to filter recipes based on the recommended cooking date
supply_photo: This field contains a URL for a photo of the supplies needed for the recipe. This could be used to display an image of the supplies in the recipe instructions.
pdf_url: This field contains a URL for a PDF of the recipe. This could be used to link to a printable version of the recipe.
meal_addon_id, meal_addon_name, meal_addon_display_name: These fields contain information about any additional meals or ingredients included with the recipe. This information could be used to display the contents of the recipe or to allow users to add additional items to the recipe.
primary_label, secondary_label, primary_label_data: These fields contain information about labels or tags associated with the recipe (e.g. "vegetarian", "gluten-free"). This information could be used to filter recipes based on specific dietary preferences or to display the labels for the recipe.
a_la_carte: This field indicates whether the recipe is available as an a la carte item. This could be used to filter recipes by availability.
is_donation: This field indicates whether the recipe is a donation item. This could be used to filter recipes by donation status.
before_you_cook_instructions, before_you_cook_instructions_markdown, did_you_know, did_you_know_markdown, what_you_need, utensils, chef, ingredients, instructions, customize_it_instructions: These fields contain information about the recipe, including instructions, ingredients, and additional notes. This information could be used to display the details of the recipe or to allow users to customize the recipe.
rectangular_meal_badge, meal_badge: These fields contain information about badges or labels associated with the recipe (e.g. "new", "customizable"). This information could be used to display the badges for the recipe or to filter recipes by badge type.
avoidances, intolerances: These fields contain information about ingredients that should be avoided or are intolerant to. This information could be used to filter recipes based on specific dietary restrictions or to display the ingredients to be avoided in the recipe.
meal_concept: This field indicates the concept or theme of the recipe (e.g. "comfort food"). This could be used to filter recipes by theme or to display the theme of the recipe in search results.
base_price_cents, total_price_with_upcharge, total_price_without_upcharge: These fields contain information about the price of the recipe. This information could be used to display the price of the recipe or to allow users to compare prices of different recipes.
sold_out: This field indicates whether the recipe is sold out. This could be used to filter recipes by availability.
price_promotion: This field contains information about any promotions or discounts available for the recipe. This information could be used to display the promotional pricing for the recipe.
price: This field contains the current price of the recipe. This could be used to display the price of the recipe.
opt_ins: This field contains information about any opt-in options available for the recipe (e.g. "add a side"). This information could be used to allow users
servings: This field indicates the number of servings for the recipe. This could be useful for determining portion sizes or for allowing users to adjust the serving size of the recipe.

