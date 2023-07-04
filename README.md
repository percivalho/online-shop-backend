# online-shop-backend

The online shop backend is an e-commerce backend.  it is configured with  a working Express.js API to use Sequelize to interact with a MySQL database.


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


## Installation
  
to install for running in localhost, just exceute the following:

  ```md
  npm i 
  ```

that would install the following package:
1.  Express.  It is a fast, and minimalist web framework for Node.js that simplifies the process of building web applications and APIs by providing a robust set of features for routing, middleware, template engines, and more.

2.  mysql2. It is a fast, robust and efficient Node.js package for MySQL database connectivity, and full protocol implementation.

3.  Sequelize.  It is a promise-based Node.js ORM for Postgres, MySQL, MariaDB, SQLite, and Microsoft SQL Server, that provides robust database interactions and an easy-to-use API for tasks such as data modeling, querying, and transaction handling.

4.  dotenv.  It is a zero-dependency Node.js module that loads environment variables from a .env file into process.env, providing a way to define secret keys, database credentials, and other environment-specific details that should not be in source code.


## Technologies Used

This application is built using the following technologies:

- **JavaScript**: Programming language for adding interactivity and dynamic content.
- **NodeJS**: an open-source, cross-platform, JavaScript runtime environment that executes JavaScript code outside of a web browser.
- **MySQL**: It is an open-source relational database management system that enables efficient storage, retrieval, and management of structured data for various applications and websites.
- **Sequelize**: An Object-Relational Mapping (ORM) library for Node.js that provides an abstraction for database operations, supports multiple databases, and offers features like transaction control, relations, etc.
- **Express**: A minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications, such as routing, and middleware setup.
- **dotenv**: A zero-dependency Node.js module that loads environment variables from a .env file into process.env, allowing the management of private credentials in a safe and modular way.

## Usage

The user should clone the repository and run 'npm i' to install the following: 
- express
- mysql2
- sequelize
- dotenv

database setup:
run with 'mysql -u root'
then run 'source db/schema.sql' to create the schema
then run 'npm run seed' to setup the seeds data

for localhost:
then run 'npm run start' to invoke the online store backend.


## Features

The application is capable of the full functionality of online store.
Include the all the Restful CRUD operations:

1.  Get all/Get any
2.  Post
3.  Put
4.  Delete
for all the category, product and tag. 


the walkthrough video is below:

[![Video Thumbnail](./assets/screenshot.png)](https://drive.google.com/file/d/1gfFAEWYA9bcTTQLpF_EbxCk9IaThEJYV)



## Tests

Testing done on:

Category:
1. testing on viewing all categories.
2. testing on viewing any one category.
3. testing on posting a new category.
4. testing on updating a category.
5. testing on deleting a category.

Product:
1. testing on viewing all products.
2. testing on viewing any one product.
3. testing on posting a new product.
4. testing on updating a product.
5. testing on deleting a product.

Tag:
1. testing on viewing all tags.
2. testing on viewing any one tag.
3. testing on posting a new tag.
4. testing on updating a tag.
5. testing on deleting a tag.


## Resources

Link to Video:

https://drive.google.com/file/d/1gfFAEWYA9bcTTQLpF_EbxCk9IaThEJYV


Link to GitHub repo:

https://github.com/percivalho/online-shop-backend.git




## License 

![License badge](https://img.shields.io/badge/license-MIT-blue.svg)


## Credits and Copyright 
&copy; Copyright 2023 - Present. Percival Ho