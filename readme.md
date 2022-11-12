# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
    step 1) 
        clone repo to local (https://github.com/ObelusFamily/Anythink-Market-3wxgf.git)
    step 2) 
        Install Docker
            2a) 
                goto (https://docs.docker.com/get-docker/) Install docker-desktop corresponding to your system
            2b) 
                to have access to docker-desktop sign-up at (https://hub.docker.com/signup) to link docker-desktop and docker-online 
            2c) 
                to confirm that docker is installed open terminal and type (docker -v)
    step 3)  
        'cd' into the project root directory and the run (docker-compose up) to load Anythink's backend and frontend
            3a) 
                If Docker is working correctly, the backend should be running and able to connect to your local database.
            3b) 
                Let's test this by pointing your browser to http://localhost:3000/api/ping
    step 4) 
        If everything is working properly, you will be able to create a new user on (http://localhost:3001/register)