# Restful-Api
A basic starter Node.js and express.js Restful Api project that covers all the CRUD operations using different Http methods like GET, POST, DELETE and PATCH. MongoDB Atlas has been used for storing and working with all the data. The api has been tested using Postman.
##
# Technologies Used
1. Node.js
2. Express.js
3. MongoDB Atlas
4. Mongoose
5. Nodemon
6. Postman
##
# Project Setup
1. Models -> 
    Post.js: For writing the model for the api using mongoose.
2. Routes -> 
    posts.js: Contains all the code for all the routes over different http methods like GET, POST, DELETE and PATCH written using the Express.js Router and                      mongoose.
3. app.js -> Contains the logic for the server created using Express.js and connection to the MongoDB Cluster.
4. package.json -> Contains all the information about the project along with the third-party packages used.
5. package-lock.json 
6. node_modules
##
# How to run the project
1. Fistly, clone the project and build it on your local machine using `git clone` command on the terminal.
2. Run `npm install` to install all the dependencies and third-party packages.
3. Install nodemon too using `npm install nodemon --save`.
4. Run the script `npm start`.
5. The server will start listening on port 3000.
6. Open any web browser and run `http://localhost:3000`to see the server running on your machine.
7. And there you go!:)
