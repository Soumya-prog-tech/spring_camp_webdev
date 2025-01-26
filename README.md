# Task 2 : 

## Backend Register and Login System : 

step 1 : installed npm and initialized packages using npm init -y
---
step 2 : created a additional script in package.json "start : npm nodemon app.js so that i can just write npm start to start the server
---
step 3 : Used express.js for routing, used mongodb for storing database, used node.js to un javascript ( as mentioned earlier), used cookie-parser for token, used express-validator for validation the requests send by the user, used bcrypt to encrypt the password, so i downloaded all the packages by npm i ("package name")
---
step 4 : created a app.js which is the main file where all the necessary pacakges are imported which are used in the server and the server is made live on port 3000
---
step 5 : created a different route folder to store all the routes. 
---
step 6 : created a user routes file for login and register purposes
---
step 7 : created a register get route - it is used to render the register page 
---
step 8 : created a folder "view" and created a register ejs file which contains the code of the register page
---
step 9 : used css tailwind and flowbite to create the frontend faster
---
step 10 : created a config folder to store all the databases, created a db.js where we import mongoose and connect to the database
---
step 11 : created a model folder where we create a user model file in which we a create a UserSchema and then create a user using that Schema 
---
step 12 : created a register method = post for bringing data from the frontend to the backend-> it includes checking the validity of the data, bringing the data from the backend and storing it in the database
---
step 13 : created a login get route - it is used to render the login page
---
step 14 : created a login ejs file which contains the code of the login page
---
step 15 : created a login put route ( including username and password) - first checked the validity of the entries, then checked if the username exists, we checked if the password matches, if the password matches, we send Logined
---

