#ecom-55

## Description
This project is the back-end code for an e-commerce website that handles a working Express.js API into Sequelize to interact with a MySQL database.

## User Story
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria
```
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```
## Installation

To install this application, clone the code into your terminal for the respective repository. Then, install npm by entering the command ```npm init```  into the terminal. Finally, the program can then be run by entering Get, Post, Put, and Delete requests in Insomnia.

To launch the MySQL command-line client, enter the flowing command in a Command Prompt window: ```mysql -u root -p ```. The ```-p```option is needed only if a root password is defined for MySQL. Enter the password when prompted.

## Usage
1. Install npm: npm init -y
2. In the terminal, type ```npm start``` to start the program.
3. Open Insomnia and enter Get, Post, Put, and Delete requests.
4. Use MySQL to check table statuses (if preferred).

## Technology Used
- Express.js
- API
- Sequelize
- MySQL database

## Video Demo link
- https://youtu.be/qemK0BkHMv4
