# E-Commerce Back End
Module 13 Object-Relational Mapping (ORM): E-Commerce Back End

---

## Contents
[Description](#description)

[User Story](#user-story)

[Acceptance Criteria](#acceptance-criteria)

[Installation](#installation)

[Usage](#usage)

[Resources & Credit](#resourcescredit)

[Features](#features)

[Images](#images)

---

## Description 
Building the bakc end for an e-commerce site. Starter code has been prrovided. The goal is to configure a working Express.js API to use Sequelize to interact with a MySQL database.

### User Story
```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

### Acceptance Criteria 
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
```
npm i
```

## Usage
```
mysql -u root -p 
```
when prompted type in your MySQL password
```
source db/schema.sql
exit
npm run seed
node server.js
```

Testing of the code was completed in Insomnia


## Features
* Express.js
* MySQL
* Sequelize

## Images
![Insomnia Image](Assets/Insomnia%20Get%20Categories.png)
