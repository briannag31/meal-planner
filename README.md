# meal-planner

# Meal Planner

#### Project 2 by Brianna Gaines

**Summary**

| Field | Detail |
|-------|--------|
| Project Name | Meal Planner|
| Description | This app will allow the user to create a weekly meal plan. They can add details of their meal for each day, see a week view, click on the meals to see the details, add new meals, and edit or delete existing meals. |
| Trello Board | https://trello.com/b/7TKDl9CA/seirfx-project-2 |


## Technologies to be used:

- HTML
- CSS
- JavaScript
- JQuery
- Google Fonts
- EJS
- Method Override
- Heroku
- Express


## Intended Routes
- get "/meal-planner" => renders home page
- get "/weekly-meals" => renders index of meals for the week
- get "/daily-meal/:id" => renders individual meal
- get "/new" => renders page with form to add a new meal
- get "/daily-meal/:id/edit" => renders page to edit individual meal
- put "/daily-meal/:id" => updates meal from edits and redirects to /daily-meal
- delete "/daily-meal/:id" => deletes meal
- post "/weekly-meals" => redirects to index of meals with added meal from the form on the new page

## Model
Meals{  
    id: Object,  
    day: string,  
    name: string,  
    description: string,  
    ingredients: array,  
    time: number,  
}

## Work Plan
- By EOD Saturday, my goal is to have all of my code finished
- By EOD Tuesday, my goal is to have all of my styling finished and deployed to Heroku

## Bonus Features (if time)

- add an API call to add a search for recipes
    - make the ingredient list in those recipes clickable to be added to a shopping list
- add authentication
