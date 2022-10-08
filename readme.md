# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_


## Setting up the local environment

1. Install docker- you can verify the version that is installed using `docker -v`
2. Run the `docker-compose up` command to load the container.
3. Test the frontend of the project by using `http://localhost:3000/api/ping`
4. Test the backend by using `http://localhost:3001/register`
