# ORM-E-commerce-backend

## Description
Internet retail, also known as **e-commerce**, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to their prevalence, understanding the fundamental architecture of these platforms will benefits me as a full-stack web developer.

This application is the back-end for an e-commerce site that configures a working Express.js API to use Sequelize to interact with a MySQL database.

## Installation

Packages needed to run components of this application:
- [dotenv](https://www.npmjs.com/package/dotenv)
- [MySQL2](https://www.npmjs.com/package/mysql2)
- [express](https://www.npmjs.com/package/express)
- [sequelize](https://www.npmjs.com/package/sequelize)

Node packages:
        
        npm i

Create data-base using the schema in the db folder:

        SOURCE schema.sql

Seed the db by running:
            
        npm run seed

To connect to the server and use on a client platform:

        node server.js


## Usage 
Use a back end client platform like Insomnia to view e-commerce functions.

![GIF of the application](./assets/13-orm-homework-demo-01.gif)

## Link to demo:
https://youtu.be/H8Qp9acWGeQ

## Credits
- Sue Lee

## License
![MIT](https://img.shields.io/badge/License-MIT-blue.svg)