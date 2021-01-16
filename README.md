# Cuizeen
Fully featured web app to connect foodies and chefs

Fork
git clone
cd cuizeen
npm install
Copy env.example to env
npm start

# BelvinsStore
Cuizeen is a simple web app, to help connect foodies and chefs to share and learn recipes for prominent continental meals.

## Getting Started

# SETUP
#####Fork the repo. 
Clone the repo.
-------------
`git clone https://github.com/jobafash/Cuizeen.git && cd Cuizeen`
## Prerequisites
The following tools will be needed to run this application successfully:
* Node v12 or above
* npm v6.10 or above

## Endpoints
- GET **/** Homepage
- GET **/courses** Get all courses
- GET **/courses/new** New course
- POST **/courses/create** To create course.
- GET **/courses/:id/edit** Page to edit details of a specific course
- PUT **/courses/:id/update** Route to update course details
- GET **/courses/:id** Get the course by ID
- DELETE **/courses/:id/delete** Delete the course by ID
- GET **/chat** To access chatroom
- GET **users/new** Page to create a new user
- POST **users/create** Route to create a new user
- GET **/users/login** User can login to their account
- POST **/users/login** User can login to their account
- GET **/users/logout** User can logout of their account
- GET **/users/:id** Route to get a user by the ID.
- GET **/users/:id/edit** Page to update new user using the ID.
- PUT **/users/:id/update** Route to update new user using the ID.
- DELETE **/users/:id/delete** Delete a user by ID
- GET **/subscribers** Get all subscribers
- GET **/subscribers/new** Page to create new subscriber
- POST **/subscribers/create** Route to create subscriber
- GET **/subscribers/:id** Route to get a subscriber by the ID.
- GET **/subscribers/:id/edit** Page to update new subscriber using the ID.
- PUT **/subscribers/:id/update** Route to update new subscriber using the ID.
- DELETE **/subscribers/:id/delete** Delete a subscriber

## INSTALLATION INSTRUCTION
**On your Local Machine**
- Run `npm install` to install all dependencies
- Copy env.example to .env
- Use `npm start` to start the application
- `node seed.js` to seed the database
- Access endpoints on **localhost:3000** for the app

## Built With
* [Node.js](http://www.nodejs.org/) - Runtime-Enviroment

## Authors
* **Oluwajoba Fashogbon**
