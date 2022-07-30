# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

[Install Docker](https://docs.docker.com/get-docker/)

You can verify docker is ready by running the following commands in your terminal:

```
docker -v
docker-compose -v
```
Then run the following command from this project's root directory to load the backend and frontend.

```
docker-compose up
```

If Docker is working correctly, the backend should be running and able to connect to your local database. You can test by browsing to http://localhost:3000/api/ping

You can test the backend by creating a user at http://localhost:3001/register

You can use <code>docker exec</code> to run commands on a running container.