# Teebay
A simple containerized product renting, buying/selling application. Tech stack includes Rails, React, Postgresql, docker, and docker compose. 

## How to run this application

To run this application in your local machine, you need to follow some simple steps. Make sure you have Docker and docker compose installed in your machine.
Clone this repository, using `git clone`

Move inside the directory using, `cd Teebay`

You need to create the databse first using this `docker compose run web rake db:create` command and then run `docker compose up -d` to run the application.
After successful build and container creation, visit `http://localhost://3001` to see the client interface and visit `http://localhost:3000` for rails application
.
