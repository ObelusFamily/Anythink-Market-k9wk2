# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

- clone this repository
- install [Docker](https://docs.docker.com/get-docker/)
- run `docker -v` and `docker-compose -v` to check if dockers is installed
- if installed run `docker-compose up`
- Then test backend here [http://localhost:3000/api/ping](http://localhost:3000/api/ping)
- also test frontend here [http://localhost:3001/register](http://localhost:3001/register)
- Also, you can use docker exec to run commands on a running container.
