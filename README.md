# ERS
employee review system made using Node.js and EJS (Embedded JavaScript) is a web application that allows companies to manage and conduct employee performance evaluations. It facilitates the process of creating, updating, and viewing employee reviews within the organization.
To create this system, you would use Node.js and Express.js to build the backend, EJS for rendering dynamic views, and a database to store and manage the data. You can also use other libraries or frameworks to enhance the functionality and user experience of the application, such as Bootstrap for styling or Socket.IO for real-time communication.

Description
A full stack app, in which the admin, can assign the employees, to review each other on the basic of there work. The admin has special power, to make any other employee as the new admin. Admin can also make the new employee, and they can also assing, the reviewer and revieweee. The admin can see the current employee, and according to the review, the admin can remove the employee. The review given to the employee, is always going to be store in the database.


Tech Stack
Node , Express, Mongodb , EJS , javaScript , html, css


How to setup the project on local system
Clone this project
Start by installing npm if you don't have it already.
Navigate to Project Directory.
After reaching the project directory you have to run the following the command.

     npm install 
     npm start || nodemon index.js
If you want to make an employee as admin then use the secret key : happy.




Features
You can review the employees. The admin has the special power to assing, the task to employee, remove the employee, add new admin, and also employee;
HomePage / Admin View
Home page / Employee view
Sign-Up
Sign-In
Forget Password
Assign Task
Employee List



Folder Structure

Employee Review System
    |
    |               |--->css
    |--->assets---->|--->images
    |             
    |
    |               |--->flashMiddleware.js
    |--->config---->|--->mongoose.js
    |               |--->passport-local-Stradegy.js
    |
    |                  |-->admin_controller.js
    |--->controllers-->|-->home_controller.js
    |                  |-->review_controller.js
    |                  |-->user_controller.js
    |
    |               |-->review.js
    |--->models---->|
    |               |-->user.js
    |
    |              
    |               |-->admin.js
    |--->routes---->|-->index.js
    |               |-->review.js
    |               |-->user.js
    |
    |              |--->_header.ejs
    |              |---> addEmployee.ejs
    |              |---> admin.ejs
    |              |---> employe.ejs
    |--->views---->|--->forget_password.ejs
    |              |--->home.ejs
    |              |--->layout.ejs
    |              |--->sign_in.ejs
    |              |--->sign_up.ejs
    |
    |-->node_modules
    |-->.gitignore
    |--> index.js
    |--> package-lock.json
    |-->package.json
    
    ````







