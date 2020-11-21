 # Node Project Structure
 
 some of the good practices followed in this project are:
 - Async/Await support 
 - WinstonJs Logger Implementation
 - Error Handling
 - Sequelize Support 
 - Basic Joi Validation
 - Open Api Specification implemented through swagger-jsdocs and swagger-ui
 - Jwt implementation 
 - Enviroment variables to hold configuration values .env file
 - OOP (object oriented programming)
 - i've followed [airbnb](https://github.com/airbnb/javascript) Coding standard with a eslint ,help to keep thing into prespective.
 
 # How to start the project 
 
 first you clone the project using the following command :
 
 git clone repo name
 
 install node version 8.11.0
 
 delete the existing package.lock.json and run npm install 
 
 then you create a postgres database Named guri with the following credintials 
 
 username : postgres 
 
 password : password
 
 run the migration using the following command :
 npx sequelize-cli db:migrate
 
 Finally you run npm start 
  
Future improvements utilize compenent based structure
