This is  a sample Angular 7 application  created form step by step from scratch and perform CRUD operations.
The backend API is exposed using Node.js, and Express framework.
MongoDB will be used for persistent storage of the data.
I used  Angular CLI 7 to generate the boilerplate project. 
This Angular 7 CRUD Example Tutorial is the comprehensive guide on building CRUD (Create, Read, Update, Delete) Web Application using the New Angular 7 Framework. The Angular 7 just released and it comes with a few new feature and improvements.

This example  contain three projects:
 - Frontend project based on angular 7
 - Backend project based on Express node and express js
 - storage project  based on mongodb

# To start  FrontEnd project

inside the angular7crud folder, execute this command
```
ng serve -o
```
  - I am using bootstrap 4 css framework,rxjs-compat and ng2-slim-loading-bar library so may be you need to run these command
  
  ```
 npm install bootstrap --save
 npm install ng2-slim-loading-bar --save
 npm install rxjs-compat --save
 ```
 
 # To start  BackEnd  and the Database projects
 
 Open the terminal inside the api folder and type the following command
  ```
 npm init -y
  ```
  And this command to install related node module
  ```
 npm install --save express body-parser cors mongoose
  ```
 INstall MongoDB and type this command to start the DB server
  ```
 mongod
 ```

