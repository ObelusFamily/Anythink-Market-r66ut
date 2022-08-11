# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Steps for setting up local envirnoment:

1. first install docker.
2. After installation you can verify using the following commands on your terminal: docker -v , docker -compose -v .
3. if it is working correctly , let's check from your browser using http://localhost:3000/api/ping .
4. now lets check the frontend and see that is is connected with backend.
5. if it is working properly then create a new user on http://localhost:3001/register .

6. And you are all set.😊
