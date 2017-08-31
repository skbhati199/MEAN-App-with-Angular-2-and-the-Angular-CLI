# MEAN BookApp with Angular 2 and the Angular CLI 
MEAN App with Angular 2 and the Angular CLI

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.3.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## How to use :

To make the server run from bin/www, open and edit "package.json" then replace "start" value.

`"scripts": {
   "ng": "ng",
   "start": "node ./bin/www",
   "test": "ng test",
   "pree2e": "webdriver-manager update --standalone false --gecko false",
   "e2e": "protractor"
 },`
 
 `npm install --save express body-parser morgan body-parser serve-favicon`
 
 `ng build`
 
 `npm start`
 
## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
