# What's for Dinner? 

### Abstract:
* This app allows a user to pick from 4 meal categories(side, main dish, dessert, entire meal) and display a suggested recipe by clicking the button labeled "Let's Cook!". A random recipe is then displayed in the box with the cookpot image. Once a recipe is displayed the user has the option to delete the recipe from the category list by clicking on the "Yuck! Delete! button". By doing so, this will delete the recipe from the category array. Now, when the user clicks the "Let's Cook" button the recipe that was deleted will no longer display as an option. 


### Installation Instructions:
* github repository link- https://github.com/dustingouner/whats-for-dinner
* SSH clone link- git@github.com:dustingouner/whats-for-dinner.git


### Preview of App:

### Preview of App:
![What's For Dinner gif](https://user-images.githubusercontent.com/117230717/219880318-4bcd6218-f7c7-403c-b4c9-797f9bb38376.gif)

### Context:
* This project was assigned to me during my third week of Mod 1 at Turing on Tuesday, February 14th. It was due by Sunday, February 19th. I was able to complete the project by Friday, February 17th. I spent about 4 hours each day from Tuesday to Friday working on the project. 


### Contributors:
* Dustin Gouner-  https://github.com/dustingouner


### Learning Goals:
* - Gain experience building an application that utilizes HTML, CSS and JavaScript
  - Write HTML and CSS to match a provided comp
  - Understand how to listen to and respond to user events
  - Individualize programming skill set


### Wins + Challenges:
* During this project I was able to improve on my css skills using flex-box. Making sure everything on the page matched the comp can always be a challenge when only provided a photo of what the site should look like. I utilized the dev tools to visually inspect where all elements lined up and to make sure the final result matched the comp provided. At first my displayRecipe function was extremely long and I was using innerHTML to manipulate the DOM in order to display the random recipe for each category. I was able to refactor my code by adding a global variable to store the current recipe displayed and then reassigning the innerText of h2 element based on the radio button selected.  

