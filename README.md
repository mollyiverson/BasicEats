# BasicEats
***
## Project Description
BasicEats is a recipe-sharing website that allows users to search for, view, and save recipes. Users can also generate a weekly shopping list for selected recipes.

## Installation

Clone repository
```bash
git clone https://github.com/skyllare/CSM_489.git
git clone git@github.com:skyllare/CSM_489.git
```
Open the repository and run this command in the terminal
```bash
npm install
```

Create  a profile for Spoonacular API to get an API key. 
[Spoonacular Sign Up](https://spoonacular.com/food-api/console#Dashboard)

Create a file named "config.js" in routes file and copy paste this code into it. Paste your Spoonacular API key.
```javascript
const MY_API_KEY = 'your key here';
module.exports = { MY_API_KEY};
```
Run this command in the terminal
```bash
nodemon ./bin/www
```
This will start the server and the web app will run on localhost:3000 in  your browser.
## Tools
We will use [Spoonacular's Food API](https://spoonacular.com/food-api) for the recipe data. We use HTML, CSS, and JavaScript to build the website interface.

This project is built using Express for node.js.

We utilize the MVC architectural pattern.

The data management for the project uses SQLite3 and Sequelize.

## Team Members
### Molly Iverson
GitHub: https://github.com/mollyiverson <br>
Email: molly.s.iverson@wsu.edu

### Skyllar Estill 
GitHub: https://github.com/skyllare <br>
Email: skyllar.estill@wsu.edu

### Caitlin Graves
GitHub: https://github.com/caitlingraves <br>
Email: caitlin.graves@wsu.edu

## Video Demo
https://youtu.be/vDrnPYFZPfI
