# Express API template
[![Build Status](https://travis-ci.com/anthenywells/express-api-template.svg?branch=main)](https://travis-ci.com/anthenywells/express-api-template)
[![Coverage Status](https://coveralls.io/repos/github/anthenywells/express-api-template/badge.svg?branch=main)](https://coveralls.io/github/anthenywells/express-api-template?branch=main)
[![Maintainability](https://api.codeclimate.com/v1/badges/97dd0e9818ad178adc03/maintainability)](https://codeclimate.com/github/anthenywells/express-api-template/maintainability)
[![Build status](https://ci.appveyor.com/api/projects/status/yk0xutuk1xjh0606?svg=true)](https://ci.appveyor.com/project/anthenywells/express-api-template)

## How to run the app

1. Clone the repo
1. Create a `.env` file at the project root and provide the following environment variables

    TEST_ENV_VARIABLE="some arbitrary string"
    CONNECTION_STRING="a url pointing to a PostgreSQL database"
    PORT="port number to serve the files. defaults to 3000"

1. Open a terminal in the project root and run `yarn install` to install the project dependencies.
1. Run `yarn test` to make sure everything is working correctly.
1. Run `yarn startdev` to start the development server
1. Open `http://localhost:3000` or use whatever port you supplied in your environment variable.
1. Remember to replace the badges with your custom badges

## How to test

1. Run `yarn install` to install project dependencies
1. Run `yarn test`

