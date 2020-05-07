
# Unit 14 Sequelize Homework: Reverse Engineering Code

Reverse engineer the starter code provided and create a tutorial for the code.
REVERSE ENGINEERING HW14:
•	Purpose: login app which is create the account login and logout and store it in the MySQL database
•	isAutheticated.js : insert to this file for authicated route which is limit route that if the client try to login they can login, but they can’t see the site if they not login.
•	Config.json: wrapper that simplifies working with environment specific configuration files, connect to server.
•	Index.js : connect database and import user information to login require by sequelize 

•	Controller(server.js): logic the site, connect between models and views. We call models to get the data, then we put that data on our view to be sent to the user:

•	server.js : synchronize the model the database entry file the web server that will start the app, center of the app, tie everything together start node express server, and all route connect together.
•	Passport.js: send the content to the database or send to get data public the view of the app display html appearance content javascript which is telling the pages to login with password
•	User.js: helping the client information more secure, define information of client on our database, but it must have to have “bcrypt” for the password 
•	Login.js: verifying if the information of client saved, then it will redirect the client to the member page.
•	Member.js: when receive get the data from the login, it will define who is client, and their information. If the client information match it will get the client to their own page.
•	Signup.js references from the form, and get the client to the member page
•	Style.css: styling the app
•	Index.html: the viewer representation, which is the appearance of the app that the user will see
•	Html-route(front-end): define what content it sent when the user visits specific route in the browser
•	Api-route.js(backend): define endpoint for api which is composed of index.js and passport.js in the config folder. (login route, log out route, get the user the data they want and display it in the viewer site).
Package.json : contain all dependencies that used for app, and basic information it need for the app. locally which contain all dependencies, author, homepage origin that it use for the app to run and basic information.
Node_modules: npm or package code that need to run npm package

