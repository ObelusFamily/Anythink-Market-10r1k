# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Local Environment Setup

### Pre-reqs

1. Docker desktop installed

### Setup Instructions

1. Validate docker is installed:

```bash
docker -v
docker-compose -v
```

1. From the root of this directory, run the following command:

```bash
docker-compose up
```

1. Validate backend is up by navigating to [http://localhost:3000/api/ping](http://localhost:3000/api/ping) and validating the following text appears: 

>{"msg":"Pong! Seems like Everythink is working, great job!"}

1. Validate frontend is up by navigating to [http://localhost:3001/register](http://localhost:3001/register) and validating a webpage appears asking you to sign up for an account

1. Create a username and sign up
