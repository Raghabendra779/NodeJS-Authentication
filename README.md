# NodeJS Authentication App:-----

A complete authentication app with login, logout, register, forget password, email verification(for added security), and access control. Can be used as starter for other Node.JS applications. using Node.js, Express, Passport, JWT, Mongoose, and more.

> App Link:  [Go Live](https://node-validation.onrender.com/)

## Functionalities:

1. User can signup using the name, email and password.
2. User can directly signup using email.
3. User can login their account using email id and password or direct using email and can go to their profile.
4. User can logout their account.
5. User can reset their old password to new password.

## Technologies Used:

1.  NodeJS
2.  Express
3.  EJS
4.  MongoDB
5.  Mongoose
6.  PassportJS
7.  JWT
8.  Nodemailer

## Prerequisites:

- Git
- NodeJS
- CLI

## Installation:

_* Into the project directory*_

`cd Nodejs_Authentication-main`

_*Installing NPM dependencies*_

`npm install`

_*Then simply start your app*_

`npm start`

The Server should now be running at http://localhost:8000/

## Folder Structure:

nodejs-auth <br>
├── assets <br>
│ └── css <br>
│ └── bootstrap.min.css <br>
│ └── images <br>
│ ├── image 1 <br>
│ ├── image 3 <br>
│ └── image 2 <br>
│  
├── config <br>
│ ├── checkAuth.js <br>
│ ├── key.js <br>
│ └── passport.js <br>
├── config <br>
│ └──authController.js <br>
├── models <br>
│ └── User.js <br>
├── node_modules <br>
├── routes <br>
│ ├── auth.js <br>
│ └── index.js <br>
├── views <br>
│ ├── dash.ejs <br>
│ ├── forgot.ejs <br>
│ ├── layout.ejs <br>
│ ├── login.ejs <br>
│ ├── messages.ejs <br>
│ ├── register.ejs <br>
│ ├── reset.ejs <br>
│ └── welcome.ejs <br>
├── .gitignore <br>
├── package.json <br>
├── package-lock.json <br>
├── README.md <br>
└── server.js <br>
