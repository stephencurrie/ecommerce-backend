# E-Commerce Back End

## Description

This application creates and updates a MySQL database as part of an E-Commerce back end server.  The application uses Sequelize and Object-Relational Mapping to create the tables in the database, create the relationships between columns in different tables, and to seed the data.  Routes are then created to to get data from the database, create data, update data and delete data.

## Table of Contents

- [Video](#video)
- [Acceptance Criteria](#acceptance)
- [What I Learned](#learned)

## Video

Here is a video of the application with a walk through of testing the different routes in Insomnia and looking at the database with Workbench.  [Video](https://drive.google.com/file/d/1MSPWhyzZtPkGtS8-Fz9NIGtj6SOA4vKm/view)

The code is in the [GitHub Repository](https://github.com/stephencurrie/ecommerce-backend)

## Acceptance

The following were the acceptance criteria for the project:

- [x] When I add my database name, MySQL username, and MySQL password to an environment variable file, I am able to connect to a database using Sequelize
- [x] When I enter schema and seed commands, a development database is created and is seeded with test data
- [x] When I enter the command to invoke the application, my server is started and the Sequelize models are synced to the MySQL database
- [x] When I open API GET routes in Insomnia for categories, products, or tags, the data for each of these routes is displayed in a formatted JSON
- [x] When I test API POST, PUT, and DELETE routes in Insomnia, I am able to successfully create, update, and delete data in my database

## Learned

The following is a list of things I learned:

- How to use ORM models to create tables and column mapping in MySQL
- How to use Sequelize to edit data in MySQL
- How to store sensitive data in a .env file
- How to create routes to a server and test them with Insomnia
- How to connect to a database with Sequelize 
- How to use async and await commands to enable asychronous, promise based behavior
- How to use "try catch" blocks to handle errors
