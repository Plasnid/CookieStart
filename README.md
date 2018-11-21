# cookies
a data driven cookie recipe

# final assignment:
 Perform each section in order.

## Part 1:
### Tasks in index.html
1. add proper tabbing to the html page(tabbing)
2. link to the reset css(linking css files)
3. link to the style.css
4. import the fonts amatic SC and Josefin Sans from fonts.google.com(importing fonts)
5. link the cookieBuilder.js script at the bottom of the body section(importing scripts)

## Part 2: 
### Tasks in data.json
1. convert the contents of data.json to proper json format(understanding json structure)

## Part 3:
### Tasks in js/cookieBuilder.js
1. Make a new instance of CookieBuilder.  Call it theCookie
2. Inside of the window.onLoad function add a console.log and add a message of “program running”
3. Call the init function of theCookie.
4. Add a console log to the init function of theCookie
5. Call gatherData from inside the init function
6. In the gatherData function use the fetch command to get data.json
7. In the last then of gatherData add a console.log and have it display resp
8. Just underneath your console log, call populateData and send it resp
9. Go to the populateData function and set the value of this.cookieIngredients to resp.cookieIngredients
10. In the same way as you set cookieIngredients, set the value for this.cookieSteps
11. In the same way as you set cookieIngredients, set the value for this.notes
12. In the same way as you set cookieIngredients, set the value for this.title
13. In the same way as you set cookieIngredients, set the value for this.descriptor
14. In the same way as you set cookieIngredients, set the value for this.prepTime
15. In the same way as you set cookieIngredients, set the value for this.difficultyLevel
16. In setTitle use querySelector to find the h1 tag and set its innerText to this.title
17. In setTitle use querySelector to find header>h2 tag and set its innerText to this.descriptor
18. In the listIngredients function make a variable called ingredientsList and have it store the result of a query selector looking for #ingredients >ul
19. In the listIngredients function uncomment the forEach and add a console log describing what it is doing
20. In the listSteps function inside the forEach, create a variable called stepItem that creates an li tag(eg. document.createElement("li”))
21. In the listSteps function inside the forEach, make the inner text of stepItem equal to stp
22. In the listSteps function inside the forEach, append stepItem to the end of stepsList
23. Add a console log to the listNotes function describing what it does.
24. In the setDifficultyLevel function set the contents of the inner html to match the following format-> Difficulty: difficultyLevelHere

## Part 4:
### Tasks in scr/scss/style.scss
Import all of the partials and mixins:
1. mixins/_textshadow.scss
2. partials/_colors.scss
3. partials/_fontSizes.scss
4. partials/_body.scss
5. partials/_header.scss
6. partials/_main.scss

## Bonus:  
For an additional 20%, extend the data object to contain a second cookie recipe.  Add buttons and events to allow the user to switch between recipes.

## Evaluation Breakdown:
| Percentage | Task |
|-----------:|:-----|
| 10% | Apropriate Tabbing |
| 10% | Linkage to CSS Files |
| 5% | Linkage To Google Fonts |
| 5% | Linkage to Javascript |
| 15% | Correctly formatted JSON File |
|  5% | Correct Instancing of a Javascript ES5 Function Class |
| 10% | Console Logs as required by instructions |
| 10% | Data loading from JSON file |
| 25% | Population of page content from Data |
| 5% | Use of Template Literals |
