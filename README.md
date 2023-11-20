# Ecommerce Database

## Description

This project serves as a potential template for an ecommerce database. It is able to organize items into Products, Categories, and Tags, with Products and Tags having a many-to-many relationship, while Categories and Products have a one-to-many relationship.  The database has an intuitive design, and is easily able to be updated and manipulated. The project is built using Javascript and MySQL, with the two of them communicating through the Sequelize node package. This project served as a great way for me to further my practice and experience using express routes along with database queries.



## Installation

To install this program, clone the repo down to your local machine. Then run "source ./db/schema.sql" in the mysql CLI to initalize the database. You can then quit the mysql cli and run "node ./seeds/index.js" to seed the database.

## Usage

Once the database has been initialized and seeded, "node server.js" can be run from the terminal to start the server. Once the server is up and running, GET, POST, PUT, and DELETE requests can be run through the /api/categories, /api/products, and /api/tags routes. A video demonstrating the capabilities and functionalities of the database and its routes can be found at [this link.](https://drive.google.com/file/d/1XGZByiOzTLJfvHsZGJoZYB2dOa_rdYe6/view)

