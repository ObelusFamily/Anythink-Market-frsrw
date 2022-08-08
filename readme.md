# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the r see elevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1) Install Docker by running `brew install --cask docker` in your terminal (this make take a while)
2) Cd into the repo and run `docker-compose up` to start the app
3) Navigate to [http://localhost:3000/api/ping](http://localhost:3000/api/ping) and you should see `{"msg":"Pong! Seems like Everythink is working, great job!"}`
4) Navigatge to [http://localhost:3001/register](http://localhost:3001/register) to create a new user
5) All setup is done, you can now start developing!
  