# 13 Object-Relational Mapping (ORM): E-Commerce Back End

## Description

Link to video demonstration: https://watch.screencastify.com/v/qh22HXhwFRzSFs4lYQg0
Link to Github Repo: https://github.com/maggierdelaney/ORM-homework

The following Object-Relational Mapping (ORM) homework adheres to the following acceptance criteria:

- GIVEN a functional Express.js API, WHEN I add my database name, MySQL username, and MySQL password to an environment variable file, THEN I am able to connect to a database using Sequelize

- WHEN I enter schema and seed commands, THEN a development database is created and is seeded with test data

- WHEN I enter the command to invoke the application, THEN my server is started and the Sequelize models are synced to the MySQL database

- WHEN I open API GET routes in Insomnia for categories, products, or tags, THEN the data for each of these routes is displayed in a formatted JSON

- WHEN I test API POST, PUT, and DELETE routes in Insomnia, THEN I am able to successfully create, update, and delete data in my database

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

1. Starter code was provided for this assignment that set up the basic seeds of the database, and some components of the Product "post" and "put" routes, as well as guides for estabslishing the relationships between certain pieces of data in the index Model.

2. First mysql is used to create the database, it is then seeded with npm run seed command. The server is started.

3. Each model established the objects and data types.

4. Each route specified a get, post, put and delete request for each category, product and tag.

5. Insomnia was used to test each route's functionality.

## Usage

1. Seed the database and run the server.

2. Go to insomnia and type in the following for each desired route:

GET ROUTES
Get all categories:
http://localhost:3001/api/categories
Get all products:
http://localhost:3001/api/products
Get all tags:
http://localhost:3001/api/tags

To find something by it's unique id, simply add the id on the end '/id'

POST ROUTES
Use the same routes as above, then in the request body select "JSON" and type in your new category, product or tag using {} and "" appropriately.

PUT ROUTES:
Use the above links but you must specify the category, product or tag by id at the end of the route using "/id", from there you can use the JSON request body again to make changes.

DELETE ROUTES:
Use the above links again and specify the category, product or tag you would like to remove by id using "/id". Click "send" and you can confirm it was deleted by navigating back to the original GET route and clicking send again to update your list.

## Credits

Nodejs npm
Express
MySQL
Sequelize
Docker

## License

Distributed under the MIT License.

## Badges

![NPM](https://img.shields.io/badge/NPM-%23000000.svg?style=for-the-badge&logo=npm&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)