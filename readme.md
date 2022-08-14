# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## Setting Up Local Enivornment

* Install [Docker](https://docs.docker.com/get-docker/)
* Verify Docker is working by following commands: `docker -v` and `docker-compose up`
* Backend will respond at `http://localhost:3000/api/ping` if the Docker is working correctly
* Run all the scripts by using `docker-compose up`