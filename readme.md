## Introduction

This project is the backend of Vidly, an imaginary video rental app. I've used Vidly as an example in several of my online programming courses, such as:

- https://codewithmosh.com/p/mastering-react
- https://codewithmosh.com/p/the-complete-node-js-course
- https://codewithmosh.com/p/asp-net-mvc

This is the implementation of Vidly in Node.js.

## Setup

Make sure to follow all these steps exactly as explained below. Do not miss any steps or you won't be able to run this application.

### Install MongoDB

To run this project, you need to install the latest version of MongoDB Community Edition first.

https://docs.mongodb.com/manual/installation/

Once you install MongoDB, make sure it's running.

### Install the Dependencies

Next, from the project folder, install the dependencies:

    npm i

### Populate the Database

    node seed.js

### Run the Tests

You're almost done! Run the tests to make sure everything is working:

    npm test

All tests should pass.

### Start the Server

    node index.js

This will launch the Node server on port 3900. If that port is busy, you can set a different point in config/default.json.

Open up your browser and head over to:

http://localhost:3900/api/genres

You should see the list of genres. That confirms that you have set up everything successfully.

### (Optional) Environment Variables

If you look at config/default.json, you'll see a property called jwtPrivateKey. This key is used to encrypt JSON web tokens. So, for security reasons, it should not be checked into the source control. I've set a default value here to make it easier for you to get up and running with this project. For a production scenario, you should store this key as an environment variable.

On Mac:

    export vidly_jwtPrivateKey=yourSecureKey

On Windows:

    set vidly_jwtPrivateKey=yourSecureKey

npm i -g serve
serve -s build
npm run build
heroku -v
heroku login
export HTTP_PROXY=http://proxy.server.com:1234
redirect into frist-api-node heroku create
redirect into frist-api-node git push heroku master
redirect into frist-api-node heroku logs
redirect into frist-api-node heroku config:set vidly_db=mongodb+srv://infooffice1399:<password>@cluster0.ahwsb21.mongodb.net/test
heroku  open

http://localhost:3000/movies
https://vidly.com/auth/callback
https://vidly.com/auth/movies
8fd6da67-1407-4ffe-8d72-60afb8df8a40

Use the following code to set up your app for local development.

heroku config:add \ HEROKU_OAUTH_ID=8fd6da67-1407-4ffe-8d72-60afb8df8a40 \ HEROKU_OAUTH_SECRET=8809ef89-cacd-4a6a-b41e-1916fbbe003d

Heroku, which is an amazing cloud service
need to install Heroku CLI 
once you install Heroku CLI and open up the terminal run
### `heroku -v `

you need to login
### `heroku login`
on Mac we use export, on windows we set HTTP_PROXY and 
### `export HTTP_PROXY=http://proxy.server.com:1234`
### `set HTTP_PROXY=http://proxy.server.com:1234`
MongoDB in the Cloud
you have set up a Heroku account, now you need to setup an mLap account 

Deploying to Heroku
first-api-node
### `heroku create vidly-api-01`
### `heroku create`
### `git push heroku master`
### `heroku open`

viewing Logs
### `heroku logs`

Connecting with MongoDB Driver
1. Select your driver and version

2. Install your driver
### `npm install mongodb@3.6`
3. Add your connection string into your application code
mongodb+srv://<username>:<password>@cluster0.ahwsb21.mongodb.net/?retryWrites=true&w=majority

we want to store this as an environment variable on Heroku
### `heroku config:set vidly_db=mongodb+srv://<username>:<password>@cluster0.ahwsb21.mongodb.net/?retryWrites=true&w=majority`
### `git add .`
### `git commit -m "write message"`
### `git push heroku master`
### `heroku create --buildpack https://github.com/mars/create-react-app-buildpack.git`
### `git push heroku master`
### `heroku open`