# Everything to set up a site

## Front End

* `npx create-react-app <name>`

## Database

* MongoDB site
  * Add new project
  * Create project
  * Build database
  * For IP address go to network access tab
  * Database acess tab
    * Edit on person
    * Set to admin

## Back End

* Make file first (touch)
* npm init
  * define entry point as server.js
* npm i
  * cors
  * mongoose
  * express
  * dotenv
  * axios
* Make server.js

### In the Back End

* Imports / requires
* Setup app type
* define port
  * PORT = process.env.PORT
* define database
  * mongoose.connect(process.env.MONODB_URL)
  * define variable for the database connection
* Try to access database
  * db.on('error', console.error.bind(console, 'connection error'))
  * db.once('open', () => console.log('Mongoose is connected'))
* nodemon to start the server

### Model making

* make a model file
  * `const mongoose = require('mongoose');`
  * `const {Schema} = mongoose`
  * `const varname = new Schema({`
    * go into typical schema pairs with name and data type `name: String`


* In .env
  * PORT = 3001 (or whatever port for the server)
  * MONGODB_URL = `<put the stuff here>`
    * Go to atlas
    * Connect
    * Connect your application
    * replace password with DB password
    * enter name of the project/file before the '?'
* package.json
  * ignore .env

## Testing Server

* `http://localhost:3001`
