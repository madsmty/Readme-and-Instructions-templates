# Node challenge: Pet Adoption RESTful API

# 1. Overview

This repository is intended to be a quick template to help practice API concepts with NodeJS.

A local animal shelter wants to create a website to facilitate pet adoption. The overall project seeks to create a platform that connects potential adopters with pets available for adoption.
The platform should allow admin users to view and manage pet profiles, review, and approve or reject open adoption requests. 
The public side of the API it should allow users to view pets available for adoption as well as submit adoption requests.

# 2. Environment Prerequisites

## Windows
1. Install NVM.
	[Windows](https://www.freecodecamp.org/news/node-version-manager-nvm-install-guide/)
2. Install Node JS (LTS) and set it as default
    ```
    nvm install 20.11.0
    nvm alias default 20.11.0
    ```
## MacOs

## Linux


# 3. Build Instructions

1. Install yarn globally for dependency management.
    `npm install yarn -g`
2. Fork this repository and download it locally.
3. Go to the root directory of the repository and run this command to download the initial dependencies.
    `yarn install` 
4. After installing the project you can run this command to configure the database.
    `yarn run db:seed` 
5. Run the project.
    `yarn run dev`
6. Run unit tests
    `yarn run test`

# 4. Instructions

## 4.1 Functional Requirements
In this [link](./ functional_requirements_example.md) you will find the definition of all expected CRUD endpoints.

## 4.2 Business Rules

In this [link](./business_rules_example.md) you will find the ....

## 4.3 Technical Requirements

* Use TypeScript for server-side development (don't use any).
* Implement Express.js to create the RESTful API.
* Use SQLite or another suitable database to store pet and user data.
* Apply proper error handling and validation throughout the application.
* Include unit tests for critical features and components using Jest.

# 5. Testing and Validation Requisites - TBD

# 6. Acceptance Criteria

## [Evaluation criteria](./evaluation_criteria_example.md)
## [Expected documentation and deliverables](./documentation_example.md)

# 7. Resources

* Boilerplate repositories where this exercise was based
    * https://github.com/mwolfhoffman/node-jwt-sqlite-typescript-starter
    * https://github.com/Chensokheng/rest-api/tree/master
* [Introducción a NodeJS](https://nodejs.org/en/learn/getting-started/introduction-to-nodejs) 
* [Ethereal Email](https://ethereal.email/): Fake SMTP service to simulate email sending.
    * [Using nodemailer with ethereal example](https://dev.to/berviantoleo/email-testing-using-ethereal-inb)
* [Manual oficial Typescript](https://www.typescriptlang.org/docs/handbook/2/basic-types.html)
## Source of seed information used in this repo
* [Dog breeds](https://github.com/jfairbank/programming-elm.com/blob/master/dog-breeds.json)
* [Cat breeds](https://github.com/jfairbank/programming-elm.com/blob/master/cat-breeds.json)

