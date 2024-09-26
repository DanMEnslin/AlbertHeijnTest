# Albert Heijn API Test

## Local Install instructions

The Github Action will run the tests on Github, but can also be run locally by followiing the below instructions:

Prerequsite:
- Node, NPM installed

Installation:
- run `npm install -g newman` to install Newman
- run `npm install -g newman-reporter-htmlextra` to install the html reporter
- run `newman run ./RijksMuseumTestDanielE.postman_collection.json -e ./RijksMuseumEnv.postman_environment.json -r htmlextra` to run the API tests