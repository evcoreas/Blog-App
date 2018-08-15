# Blog Web App
A simple Blog Web Application focusing mainly on the RESTful routing architecture. I created this app using
MongoDB fot the database, Express, EJS for the javascript templating engine, Node.js and Semantic UI for the styling.
### Hosted on Heroku
* If you would like to see a live version of this application go to: [https://dream-blog.herokuapp.com/](https://dream-blog.herokuapp.com/)
* For the github repo for the Heroku version go to: [evcoreas/dream-blog](https://github.com/evcoreas/dream-blog)

## Getting Started
To get this App up and running on your local machine please clone this repository.

### Prerequisites
Please make sure you have the following on your local machine:
* [MongoDB](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/) - The Database
* [Node.js](https://nodejs.org/en/) - This is required in order to use node package manager

## Installing
After you clone the repository, go into the Blog-App-master folder in the terminal:
```
cd Blog-App-master
```
Then configure MongoDB by putting the following command in the terminal and keep it running while using the app:
```
./mongod
```
Now open a new terminal window and go into the BlogApp folder:
```
cd BlogApp
```
Then you will Install all the dependencies by running the following command:
```
npm install or npm i
```

## Deployment
You are now ready to run the application!
Run the following command:
```
npm app.js
```
View the Application on your local machine by going to: [localhost:8080/](http://localhost:8080/)
