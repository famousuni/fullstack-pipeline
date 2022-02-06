# Udagram Pipeline

This project is a full stack application with pipeline integration AWS via CircleCI
- Pipeline Status: [![CircleCI](https://circleci.com/gh/famousuni/fullstack-pipeline/tree/main.svg?style=svg)](https://circleci.com/gh/famousuni/fullstack-pipeline/tree/main)

- [Access Live Application](http://c-udagram-1.s3-website-us-east-1.amazonaws.com/)

## Getting Started

- Clone this repo locally.
- Follow Installation steps

The project can run but is missing some information to connect to the database and storage service. These will be setup during the course of the project


### Installation

Provision the necessary AWS services needed for running the application:

- In AWS, provision a publicly available RDS database running Postgres.
- In AWS, provision a s3 bucket for hosting the uploaded files.
- Export the ENV variables needed or use a package like
- From the root of the repo, navigate udagram-api folder `cd udagram-api` to install the node_modules `npm install`. After installation is done start the api in dev mode with `npm run dev`.
- Navigate to the udagram-frontend `cd udagram-frontend` to install the node_modules `npm install`. After installation is done start the api in dev mode with `npm run start`.

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd starter/udagram-frontend`
1. `npm run test`
1. `npm run e2e`

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

The e2e tests are using Protractor and Jasmine.


CircleCI will invoke the various npm install npm build and npm deploy scripts from the root directories package.json

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## License

[License](LICENSE.txt)
