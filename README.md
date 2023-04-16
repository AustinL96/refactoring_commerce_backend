# Refactoring an E-commerce Back End
![Project License](https://img.shields.io/badge/license-MIT-orange.svg)

## Description
This project allows a user to input new categories, products (with their prices, category ids, and more), and tags. It also allows someone to search by specific parameters too.

## Table of Contents
* [Installation](#Installation)
* [Usage](#Usage)
* [Contributions](#Contributions)
* [Tests](#Tests)
* [License](#license)

## Installation
A user will need VS Code, Node js, Insomnia, and to install dependencies such as "dotenv", "express", "mysql2", and "sequelize". A user will need to create their own .env file as well. A user will also need MySQL to make use of mysql2.

## Usage
* Step 1: enter your mysql shell and source the schema file to create the database. 
* Step 2: In the terminal run "npm run seed" to begin seeding the database tables. 
* Step 3: In the terminal run "npm start" to launch the server. 
* Step 4: From there open Insomia and start making HTTP requests. Begin from "http://localhost:3001/api/categories" with a get request as an example to receive all the categories. You can make further alterations with Post, Put, and Delete requests, inputting the data as JSON with Post and Put. 

To see it in action, follow this [video walkthrough](https://drive.google.com/file/d/10qH8PwZHyXHJHN0RW5wsMoHBHPRIlGck/view?usp=sharing). I speak throughout this, to make it easier to follow along with what I am doing.

## Contributions
N/A

## Tests
N/A

## License
This project is licensed under the MIT license.

## Questions
[My Github Account](https://github.com/AustinL96)

Questions about this project? Reach out to me at [austinlewis165@gmail.com](mailto:austinlewis165@gmail.com)