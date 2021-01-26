#PhoneBook - app api in Express/Nodejs

The `api` uri preceed all API endpoints and the following endpoints are currently available
* GET `/api/contacts`
* POST `/api/contacts`
* GET `/api/contacts/:id`
* PUT `/api/contacts/:id`
* PATCH `/api/contacts/:id`
* DELETE `/api/contacts/:id`


# How to Install & Use

  >  Install Nodejs-(LTS) from  this site
    https://nodejs.org/en/
    
> Open "cmd" OR command prompt / terminal in windows/linx

 * Open project folder & type : "npm install"
It will install all dependencies required by this project



Install mongodb for database & mongodbcompass for exploring database & management
https://www.mongodb.com/try/download/community
https://www.mongodb.com/products/compass

Start the mongodb server mongod.exe or mongo.exe in start menu or search from search bar

Go to project folder & open cmd , type: " npm start "
This will start the api-server

open the browser (chrome or firefox) & go to this url: "localhost:8080/api/contacts"

Currently it is empty because there is nothing in database

Open mongodb compass & click connect(leave the input field as it is), it will automatically connect to local host & select the database "Contact or resthub" Insert data into it & goto browser refresh & you will see the data


