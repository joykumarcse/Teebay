# Teebay

A simple containerized aplication for product renting, buying/selling online. User can add, update, delete their product as well as buy/rent products for a certain price asked by the seller/borrower.

## How to run this application

To run this application on your machine, first of all you need to clone this respository and make sure you have Docker and Docker Compose installed in your machine.
After cloning the repository `cd/Teebay` and then simply run `docker compose up -d`

The rails server will run at `http://localhost:3000` and the react app will run at `http://localhost:3001` in your local machine. The postgres database is containerized and it is running at default port `5432`

To check the running images, run `docker images` and to check the containers run `docker ps`

To stop this application, simply run `docker compose down` from the project directory.

