# Django-LiveProject
## Introduction
For two weeks in my time at The Tech Academy, I worked along side my peers as a team to create a website for hobbies using Django. The team took part in daily stand-ups to prepare for our sprints. We used DevOps to stay on track and organized. I better understood version control and learned new front end and back end skills while working in a team. We each created webpages for a hobby we each chose. I created my webpages around recipes. The two weeks were broken down into stories that each individual did at their own pace. The stories starting out had to do with the front end and UX, while the later stories revolved around gathering user input and backend database work as well as integrating an API to my portion of the site.
## Overview
First few stories were just to get a basic look for the pages and to get them linked to the main page. 
![Image of Home Page](https://github.com/glarson1/Django-LiveProject/blob/main/Images/Home.PNG)

Created a base.html containing my navbar and footer that was used for all other pages.
![Image of Home Page](https://github.com/glarson1/Django-LiveProject/blob/main/Images/Recipes_Base.PNG)

Next was to create models and view functions that will be called upon to gather input from a user and store that in a database. I wanted mine to be setup where the user enters in their recipes into a form where it will be saved and could be called upon later to edit or delete.

![Image of Home Page](https://github.com/glarson1/Django-LiveProject/blob/main/Images/Models.PNG)

The views.py:

![Image of Home Page](https://github.com/glarson1/Django-LiveProject/blob/main/Images/ViewsCreate.PNG)
![Image of Home Page](https://github.com/glarson1/Django-LiveProject/blob/main/Images/ViewsSeeDetailsEdit.PNG)
![Image of Home Page](https://github.com/glarson1/Django-LiveProject/blob/main/Images/ViewsDelete.PNG)

Added the functions to the html pages so the user could use them:

![Image of Home Page](https://github.com/glarson1/Django-LiveProject/blob/main/Images/RecipeHTMLCreateSee.PNG)

So the user see this:

![Image of Home Page](https://github.com/glarson1/Django-LiveProject/blob/main/Images/CreatingRecipe.PNG)
![Image of Home Page](https://github.com/glarson1/Django-LiveProject/blob/main/Images/ViewRecipesPage.PNG)
![Image of Home Page](https://github.com/glarson1/Django-LiveProject/blob/main/Images/AreYouSure.PNG)

## Adding an API
My favorite part of the project was finding an API online that fit my topic and placing it in my section of the project. This challenged me and coming out of it I feel like I gained a lot of knowledge of something I had no experience in previous.

I started by creating a form underneath the form I used for all of the prior work that I named APIForm.

![Image of Home Page](https://github.com/glarson1/Django-LiveProject/blob/main/Images/Forms.PNG)

Then I created a function in views.py that I made sure to "over comment" since this was me doing something I never have before.

![Image of Home Page](https://github.com/glarson1/Django-LiveProject/blob/main/Images/APIFunction.PNG)

And finally this is what the user sees. They enter in a food they would a recipe of and the forms below fill with multiple different recipes along with cooking time, servings, and a link to the source of the recipe where the user can continue their search of what they wish to cook.

![Image of Home Page](https://github.com/glarson1/Django-LiveProject/blob/main/Images/APIPage.PNG)











