# Recipe Rhapsody 📖

## Interactive Recipe Book Project

This project is a simple interactive recipe book built using HTML, CSS, and JavaScript. It allows you to browse through a collection of recipes, search for specific ones, and filter them by category.


## Features

-   **Recipe Display:** Recipes are presented in an appealing book-like format, with images, ingredients, and instructions.
-   **Search Functionality:** Users can search for recipes by name or ingredients using the search bar.
-   **Category Filtering:** Recipes can be filtered by category using the dropdown menu.
-   **Add New Recipe:** You can easily add new recipes to the collection with their details.

## File Structure

-   **`index.html`**: Main HTML structure for displaying recipes.
-   **`index1.html`**: HTML structure for adding new recipe.
-   **`styles.css`**: CSS styles for the webpage layout and appearance.
-   **`scripts.js`**: JavaScript code to handle recipe display, search, filtering, and adding new recipes.

## Functionality

### `index.html`

-   Displays the recipe book header with search bar, category filter, and "Add Recipe" button.
-   Fetches recipes data from `recipes` array in `scripts.js`.
-   Dynamically generates HTML for each recipe and displays it within the "book" section.

### `index1.html`

-   Has a form with input fields for recipe name, image URL, ingredients, instructions, and category.
-   The form data is submitted to the `addRecipe` function in `scripts.js`.

### `scripts.js`

-   Contains an array `recipes` to store recipe data.
-   `displayRecipes()` function renders recipes on the page.
-   `searchRecipes()` function filters recipes based on search term.
-   `filterByCategory()` function filters recipes based on selected category.
-   `addRecipe()` function adds a new recipe to the `recipes` array.

## How to Use

1.  Open `index.html` in a web browser.
2.  Browse through the recipes displayed.
3.  Use the search bar to find specific recipes.
4.  Select a category from the dropdown to filter recipes.
5.  Click "Add Recipe" to add a new recipe to the collection.

## Future Improvements

-   Implement local storage to save recipes persistently.
-   Add more recipe categories.
-   Allow users to edit or delete existing recipes.
-   Improve the user interface with more interactive elements.

Feel free to contribute to this project by forking the repository and adding your own features or improvements. Let's create a delightful recipe-sharing experience! 🎉
