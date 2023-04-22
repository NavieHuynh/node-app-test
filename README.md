# Demo Express/Mongo setup with Docker

This repo is to demonstrate how to setup an express app connected to a mongo server

## Features:
- Configuring an express server to connect to a mongo server using docker
- Executing a mongo query from the express server
- Formatting and displaying the results of the query into templates
- Postman collection with endpoints for validating correctness of endpoints/network connection


## Setup:
- Install Docker Desktop on the host OS 
- Run `docker-compose up` to startup the express and mongo servers
- check http://localhost:3000/ to access the express server locally

## Dependencies
- Use `npm install {package}` to update the package.json with new packages
- Rebuild the containers to apply the changes

## Database setup
- Run the `populatedb.js` script with the mongo container URI to pre-populate mongo entries
