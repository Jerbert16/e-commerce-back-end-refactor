# E-Commerce Backend Refactor 

## Project Description

E-commerce, or internet retail, is already major industry, and it's poised for continued growth. As a full-stack developer it's imperative to understand how databases - and database manipulation using code - play a role in these types of applications. This project aims to explore those notions by taking starter code and refactoring it into a back end that a manager at an internet retailer can use. 

This application uses the following: 
* Sequelize
* Mysql2
* Express
* JavaScript

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
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
```

## Application In Action 