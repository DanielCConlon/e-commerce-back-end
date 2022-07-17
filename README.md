# e-commerce-back-end

GithubRepo: https://github.com/DanielCConlon/e-commerce-back-end
Part 1 demo: https://watch.screencastify.com/v/MTSWitPFJDZ5quKG5NQD
part 2 demo: https://watch.screencastify.com/v/G0gl8b8VgsWqbdsa820M

## Table-of-Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)

## [Description](#table-of-contents)

Build the back end for an e-commerce site. You’ll take a working Express.js API and configure it to use Sequelize to interact with a MySQL database.

Requirements for the project:
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database

## [Installation](#table-of-contents)

Download the repo from Github. You will also need to run the command npm install express mysql2 in order to get npm and mysql ready.

## [Usage](#table-of-contents)

After you have installed mysql2 you will need to the root folder of the application in the command line and run mysql -u root -p. You will need to create the ecommerce_db. Once the database is made you will run npm run seed in the bash terminal to populate the database. After you populate the database you will need to create routes in insomnia to interact with the database information.
