# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
* Install Docker. https://docs.docker.com/get-docker/
* Verify Docker by running the following commands in terminal `docker -v` and `docker-compose -v`.
* Run `docker-compose up` from the project root directory to load Anythink's backend and frontend. If Docker is working correctly, the backend should be running and able to connect to your local database.
* Test the connection by pointing your browser to http://localhost:3000/api/ping
* Check the frontend and make sure it's connected to the backend. You should be able to connect a new user on  http://localhost:3001/register
* Make sure that you run all scripts in one of the containers created by docker-compose up. You can also use docker exec to run commands on a running container.

