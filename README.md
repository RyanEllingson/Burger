# Burger
Unit 13 homework

See the deployed app on Heroku:

https://ryan-burger.herokuapp.com/

# Project Description
![Screenshot](https://github.com/RyanEllingson/Burger/blob/master/assets/images/screenshot.JPG)

This app uses allows the user to add items to a database, view all the items in the database, change a property of an item, and delete an item from a database.  The idea for the app is that the items in the database are burgers, and a once in the database a burger can either be "devoured" or "not devoured."  The user adds a burger to the database by typing the name into the entry field and clicking "Add burger."  This will create a burger object in the database with the given name, and its "devoured" value will be set to false.  All burgers that are not devoured are shown on the left side of the screen.  All of the burgers that are not devoured have a button next to them that, when clicked, change the burger from "not devoured" to "devoured."  All devoured burgers are displayed on the right side of the screen.  Each of the devoured burgers has a button next to it labeled "Delete" that, when clicked, removes the burger from the database.

# Techniques and Technologies Used

This app is deployed on Heroku and utilizes a JAWSDB MySQL database to store all data.  It uses Express web server, and Sequelize for making queries to the database.