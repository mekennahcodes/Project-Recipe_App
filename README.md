# Recipe CRUD App

## Overview

Welcome to the Recipe CRUD App project! In this project, you will build a Recipe tracking app that allows users to add new recipes, display a list of recipes, and delete recipes from the list. The app also includes styling as provided in the mockup.

## Project Structure

The project comes with starter code that you can use as a foundation. Your main tasks include adding handlers and logic to make the app functional.

### Specific Instructions

1. **Displaying Recipes:**
   - The app should display a recipe's name, cuisine, photo, ingredients, preparation instructions, and a delete button.
   - At least one additional component should be created and used by the RecipeList component.

2. **Form for Adding Recipes:**
   - To create a recipe entry, the app should have a form with input fields for the name of the dish, the cuisine it belongs to, and a URL pointing to a picture of the dish.
   - Use `<textarea>` for the ingredients and preparation.
   - For the tests to pass, use the following names for your inputs: `<input name="name">`, `<input name="cuisine">`, `<input name="photo">`, `<textarea name="ingredients">`, and `<textarea name="preparation">`.
   - The new recipe should be added to the end of the list of recipes.

3. **Deleting Recipes:**
   - Clicking the delete button in the recipe list should remove the entire row/recipe.
   - For the tests to pass, ensure that the delete button has `name="delete"` (e.g., `<button name="delete" onClick={deleteRecipe}>Delete</button>`).

### Styling Instructions

1. **Header Styling:**
   - The "Delicious Food Recipes" text surrounded by an `<h1>` tag should use the 'Playfair Display SC' font (already imported in App.css).
   - Center the text and set its size to 64px.

2. **Table Styling:**
   - Use `nth-child` to set the width of the columns.
   - Set the width for the preparation and ingredients columns to 30%.
   - Set the width for the rest of the columns to 10%.
   - Use `nth-child(odd)` to set the zebra striping color pattern for the rows in the `tbody`. Feel free to choose a suitable color.

3. **Scrollbars and Image Styling:**
   - Display a scrollbar for the preparation and ingredient columns if the text is too long.
   - Use the predefined `content_td` class and `<p>` tag to wrap the text (e.g., `<td className="content_td"><p>{recipe.ingredients}</p></td>`).
   - Use the `object-fit` property to scale-down images and set the image width and height to 100%.

## Success Criteria

### Functionality
- Users can create a recipe entry.
- Users can read the list of recipes, with the new recipe added to the end.
- Users can delete a recipe.

### CSS Styling
- CSS is used to make the app look like the provided mockup.

### React Code Organization
- The app uses multiple components that work well together.
- Recipe data is contained in the state.

### General Code Organization
- Minimal code duplication.

Feel free to reach out if you have any questions or need further assistance. Happy coding!
