# Zombies
W4

We have been contacted by the Zombie Awareness Organisation, they have been creating a new app to make the public aware of the zombie apocalypse and informing them about who has been bitten! To get familiar with their codebase:

1. Run the application, by creating and seeding the database, and viewing the application in the browser.
2. Draw a diagram that details the relationship between the database tables.

## Part 1

Answer the following questions:

1. This project has multiple controllers. What is the benefit of this?
2. In the controllers, we are referencing the views as symbols containing strings (e.g. `erb(:"bitings/new")`) rather than just symbol (e.g. `erb(:new)`). Why do we need to do this?
3. Look at the `bitings/new` view. For each new biting, the user is able to select a victim and a zombie. How are the select’s being populated dynamically? (Trace the data flow from the database to the select dropdown menu)

## Part 2

The Zombie Awareness Organisation has a problem - they cannot seem to get the CSS right! You have been tasked with altering the existing CSS so that it looks like the provided prototypes.

Complete the following tasks:

1. Change the orientation of the biting entries to vertical using flex (see Image 4)
2. Change the orientation of navigation bar to vertical using flex (see Image 1 - 5)
3. Change the orientation so that the content sits to the right of the navigation bar using flex (see Image 1 - 5)
4. Change position of the line above the content to go to the left of the content (see Image 1 - 5)
5. Reduce the gap between the navigation bar and the content using padding (see Image 1 - 5)
6. Change the background image to 'background.jpg' (see Image 1 - 5)
7. Whoops! The colour scheme doesn't work with the new background! Change the text colour of the title, the delete button and the dividing line colour to: darkred (see Image 4)
8. Change the colour of the main text and the tables to: papayawhip (see Image 3 - the text in the right side of the table and the colour of the table itself are a cream colour)
9. Change the colour of the links to: #a2937e (see Image 3 - the names of the victims (left side) are a different colour to the right side, and are the same colour as the navigation bar text)
10. Change the colour of the new biting button to: darkolivegreen (see Image 5)

*HINT - some points may require REMOVING existing code instead of adding something new*

## Extension:
1. Research how to add an image to the dropdown menus, and use this to add the hazard logo to the dropdowns in the new biting form. (see Image 5)
