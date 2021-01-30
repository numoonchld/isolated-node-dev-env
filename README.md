# Info 

- JS based node development environment container's image and volume

### Start Container 

- ensure Docker Desktop (and Docker Compose separately in Linux) is installed on your machine 

`docker-compose run --rm --service-ports nod_dev_env`
    - initializes containers and goes into the node dev environment CLI

### Setup Guide

`npm init`
    - initializes a node app in `/home/app` and creates `package.json` file

`npm install --save express`
    - installs ExpressJS 

`npm install --save-dev nodemon`
    - installs nodemon for hot reload of npm app

### Development Server 

`npm start`
    - kick off the development server 
