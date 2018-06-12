## Learn Restify and JIO with Node

This codebase was built with [Restify]('http://restify.com/docs/home/') for the server and [jio](https://github.com/hapijs/joi) for js schema validation. 
This project was built to learn these trechnologies, it is does not solve an problem.

[This](https://auth0.com/blog/developing-well-organized-apis-with-nodejs-joi-and-mongo/) is post used to build this codebase. The project is a simple API that manages users birthdates.

### How to Run the app
* pull the codebase
* start mongo in another terminal
* run "node server.js" in the project root directory


## END POINTS
* POST /users: An endpoint to create new users.
* GET /users/{username}: An endpoint to retrieve users by their usernames.
* POST /birthdates: And endpoint to register new birthdates.
* POST /birthdates/{username}: An endpoint to retrieve the birthdate of a certain user.
