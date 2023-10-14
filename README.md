<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Recipe App</title>
    <!-- Add your CSS and JavaScript links here -->
</head>
<body>
    <header>
        <h1>Welcome to My Recipe App</h1>
    </header>
    
    <main>
        <section id="recipe-list">
            <!-- Display a list of recipes here -->
        </section>
        
        <section id="recipe-details">
            <!-- Display the details of a selected recipe here -->
        </section>
        
        <section id="recipe-form">
            <h2>Add a New Recipe</h2>
            <form id="add-recipe-form" enctype="multipart/form-data">
                <label for="recipe-title">Recipe Title:</label>
                <input type="text" id="recipe-title" name="recipe-title" required>
                
                <label for="recipe-image">Recipe Image:</label>
                <input type="file" id="recipe-image" name="recipe-image" accept="image/*" required>
                
                <button type="submit">Add Recipe</button>
            </form>
        </section>
    </main>
    
    <footer>
        <p>&copy; 2023 My Recipe App</p>
    </footer>
    
    <!-- Add your JavaScript code here -->
</body>
</html>
