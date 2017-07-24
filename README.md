## About copay-recovery
A simple UI to recover funds from Copay backups.

## Installation
Get the source code:

```
git clone git@github.com:bitpay/copay-recovery.git && cd copay-recovery
```

Open index.html in your browser

## Public Installation

There is a public install of this software hosted at github at: 
https://bitpay.github.io/copay-recovery/

# CopayRecoveryNg4app

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.2.1.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

## Publish web on Github Pages (gh-pages)

### Install:
npm i -g angular-cli-ghpages

### Build:
build --prod --aot=false --base-href "https://USER.github.io/APP-NAME/"

(see base-href on your repo settings)

### To publish the web:
go to master branch and run:
ngh

Successfully published!
