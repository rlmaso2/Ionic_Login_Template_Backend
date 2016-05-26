
Welcome to the Bionic Innovations (www.BionicInnovations.com) Ionic Login Template.

This project is a modified version of the Devdactic RESTful API User Authentication with Node.js and AngularJS Server (https://devdactic.com/restful-api-user-authentication-1/).

This Node.js server will allow us to sign up, login and request member information from protected endpoints. 

I used the complete MEAN stack:

MongoDb – Our Database
Expressjs – A simple server
AngularJS – For our frontend later
Node.js – Our backend framework

So please make sure you have everything installed, especially the MongoDB

We will use PassportJS for our security and use the JSON Web Token idea for our token. This is a recommended approach for all RESTful APIs, the JWT is and will become more and more the standard.

Additionally we will install some encryption for passwords, everything the server needs and a simple connector to our MongoDB.

Once you have everything installed the server can be started using the following method.

Reminder: This backend was setup using Cloud 9. Some variables will need to be modified to work on your enviroment.

## Running the server

1) Open `server.js` and start the app by clicking on the "Run" button in the top menu.

2) Alternatively you can launch the app from the Terminal:

    $ node server.js

Once the server is running, open the project in the shape of 'https://projectname-username.c9.io/'. As you enter your name, watch the Users list (on the left) update. Once you press Enter or Send, the message is shared with all connected clients.
