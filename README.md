Project: Recipes

 The Odin Project
 Foundation

 <https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/recipes>

Assignment
Iteration 1: Initial structure

    Within the odin-recipes directory, create an index.html file.
    Fill it out with the usual boilerplate HTML and add an h1 heading “Odin Recipes” to the body.

Iteration 2: Recipe Page

    Create a new directory within the odin-recipes directory and name it recipes.
    Create a new HTML file within the recipes directory and name it after the recipe it will contain. For example lasagna.html. You can use the name of your favorite dish or, if you need some inspiration, you can find a recipe to use here.
    For now, just include an h1 heading with the recipe’s name as its content.
    Back in the index.html file, add a link to the recipe page you just created. The text of the link should again be the recipe name.

Iteration 3: Recipe Page Content

The recipe page should have the following content:

    An image of the finished dish under the h1 heading that you added earlier. You can find images of the dish on google or the site recipe site we linked to earlier.
    Under the image, it should have an appropriately sized “Description” heading followed by a paragraph or two describing the recipe.
    Under the description, add an “Ingredients” heading followed by an unordered list of the ingredients needed for the recipe.
    Finally, under the ingredients list, add a “Steps” heading followed by an ordered list of the steps needed for making the dish.

Iteration 4: Add More Recipes

    Add two more recipes with identical page structures to the recipe page you’ve already created.
    Don’t forget to link to the new recipes on the index page. Also, consider putting all the links in an unordered list so they aren’t all on one line.

Project Skyfold

odin-recipes
    images
        recipe-1.jpg
        recipe-1.jpg
        recipe-1.jpg
    recipes
        recipe-1.html
        recipe-2.html
        recipe-3.html
index.html

Boilerplates

index.html

!doctype
html
    head
        title Odin Recipes
        meta charset UTF-8 lang=EN
    body
        h1 Odin Recipes
        img odin-recipes-header.jpg
        p Page Description
        h2 List of links
        ul
            li a recipes\recipe-1.html
            li a recipes\recipe-2.html
            li a recipes\recipe-3.html
        ul
            li a english-lang
            li a russian-lang
        a #top

recipe-#.html

!doctype
html
    head
        title Recipe # Title
        meta charset lang
    body
        h1 Recipe #
        img recipe-#.jpg
        p Description
        h2 Ingridients
        ul
            li
            li
            li
        h2 Instructions
        ul
            li
            li
            li
        ul
            li a english-lang
            li a russian-lang
        a #top

used tags: html, body, title, meta, h1, p, ul, li, a
