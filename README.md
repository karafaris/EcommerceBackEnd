# 13 Object-Relational Mapping (ORM): E-Commerce Back End

## Description
The motivation behind building the back end for an e-commerce site using Express.js API and Sequelize is to create a scalable and efficient solution for managing a MySQL database. This project solves the problem of establishing a solid foundation for an e-commerce site by integrating Express.js and Sequelize, enabling streamlined data storage, retrieval, and complex query handling. Throughout the development process, valuable lessons are learned in RESTful API design, Sequelize ORM usage, middleware implementation, authentication, and database optimization. The project stands out by combining these technologies to deliver a powerful, standardized, and maintainable back-end infrastructure for e-commerce applications.


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
## GitHub Repository 
https://github.com/karafaris/EcommerceBackEnd.git

## DEMO - YouTube URL's for Part 1 and Part 2
Part 1 https://youtu.be/LBzGD_z8x6Q 
Part 2 https://youtu.be/10wDNru121c

## Instructions on how to run the app
Add a .env file to the root of the app with the following details
DB_NAME='ecommerce_db'
DB_USER='root'
DB_PW='xxx'



