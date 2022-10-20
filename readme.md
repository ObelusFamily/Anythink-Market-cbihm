# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

### Docker

- Install [Docker](https://docs.docker.com/get-docker/)
- Verify docker is working as expected by running `docker -v` and `docker-compose -v`
- Run `docker-compose up` to start the app and all the dependencies
- Ensure the backend is running by visiting [http://localhost:3000/api/ping](http://localhost:3000/api/ping)
- Ensure the frontend is running by visiting [http://localhost:3001](http://localhost:3001)
- Run `docker-compose down` to stop the app
