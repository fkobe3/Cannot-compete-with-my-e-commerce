# E-commerce Back End

## Description
E-commerce back end is a Node.js application using a MySQL database to store, edit, and delete product information for a sample e-commerce website backend.  

## Table of Contents
* [Installation Requirements](#install)
* [NPM Packages Used](#npm)
* [Application Usage](#usage)
* [Tests](#tests)
* [Questions](#questions)

## <a name=install></a>Installation Requirements
E-commerce backend requires node.js which must be installed prior to using the application. There are also package dependencies required which can be installed using the following at root:

```
npm install
```
The application uses MYSQL database which must also be installed to use. There are schema.sql and seed files that can be used to build and populate a sample working product database.

### <a name=npm></a>NPM Packages
* mysql2
* dotenv 
* express 
* sequelize 

***
## <a name=usage></a>Application Usage
The application can be cloned from github using the git clone command.
```
In order to properly connect the application with a MySQL databaase a .env file must be created and populated with the appropriate information including your database password:

```
DB_NAME='ecommerce_db'
DB_USER='root'
DB_PW='<your password>'
```
Once all of the dependencies are installed, the database can be built and seeded using the following commands. The first should be executed in the mysql CLI, and the second in node terminal. 
```
source db schema.sql
npm run seed
```
To run the application, from root use:
```
npm start
```
## Tests
No tests were completed yet for this application. 

## Questions
Any questions or feedback regarding this project can be sent directly to my email at fkobe3@gmail.com or through git, my username is fkobe3. 