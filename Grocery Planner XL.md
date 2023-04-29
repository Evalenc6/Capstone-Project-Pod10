# **Grocery Planner XL**

## Table of Contents

1. [App Overview](#App-Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
1. [Build Notes](#Build-Notes)

## App Overview

### Description 

**Description of your app** 
Contains a database of recipes for users to choose from, as well as a form to add their own recipes. Users can save any of these recipes to their own "recipe box" or favorites section. They can view information about how to make any given recipe, as well as the required ingredients. The user can create a meal plan for the week (or any determined amount of time) by adding in recipes for breakfast, lunch, dinner, etc. throughout the week. The app will then create a grocery shopping list for them that encompasses all the recipes.                             
                            

### App Evaluation

<!-- Evaluation of your app across the following attributes -->


**Category:** Food/Organizer
**Mobile:** This app is especially useful as a mobile app because when people are grocery shopping, they will have their phone on them to view their grocery list. This mobile ability is incredibly useful when going to a grocery store.
**Story:** This app will allow people to better plan their grocery trips and get everything they need for the week. It will be much easier to remember every single item they need for all the recipes they want to cook, and to not get items they don't need which would otherwise go bad.
**Market:** There is a very large audience for this app in the sense that anyone who cooks or grocery shops could make use of this app.
**Habit:** This app would most likely be used by someone weekly for shopping lists, and daily for recipe instructions.
**Scope:** The most challenging parts of this app would be making a personalized database for users and saving that data. Even without every last feature, this app would still be interesting and valuable to users. The scope is clearly defined because the problem is fully understood, meaning the solution of the app is also much easier understood.
## Product Spec

### 1. User Features (Required and Optional)

Required Features:

- ~Database of recipes from API~
- ~Ability to view instructions and ingredients from recipes~
- Filtered search through recipes

Stretch Features:

- Ability to favorite/save recipes
- Generate shopping list given recipes
- Form to write new recipes
- Display nutrient facts on recipes

### 2. Chosen API
**Edamam** - https://api.edamam.com/api/recipes/v2 
- Get Recipe Image
  - Users can see the image of what the food will look like.
- Get Ingredients
    - Users can select recipes to view the ingredients necessary to cook them. The app will also use this data behind the scenes to create the shopping list.
- Get Instructions
    - Users can select recipes to view the instructions to cook them. 
- Get Cuisine Type
    - Users will be able to see where the recipe originates from. They can use this category to filter the recipe search.
- Get Meal Type
    - Users will be able to check if this item is a breakfast, dinner, brunch, lunch/dinner, snack, and teatime. They can use this category to filter the recipe search.
- Get Dish Type
    - User can view the the specific category that the food sits under like cereal, drink, and more. They can use this category to filter the recipe search.

### 3. User Interaction


- Get Recipe Image
    - Users clicks on a specific recipe they like-
        - => Will be able to see the recipe image. 
- Get Ingredients
    - User will enter recipe name in search box, or filter the search by cuisine, meal, or dish type. 
        - => They will scroll through a view of the recipes given the search parameters. They can select any given recipe to view the ingredients.
- Get Instructions
    - User will enter recipe name in search box, or filter the search by cuisine, meal, or dish type. 
        - => They will scroll through a view of the recipes given the search parameters. They can select any given recipe to view the instructions.
- Get Cuisine Type
    - User can select cuisine type options from a multi-select menu. 
        - => The search shows results in accordance with this selection.
- Get Meal Type
    - User can select meal type options from a multi-select menu. 
        - => The search shows results in accordance with this selection.
- Get Dish Type
    - User can select dish type options from a multi-select menu. 
        - => The search shows results in accordance with this selection.

## Wireframes

<!-- Add picture of your hand sketched wireframes in this section -->
<img src="https://cdn.discordapp.com/attachments/1097666145751945277/1097692293382819972/IMG_5148.jpg" width=600>

### [BONUS] Digital Wireframes & Mockups

<img src="https://drive.google.com/uc?export=view&id=1Aaqgiv4rRAUJG-JKMmOfPIcnIB-md9Q3" width=600>

## Build Notes

Here's a place for any other notes on the app, it's creation 
process, or what you learned this unit!  

For Milestone 2, include **2+ GIFs** of the build process here!
<img src='http://i.imgur.com/Ir2Mwsc.gif' title='Video Demo' width='' alt='Video Demo' />


<img src='http://i.imgur.com/9Qika2H.gif' title='Video Demo' width='' alt='Video Demo' />
## License

Copyright **2023** **Evan Valencia, Ella Goode, Bilal Khan**

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
