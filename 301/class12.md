# Crud

## Status Codes

* In your own words, describe what each group of status codes represents:
  * 100's = Informational codes - handshake code
  * 200's = Success codes
  * 300's = Redirection - redirecting the request to a different location
  * 400's = Client error codes - invalid requests or authentication errors
  * 500's = Server error codes - Best to retry

* What is status code 202?
  * Accepted, typically used for asynchronous processing since it will eventually return a value once complete.
* What is status code 308?
  * Permanent redirect, tells the client to use a different URL for all following requests
* What code would you use if an update didn't return data to a client?
  * 204
* What code would you use if a resource used to exist but no longer does?
  * 410
* What is the 'Forbidden' status code?
  * 403

## REST API

* Why do we need to pull our MongoDB database string out of our server and put it into our .env?
* What is middleware?
  * Code that runs when the server gets the request before it's passed to the routes.
* What does `app.use(express.json())` do?
  * Allows the server to accept .json formats as a body instead of a post element
* What does the `/:id` mean in a route?
  * It allows anything following the ':' to be a parameter
* What is the difference between `put` and `patch`?
  * `put` will update everything while `patch` only updates a particular segment of information
* How do you make a default value in a schema?
  * By using `default` when creating the schema when creating the mongoose.schema definition
* What does a `500` error status code mean?
  * An error on the server side
* What is the difference between a status `200` and a status `201`?
  * `200` indicates that everything is cool while `201` specifically indicates that an object was created successfully.

## Readings and Media

* [Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)
* [Build A REST API with Node.js, Express, & MongoDB - Quick](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)
