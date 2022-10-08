# Object-Relational Mapping (ORM) - E-commerce Back End
[![This repository is Unlicensed and free to use.](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/)

## Description
Due to the prevalence of E-commerce platforms, this is a practice back end to understand the fundamental architecture of e-commerce sites. This application was built using an Express.js back end and Sequelize to interact with a MySQL database.
  
## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

In order to use view this back end site, requirements are MySQL and node.js. To install all dependencies, run ```npm i ``` in the terminal.

## Usage 
The user must create MySQL crendentials in a .env file, with the database name, username, and password. 
```
DB_NAME='ecommerce_db'
DB_USER=''
DB_PASSWORD=''
```
Then run the db schema sql file and seed the database using ```npm run seed``` then run the application with ```node server.js```.

---

Video walkthrough of creating and seeding the database, and starting the application

![Seeding database and starting application](./assets/seeding%26running.gif)

---

Video walkthrough of creating and seeding the database, and starting the application

![Seeding database and starting application](./assets/seeding%26running.gif)


## Credits
While working on this project, I worked alongside Jackson Myhre in the same bootcamp class. A lot of the routes were taken from class activities and edited to work in this assignment.

## License
Licensed by The Unlicense
