<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Building AI project

Final project for the Building AI course

## Summary

A smart recipe suggestion system that adapts meals to users' dietary needs (allergies, preferences, health goals) while maintaining flavor and nutrition. About 200 characters.
## Background
    32 million Americans have food allergies (FDA)

    60% struggle to find recipes matching their dietary needs

    Personal motivation: My gluten-free friend's cooking challenges

    Important for:

        Food safety

        Inclusive cooking

        Healthy eating

## How is it used?

        User inputs restrictions (vegan, nut-free, etc.)

    System suggests adapted recipes

    AI modifies ingredients while preserving taste

    Outputs shopping list and instructions

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
<img src="https://via.placeholder.com/600x400?text=Recipe+App+Mockup" width="500" alt="Recipe generator interface mockup">

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def adapt_recipe(original_recipe, restrictions):
    substitutions = find_substitutes(original_recipe, restrictions)
    adjusted_recipe = replace_ingredients(original_recipe, substitutions)
    return nutrition_check(adjusted_recipe)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

Data Source	Use Case
Recipe1M+	Recipe database
USDA FoodData	Nutrition facts
Allergen API	Safety checks
## Challenges

    Won't account for:

        Rare ingredient combinations

        Cultural taste preferences

    Limitations:

        Requires accurate user input

        Can't physically test recipes

    Ethical considerations:

        Allergy disclaimer needed

        Cultural appropriation in cuisine

## What next?

HPotential expansions:

    Integration with grocery delivery

    User taste preference learning

    Community recipe sharing
## Acknowledgments

    Inspired by Plant Jammer's AI chef

    Uses Food.com data under CC BY-NC-SA

    Recipe formatting based on RecipeML standard

    Special thanks to course mentors at University of Helsinki
* etc
