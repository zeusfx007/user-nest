# Nest.js Project

This is a sample Nest.js project with instructions on how to set it up.

## Prerequisites

Before you get started, ensure you have the following tools and dependencies installed:

- Node.js and npm: [Download and install Node.js](https://nodejs.org/)
- Nest CLI: Install globally using npm with the following command:
  ```bash
  npm install -g @nestjs/cli

- Sequelize CLI: Install the Sequelize CLI globally by running the following command:
  ```bash
  npm install -g sequelize-cli

- MySQL Database: You'll need a MySQL database instance. Make sure you have a MySQL server running, and create a database named userdb.

- Getting Started
- Clone the Repository:

- Install Dependencies:
   ```bash
  cd nestjs-project
  npm install

- Configure Database:

- Open the sequelizeConfig file and update the database configuration according to your MySQL setup. Make sure to set the database name to userdb.
  ```bash
   {
    "development": {
      "username": "your-username",
      "password": "your-password",
      "database": "userdb",
      "host": "localhost",
      "dialect": "mysql"
    }
  
  }

- Run Migrations:
   ```bash
   sequelize db:migrate


- Start the Server:
   ```bash
   npm run start



