# Files Manager

A simple file management API built with Express, MongoDB, Redis, Bull, and Node.js.

## Requirements

### Applications

+ Node.js
+ Yarn (the package manager/resource negotiator)

### APIs

+ A Google API should be created with at least an email sending scope and a valid URL (e.g.; `http://localhost:5000/`) should be one of the redirect URIs. The `credentials.json` file should be stored in the root directory of this project.

## Installation

+ Clone this repository and switch to the cloned repository's directory.
+ Install the packages using `yarn install` or `npm install`.

## Usage

Start the Redis and MongoDB services on your system and run `yarn start-server` or `npm run start-server`.

## Tests

+ Create a separate `.env` file for the tests named `.env.test` and store the value of the environment variables for the testing event in it.
+ Run `yarn test` or `npm run test` to execute the E2E tests.

