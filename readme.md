# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

Step 1:
- So first thing’s first - install Docker (https://docs.docker.com/get-docker/)

Step 2:
- Verify docker is ready by running the following commands:
- docker -v: verify docker version
- docker-compose -v: verify compose version

Step 3:
- Run "docker-compose up" (make sure docker desktop is running first)

Step 4: 
- Test the backend and see if it is running by going to http://localhost:3000/api/ping

Step 5:
- Test the frontend: http://localhost:3001/register

Step 6: 
- Create a new user 
