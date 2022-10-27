# Lab-29

## Testy - Phase 4

### Author: Alan Chelko

## Problem Domain

* Today, we continue the second of a 4-Phase build of the RESTy application, written in React. 
* In phase 2, we will be receiving user input in preparation of connecting to live APIs, using the useState() hook in our functional components. 
* In order to properly manage state with the useState hook, we will now convert App.js to a functional component.

## Requirements

The following user stories detail the major functionality for this phase of the project.

* As a user, I want to enter the REST Method and URL to an API
* As a user, I want to see a summary of my request as well as results returned from an API request in my browser in a readable format

Application Flow:

* User enters an API URL
* Chooses a REST Method
* Clicks the “Go” button
* Application fetches data from the URL given, with the method specified
* Displays the response headers and results separately
* Both headers and results should be “pretty printed” JSON

## Testing

    * NOTE: For this assignment, testing is not required.
   
## Setup

    * PORT: 3000

### Deployed server

    * Heroku: [chelko-basic-api-server-prod](https://dashboard.heroku.com/apps/chelko-bearer-auth-prod/)

### Running the app

    * npm start
 
### Running the tests

    * npm test

### UML: Basic Auth Server -- Lab 06 UML

![UML - Lab 04](public/lab-26.png)
