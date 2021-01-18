### Questions

1. What is responsible for defining the routes of the `games` resource?
    - the .Router method from the express package. Allows for template routes to be created for each resource, rather than specifying the paths for each one.

2. What do you notice about the folder structure?  Whats the client responsible for? Whats the server responsible for?
    - The folder structure is split into the client and server directories which are responsible for the frontend and backend, respectively.

3. What are the the responsibilities of server.js?
    - server.js connects frontend and backend. A connection is made to the database, as well as defining routes for each resource.

4. What are the responsibilities of the `gamesRouter`?
    - gamesRouter defines the path for a particular resource to be applied to the express router.

5. What process does the the client (front-end) use to communicate with the server?
    - The client uses fetch requests to communicate with the server.

6. What optional second argument does the `fetch` method take? And what is it used for in this application? Hint: See [Using Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) on the MDN docs
    - The second argument, init, is an object containing any specified custom settings from a list of possible options such as request method, mode, credentials.

7. Which of the games API routes does the front-end application consume (i.e. make requests to)?
    - It can make requests to all routes in helpers/create_router.js via .../api/games.

8. What are we using the [MongoDB Driver](http://mongodb.github.io/node-mongodb-native/) for?
    - The MongoDB Driver allows for callback and promise based interactions with the database.

