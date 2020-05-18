# Angular8MeanstackAngularMaterial

Step by step article on [Angular 8/9/10 MEAN Stack Tutorial – Build CRUD App with Angular Material 8](https://www.positronx.io/angular-8-mean-stack-tutorial-build-crud-angular-material/)

## How to run the app?
- Run `npm install` to install required dependencies.
- Run `ng serve` to run the angular app
- Start the MEAN Stack backend
  - `cd backend` to enter into the backend folder
  - `nodemon server` to start the nodemon server
  - `mongod` to start the mongoDB shell

## Start MEAN Stack App
Start Angular app & install required dependencies

- git clone https://github.com/SinghDigamber/Angular8MeanstackAngularMaterial.git
- Run `npm install` from the root of the project
- run `ng serve --open` to start angular 

## Start Backend
- run `cd backend`
- run `npm install`
- run `nodemon` 

## Start MongoDB
I assume you have already set up MongoDB community edition in your local development system, if not then you can take the help from the following tutorial. [https://docs.mongodb.com/manual/administration/install-community/](https://docs.mongodb.com/manual/administration/install-community/)

- mongod --config /usr/local/etc/mongod.conf
- brew services start mongodb-community@4.2
- mongo