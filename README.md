# e-commerce-backend

CHANGING README CHANGING README

Building a back end for a typical e-commerce site.

## Description

This project focuses on back-end route development for CRUD operations such as "GET", "POST", "PUT", and "DELETE" in a typical e-commerce site.

## Demonstrations

!<video controls src="assets/video_walkthrough/e-commerce_vid_walkthrough.mp4" title="Demonstration Video"></video>

## Screenshots

Screenshots of each operation for each model are included in the assets/screenshots folder in this github repository, for additional reference.

![GET categories](./assets/screenshots/categories_get.jpg)

![GET products by ID](./assets/screenshots/products_get_by_id.jpg)

![POST tags](./assets/screenshots/tags_create.jpg)

![PUT products](./assets/screenshots/products_update.jpg)

![DELETE tags](./assets/screenshots/tags_delete.jpg)

## Installation

Navigate to the project directory and use "npm i" in your terminal to install all necessary node packages.

To create your database, type "psql -U postgres" in your terminal, then type "\i db/schema.sql", then "\q" to exit the postgres shell.

To seed your database, type "npm run seed" in your terminal.

## Usage

User can navigate to their Insomnia app to test route functionality.

When testing the "POST" and "PUT" functions, the JSON body of your req.params should look like this for the various models:

Categories:

{
"category_name": "socks"
}

Products:

{
"product_name": "Basketball",
"price": 20.00,
"stock": 30,
"tagIds": [1, 2, 3, 4]
}

Tags:

{
"tag_name": "purple"
}

## Links

GitHub repository: https://github.com/MelissaCade/e-commerce-backend

## Credits

This page uses the materials and resources provided in the University of Denver Coding Bootcamp.

I also used the following websites as reference to figure out how to do everything:

stack overflow - https://stackoverflow.com/  
free code camp - https://www.freecodecamp.org/  
geeks for geeks - https://www.geeksforgeeks.org/  
mdn web docs - https://developer.mozilla.org/en-US/  
w3schools - https://www.w3schools.com/
sequelize - https://sequelize.org/
