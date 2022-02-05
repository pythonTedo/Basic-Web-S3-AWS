# udacity-c2-basic-server

This is a simple node-express server to explore and understand the Request-Response pattern.

***
## Getting Setup

### Installing project dependencies

This project uses NPM to manage software dependencies. NPM Relies on the package.json file located in the root of this repository. After cloning, open your terminal and run:
```bash
npm install
```
>_tip_: **npm i** is shorthand for **npm install**

### Installing useful tools
#### 1. [Postbird](https://github.com/paxa/postbird)
Postbird is a useful client GUI (graphical user interface) to interact with our provisioned Postgres database. We can establish a remote connection and complete actions like viewing data and changing schema (tables, columns, ect).

#### 2. [Postman](https://www.getpostman.com/downloads/)
Postman is a useful tool to issue and save requests. Postman can create GET, PUT, POST, etc. requests complete with bodies. It can also be used to test endpoints automatically. We've included a collection (`./udacity-c2-restapi.postman_collection.json `) which contains example requsts.

***

## Running the Server Locally
To run the server locally in developer mode, open terminal and run:
```bash
npm run dev
```

Developer mode runs off the TypeScript source. Any saves will reset the server and run the latest version of the codebase. 

***
## Important Files and Project Structure

The source code for this demo resides in the ./src directory.

### src/server.ts
The main code for this demo is located in the ./src/server.ts file. This includes 

### src/cars.ts
This is a javascript object containing a list of cars. This will be useful for providing data for our simple endpoints.

### src/unit-test-examples/
This directory contains some simple unit functions (`units.ts`) and corresponding tests using Mocha and Chai (`units.tests.ts`).

***
This is Basic Web Backend APP with Node.js Express on Type Script.

This is exercise 1 from the path of Udacity course for Cloud Developer.
Course 2: Full stack Apps on AWS.

This App is a introduction in Node.js Express with Type Script.
The original code is from: https://github.com/udacity/cloud-developer/tree/master/course-02/exercises/udacity-c2-basic-server
The autor is udacity.

### *Notes for me*
npm install - installing all dependencies from package.json
npm run dev - to run the local server 
npm test - to run out unit tests 

tslint.json 
tsconfig.json -- both confert js to ts

scr - main Type Script code
udacity-c2-basic-server.postman_collection.json - in postman templates for each action with pre-defined params.


