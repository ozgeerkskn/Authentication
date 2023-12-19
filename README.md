# Authentication - Express-Mongoose-Passport-Auth
This is a web application developed using Express.js, MongoDB, and Passport for user authentication and sharing secrets.
The application allows users to share their secrets while providing support for local authentication through Passport and integration with Google OAuth 2.0.

## Features
* User Authentication: Support for user registration and login using Passport and Passport-Local-Mongoose.
* Google OAuth 2.0: Users can log in with their Google accounts using the Google authentication strategy.
* MongoDB and Mongoose: User information is stored in MongoDB using the Mongoose ODM.
* Sharing Secrets: Users can share their secrets, and view secrets shared by other users.
* Dynamic Templates: EJS template engine is used for generating dynamic HTML content.

## Usage
1. Install Dependencies
   # npm install

2. Set Environment Variables

Create a .env file and add your Google OAuth client CLIENT_ID and CLIENT_SECRET.

3. Configure MongoDB Connection

Update the mongoose.connect function with your own MongoDB connection URL.

4. Start the Application
   # node app.js

5. Browse in Your Browser

Go to http://localhost:3000 and start using the application.




