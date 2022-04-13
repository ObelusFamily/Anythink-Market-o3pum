# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

# First Steps:
* Make sure you have docker installed (you can run "docker -v")
* Make sure you have yarn and a running version of MongoDB
* Have the latest LTS version of node 
* Run npm install in both the backend and frontend folders to make sure you have all the necessary dependencies
* For the API ping and Register, I recommend using either just the browser or creating a collection on Postman for further testing

# Installing the app:
* Create a dotenv file on the backend folder ( ./backend/.env ) && set the PORT to 3000 and create a MONGODB_URI to connect to your local database
* Create a dotenv file on the frontend folder ( ./frontend/.env ) && set the PORT to 3001 
* Make sure the ports in both frontend and backend are NOT the same

# Running the app:
* Use the command "docker-compose up" on the root folder

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.
