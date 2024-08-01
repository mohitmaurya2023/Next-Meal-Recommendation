# Hello are you working on this project.



# Next Meal Recommendation
Final project for the Building AI course

## Summary
Picking among favorite food is hard and balance the nutrients value of everyday meal is even more difficult. So this AI project would be about taking the preference of the users and nutrient value of the food and suggest a healthy meal. 

## Background

Food is one of the one of the most important thing in people life. It is the source of energy, nutrients for any living creature to sustain and growth. But people only eats food that suits their preference and it has to be easy to obtain since spending 10 hours to cook something is not suitable for everyone. But tasty and simple to obtain may not be a good choice when it comes to balance diet, so most people will neglect one or two categories (nutrients probably will be the least importance) when it comes to food. By using AI to understand the preference of the users and generate a list of dishes is probably possible and filter it again based on the nutrients value will give a healthy and tasty option for every meal.

## How is it used?

It probably is a solution for everyone, especially someone with limited time to consider and cooking their own meal. Users can use the suggestion as ease or change it to suit their preference even more, and if cooking is a problem, ordering the suggestion food is also a pretty good idea. Users must take into account that AI is not perfect and the suggestion may not be perfectly balance in nutrients or suit your preference.


## Data sources and AI methods

Data source: The data will be input by users when starting to use the service. It is also possible to import such data from food delivery service used by the user. The information about the nutrients value of each dish can be obtain through service like ReciPal API or Edamam Nutrition Analysis API. The recommendation balance diet can be obtain through Edamam Diet Recommendations API. 
AI Methods: since nutrients value and taste can be categories and turn to numerical value, Linear regression and Logistics regression could be enough but using neural network may give even better result.
## Challenges

Each dish has a unique taste, the preference of users may result in incorrect suggestion since it will taste differently when cook by different person. Another challenge is that food with necessary nutrients may not fit in the user's preference at all, for example a kid only likes fastfood and hate vegetable, it would be impossible to suggest a balance diet in this case. 
## What next?

Probably someone with enough time to plan the whole thing, build a model, and test it out.

## Acknowledgments
* Thanks the [Elements of AI](https://www.elementsofai.com/) Team for the knowledge and reason to think about this project :)
* The idea mentions some API service which probably have no problem with copyright :)
