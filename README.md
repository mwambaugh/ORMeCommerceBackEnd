# ORMeCommerceBackEnd
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)]

# Table of Contents 

[User Story](#User-Story)

[Usage](#Usage)

[Instlation](#Instalation)

[Links](#Links)

[Contributing](#contributing)

[Questions](#questions)

[Acceptance Criteria](#acceptance-criteria)

## User Story
* AS A manager at an internet retail company
* I WANT a back end for my e-commerce website that uses the latest technologies
* SO THAT my company can compete with other e-commerce companies

## Usage
Internet retail, also known as e-commerce, is the largest sector of the electronics industry, having generated an estimated US$29 trillion in 2017 (Source: United Nations Conference on Trade and Development). E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to the prevalence of these platforms, developers should understand the fundamental architecture of e-commerce sites.

My challenge was to build the back end for an e-commerce site. My goal was to take a working Express.js API and configure it to use Sequelize to interact with a MySQL database.

## Instalation
To install this app and make it your own you will need to use such commands such as `npm i` , `npm install mysql2`, sequalize, express, dotenv, and `npm run start`. Tests will need to use [insomnia](https://insomnia.rest/).
 
## Links
[Testing Routes Demo](https://watch.screencastify.com/v/zxfutI945amEiGO1kOuE)   

## Contributing 
This project was based off class starter code cloned from:[here](https://github.com/coding-boot-camp/fantastic-umbrella). This assignment was worked on by student, M.C. Wambaugh, with the support of her TA's during office hours and meeting regularly with a tutor, and her classrom peers and huge thanks to the tutors at AskBCS in slack for git hub help and moving the repo/directory. The student also used universial resources such as  YouTube.com, shields.io/, and our class repo examples. Many thanks to those who continue to support learning in the technological community.

## Questions 
Please direct questions to Marta Wambaugh at marwambaugh@gmail.com and https://github.com/mwambaugh 

## Acceptance Criteria
* GIVEN a functional Express.js API
* WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
* THEN I am able to connect to a database using Sequelize
* WHEN I enter schema and seed commands
* THEN a development database is created and is seeded with test data
* WHEN I enter the command to invoke the application
* THEN my server is started and the Sequelize models are synced to the MySQL database
* WHEN I open API GET routes in Insomnia Core for categories, products, or tags
* THEN the data for each of these routes is displayed in a formatted JSON
* WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
* THEN I am able to successfully create, update, and delete data in my database