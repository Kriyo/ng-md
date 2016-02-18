# People Data Web Application

## The Stack:

MEAN (Mongo, Express, Angular, Node) based.

### Instructions to spin up
 - Clone Repo ```git clone https://github.com/Kriyo/ng-md.git```
 - Go inside and install packages and dependencies ```cd ng-md && npm install```
 - If you have any issues at this point it may require installing node, bower or grunt.
 - Make sure mongo db is running:
    - ```sudo mongod``` (MAC / Linux)
    - ```cd YOUR_MONGO_DB_INSTALLATION_PATH/Server/VERSION_NUMBER/bin && mongod.exe``` (On Windows).
 - Start Grunt ```grunt serve```
 - The web application should default to building the development mode on localhost:9000/

### Generic Usecase of Application
The application is pretty basic as it's a yeoman scaffolded CRUD MEAN Stack.

You should be auto directed to localhost:9000/login where you can login using existing credentials
 - Admin Creds:
  -  Username: admin@admin.com
  -  Password: admin

- Standard User Creds:
  - Username: test@test.com
  - Password: test

Alternatively you can just register a new account (localhost:9000/register) and it will auto log you in and store the credentials in your local mongoDB, persistence shouldn't happen as this is setup to seed on server initiate.


You can now go to the main screen at localhost:9000/ (attempting to route to anything other than the three main views will kick you back to the main view anyway).

Here you can see there's a search field to filter the records.

And three varities of views to display the data in different formats.
