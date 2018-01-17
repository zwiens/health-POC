## Prerequisites
1. Install [Node.js](https://nodejs.org) and [MongoDB](https://www.mongodb.com)
2. Install Angular CLI: `npm i -g @angular/cli`
3. From project root folder install all the dependencies: `npm i`

## Run
### Development mode
`npm run dev`: [concurrently](https://github.com/kimmobrunfeldt/concurrently) execute MongoDB, Angular build, TypeScript compiler and Express server.

A window will automatically open at [localhost:4200](http://localhost:4200). Angular and Express files are being watched. Any change automatically creates a new bundle, restart Express server and reload your browser.

### Production mode
`npm run prod`: run the project with a production bundle and AOT compilation listening at [localhost:3000](http://localhost:3000) 

## Please open an issue if
* you have any suggestion to improve this project
* you noticed any problem or error

## To do

## Running frontend unit tests
Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running frontend end-to-end tests
Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/). 
Before running the tests make sure you are serving the app via `npm start`.

## Running backend tests
Run `mongod` to run an instance of MongoDB, then run `npm run testbe` to execute the backend tests via [Mocha](https://mochajs.org/).

## Running TSLint
Run `ng lint` (frontend) and `npm run lintbe` (backend) to execute the linter via [TSLint](https://palantir.github.io/tslint/).

## Wiki
To get more help about this project, [visit the official wiki](https://github.com/DavideViolante/Angular-Full-Stack/wiki).

## Further help
To get more help on the `angular-cli` use `ng --help` or go check out the [Angular-CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

### Author
* Zachary Wiens. Special thanks to: [Davide Violante](https://github.com/DavideViolante) who provided the MEAN stack starter kit.
