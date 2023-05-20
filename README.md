# Hosting a Full-Stack Application
[Link to Udagram Application](http://uda-bucket-355177273640.s3-website-us-east-1.amazonaws.com)

Screenshots documenting deployment processes can be found in the root directory of the project in the ```docs``` folder.

# Project Explanation

The purpose of this capstone project is to demonstrate one's ability to deploy a Full Stack application to a cloud service (AWS in this case) and to implement a working CI/CD pipeline.

Udagram is the name of the application deployed in this project.
It's a full stack, starter app (minimalist Instagram clone) provided by Udacity.com for use in the capstone project of the Full Stack Javascript Developer nanodegree certification course.

## Table of Contents

-   [Project Title](#hosting-a-full-stack-application)
-   [Project Explanation](#project-explanation)
-   [Table of contents](#table-of-contents)
-   [Abilities Demonstrated](#abilities-demonstrated)
-   [Web Technologies](#web-technologies)
-   [Dependencies](#dependencies)
-   [Installation](#installation)
-   [Testing](#testing)
-   [Unit Tests](#unit-tests)
-   [End to End Tests](#end-to-end-tests)
-   [Built With](#built-with)
-   [License](#license)

## Abilities Demonstrated

The sucessful deployment of this full stack app displays an understanding of and a facility in:

- Utilization of the Command Line in deployment processes
- Initializing and configuring a relational database instance on a cloud service
- Deploying of a backend API application
- Deploying of a frontend application
- Implementating of modifications in package.json scripts
- Adopting of environment variables to replace hard-coded secrets
- Proficiency in interacting with AWS services
- Manual deployment of a full stack application
- Connecting a public repo to an automated deployment process triggered by code pushes
- Comprehensive documentation for ease of use in future interaction with the codebase

# Web Technologies

Web technologies used in this project include:

-   APIs
-   Express.js
-   Node.js
-   Typescript
-   PostgreSQL
-   Ionic
-   AWS 
-   AWS CLI
-   AWS Elastic Beanstalk
-   AWS s3 Buckets
-   CircleCI
-   Github
-   Git
-   Npm
-   Browser dev tools
-   HTML, CSS & Javascript
-   Angular

### Dependencies

```
- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```

### Installation

Provision the necessary AWS services needed for running the application:

1. In AWS, provision a publicly available RDS database running Postgres. 
1. In AWS, provision a s3 bucket for hosting the uploaded files. 
1. Export the ENV variables needed or use a package like [dotnev](https://www.npmjs.com/package/dotenv)/.
1. From the root of the repo, navigate udagram-api folder `cd starter/udagram-api` to install the node_modules `npm install`. After installation is done start the api in dev mode with `npm run dev`.
1. Without closing the terminal in step 1, navigate to the udagram-frontend `cd starter/udagram-frontend` to intall the node_modules `npm install`. After installation is done start the api in dev mode with `npm run start`.

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

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## License

[License](LICENSE.txt)

### Link to Application
http://uda-bucket-355177273640.s3-website-us-east-1.amazonaws.com/