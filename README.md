# mern-auth

In this part (part 1),

- we will
- Initialize our backend using npm and install necessary packages
- Set up a MongoDB database using mLab
- Set up a server with Node.js and Express
- Create a database schema to define a User for registration and login purposes
- Set up two API routes, register and login, using passport + jsonwebtokens for         authentication and validator for input validation
- Test our API routes using Postman


Install

- Lastly, make sure you have the following installed.
- Text Editor (Atom) (or VS code/Sublime Text)
- Latest version of Node.js (we’ll use npm, or “Node Package Manager”, to install dependencies—much like pip for Python or gems for Ruby)
- MongoDB (quick install: install Homebrew and run brew update && brew install mongodb)
- Postman (for API testing)
- Prettier (to seamlessly format our Javascript; in Atom, Packages → Prettier → Toggle Format on Save to automatically format on save)

- Install the following dependencies using npm
➜  mern-auth npm i bcryptjs body-parser concurrently express is-empty jsonwebtoken mongoose passport passport-jwt validator

-> npm i -D nodemon

## iv. Setting up our server with Node.js and Express

- The basic flow for our server setup is as follows.
- Pull in our required dependencies (namely express, mongoose and bodyParser)
- Initialize our app using express()
- Apply the middleware function for bodyparser so we can use it
- Pull in our MongoURI from our keys.js file and connect to our MongoDB database
- Set the port for our server to run on and have our app listen on this port

## Part 2: Creating our frontend & setting up Redux

- Setting up our frontend
- :1. Edit the root package.json
- :2. Scaffold our client with create-react-app

## 3. Change our package.json within our client directory

- "proxy": "<http://localhost:5000",>

## 5. Run npm run dev and test if both server and client run concurrently and successfully

- :6. Clean up our React app by removing unnecessary files and code
- :7. Install Materialize.css by editing our index.html in client/public
