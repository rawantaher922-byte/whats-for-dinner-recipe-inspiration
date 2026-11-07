# whats-for-dinner-recipe-inspiration

What's For Dinner is a simple, responsive recipe website that helps users decide what to cook. It displays random meal suggestions with detailed information about each recipe.

##  Features

- Display a random recipe when the website loads.
- Generate another random recipe using the Try Another Recipe button.
- Display recipe details, including:
  - Meal name and description.
  - Cuisine type and difficulty level.
  - Rating and reviews.
  - Preparation and cooking time.
  - Number of servings.
- Four recipe sections:
  - Ingredients.
  - Instructions.
  - Nutrition.
  - Chef's Tips.
- Display a warning when total preparation and cooking time exceeds 45 minutes.
- Responsive design for desktop and mobile devices.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Bootstrap 5
- Font Awesome

##  Project Structure

```
What's-For-Dinner/
│
├── index.html
│
├── css/
│   ├── all.min.css
│   ├── bootstrap.min.css
│   └── style.css
│
├── js/
│   ├── index.js
│   └── bootstrap.bundle.min.js
│
└── images/
    ├── Recipe Images
    └── avatar-4.jpg
```

##  Getting Started

1. Clone the repository.
2. Open the project folder in VS Code.
3. Make sure all CSS, JavaScript, and image files are in their correct folders.
4. Open `index.html` using Live Server.
5. Enjoy exploring different recipes!

## How It Works

1. Recipes are stored in a JavaScript array called `meals`.
2. The `getRandomMeal()` function selects a random recipe.
3. The `displayMeal()` function displays the selected recipe information dynamically.
4. Ingredients, instructions, nutrition facts, and tips are generated dynamically.
5. A preparation alert appears when the combined preparation and cooking time exceeds 45 minutes.
6. Clicking Try Another Recipe displays another random meal.

##  Available Recipes

The project includes recipes from different cuisines:

- Mexican
- American
- Italian
- Asian
- Greek
- Mediterranean
- French
- Thai
- Japanese
- Indian

## Future Improvements

- Add the ability to save favorite recipes.
- Implement recipe search and filtering.
- Add recipe history.
- Allow users to share recipes.
- Add more recipes and cuisines.

## Author

Developed as a front-end web development project.

What's For Dinner – Your daily meal inspiration!
