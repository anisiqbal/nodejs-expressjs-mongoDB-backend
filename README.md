# nodejs-expressjs-mongoDB-backend
Backend APIs using ExpressJS, MongoDB, NodeJS

# Article Reference
https://medium.com/@dinyangetoh/how-to-build-simple-restful-api-with-nodejs-expressjs-and-mongodb-99348012925d

# Steps to follow - Setup

1. install Nodejs
2. install Postman
3. install MongoDB

# Initialize NodeJs project
> npm init

# Install Express and Setup Server
> npm install express --save

# create a file at root of project folder
> index.js (paste the code mentioned in Article)

# Save the file and run following command on the terminal window
> node index

# Create a route file in your project root
> api-routes.js

# Our current setup requires that we restart the server each time we make changes to our files or add new ones. This can become stressful and frustrating sometimes but there is a quick fix for it.
> npm install -g nodemon

# Setting up MongoDB
> Add a environment variable where the MongoDB folder is located = C:\Program Files\MongoDB\Server\4.4\bin
> start MongoDB instance by running this command in CMD = mongod

# install mongoose, body-parser
> npm install mongoose (Nodejs package for modeling Mongodb)
> npm install body-parser (Enables your app to parse data from incoming request like form data via urlencode)