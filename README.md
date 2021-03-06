# WCRealEstate-Backend

This is the backend API for the World Class Real Estate Project.

Note - Run the commands without the quotes

## Steps to set up the application

1. Clone the repository by using the commannd "git clone https://github.com/gurparshad/visioncraft-assignement-backend.git"

2. Download and install node js and npm (node package manager) https://nodejs.org/en/download Verify the installation by running the following commands in command promt.
   - "node –v"
   - "npm –v" 
 If installation is successfull above commands will return teh versions of node and npm resp.
    
3. To install all the dependencies run the command "npm install" from inside the project root directory.

## Setting up the database

1. Download and Install mysql and MysQL workbench
    - for windows server and workbench https://dev.mysql.com/downloads/mysql/
    - for Linux server Install: http://bit.ly/2DijNpJ , Workbench Install: http://bit.ly/2B153d8 
    - for Mac Server Install: http://bit.ly/2PU2IZU , Workbench Install: http://bit.ly/2B2xiZ2 
 
2. Create a database schema through the command line or MySQL workbench.

3. Change the configuration in the config.json file located in rootDirectory/config
    - database = nameOfYourDatabase
    - username = yourDatabaeUsername
    - password = yourDatabasePassword
    - dialect = yourDatabaseDialect (mysql if using mysql database)
   
4. Run the command "npx sequelize-cli db:migrate" The database will be created with three tables - users, properties and pictures.

## Start the application

Run command "npm start"

## Postman API CLient link

https://www.getpostman.com/collections/ae25afdc3ed07c005cd4

## Languages and libraries used

- node js
- express js
- mysql
- javascript
- sequelize
- mysql2
- bcrypt
- sequelize-cli
- express-validators
- cross-env
- config 
