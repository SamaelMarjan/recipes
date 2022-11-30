# Getting Started with Create React App

# At first create a folder called React-recipe

# To add react files in the recipe f0lder we need to do
    - npx create-react-app ./

# We will use version control using git-
    - git init
    - git add .
    - git commit -m "first commit"
    - git branch -M main
    - git remote add origin https://github.com/SamaelMarjan/recipes.git
    - git push -u origin main

# to pust the existing repository 
    - git add .
    - git commit -m ""
    - git branch -M main
    - git push -u origin main

# After the installation of react we will delete all the unneccecery file from src folder
    - App.css
    - App.test.js
    - logo.svg
    - reportWebVitals.js
    - setupTests.js

# And then we need to add a component folder and create a file called -
    - Meal.jsx

# Create another file
    - MealItem.jsx
    # to show meal items from api and import MealItem.jsx to App.jsx

    - RecipeIndex.jsx 

    # in RecipeIndex.jsx we have to create a array of data called alpha and map it

    const alpha = [
    'A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z'
    ]

    then -

    return (
    <>
    {
      alpha.map(item => {
        return (
          <div className='numBox' key={num++}>
            <h3>{item}</h3>
          </div>
        );
      })
    }
    </>
    );
