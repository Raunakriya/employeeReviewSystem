# Employee Review System
## Description
 A backend project,The Employee Review System. It is an application that allow employees
to talk about each other based upon their work and behavior. 
It works like -- employees can write feedback about each other, but only the admin, can assign task , add new employ and give authority to other employee.


the main purpose of This application Employee Review System is for companies to improve and grow. 
It allow employees to talk each other, in a professional and respectful manner.
  
## Tech stack
  Tech Stack used for this application --MongoDB for database, nodejs and express for creting server and ejs for views template, javascript , html, css, and bootstrap for frontend. 
It is easy for employees to use and helps create a positive work environment.
  
## How to setup the project on local system
  1. Clone this project
  2. Start by installing npm if you don't have it already.
  3. Navigate to Project Directory by : Using
  
  cd employeeReviewSystem
  
  
  
  After reaching to the this preoject directory yo have to run this following command :
  
  $ npm install
  $ nodemon index.js or npm start
  
  4. Admin PassWord(important) 
  
  12345
  
  

 
  ## Features
  * Adimin Interface
  ![Alt text](https://github.com/Raunakriya/employeeReviewSystem/blob/main/assets/Images/Screenshot%20(52).png?raw=true)
  *Interface for employee who is not admin
  ![Test Image 4](https://github.com/Raunakriya/employeeReviewSystem/blob/main/assets/Images/Screenshot%20(53).png?raw=true)
  * Admin have all employee Data
  ![test5](https://github.com/Raunakriya/employeeReviewSystem/blob/main/assets/Images/Screenshot%20(54).png?raw=true)
  * Admin assing work to employ for feeback each other, or give Authority to others.  
  ![test6](https://github.com/Raunakriya/employeeReviewSystem/blob/main/assets/Images/Screenshot%20(55).png?raw=true)
  * SignUp Interface
  ![test5](https://github.com/Raunakriya/employeeReviewSystem/blob/main/assets/Images/Screenshot%20(56).png?raw=true)
  * SignIn Inteface
  ![test5](https://github.com/Raunakriya/employeeReviewSystem/blob/main/assets/Images/Screenshot%20(57).png?raw=true)
 

  ## Folder Structure
bash

employee-review-System
    |
    |               |--->css
    |--->assets---->|--->images
    |               |---> js
    |
    |               |--->mongoose.js
    |--->config---->|
    |               |--->passport-local-Stradegy.js
    |
    |                  |-->admin_controoler.js
    |--->controllers-->|-->review_controller.js
    |                  |-->user_controller.js
    |
    |               |-->review.js
    |--->models---->|
    |               |-->user.js
    |
    |              
    |               |-->admin.js
    |--->routes---->|-->review.js
    |               |-->index.js
    |               |-->user.js
    |
    |
    |
    |
    |              |--->_header.ejs
    |              |--->_footer.ejs
    |              |--->admin.ejs
    |--->views---->|--->employee.ejs
    |              |--->home.ejs
    |              |--->layout.ejs
    |              |--->login.ejs
    |              |--->register.ejs
    |              
    |
    |-->index.js
    |
    |-->node_modules
    |-->.gitignore
    |-->package.json
    |
