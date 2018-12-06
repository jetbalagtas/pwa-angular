# PwaAngular

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.1.1.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Working with a Service Worker

To work with Service Workers for a Progressive Web App, instead run `npm start` and navigate to `http://localhost:8080`. This will run the production version of the app (see note on building the production version with the `--prod` flag below). This command incorporates the `http-server -p 8080 -c-1 dist/pwa-angular` as described in the [Angular CLI Service Worker docs](https://angular.io/guide/service-worker-getting-started) at the time of this writing.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build. Note that Angular CLI adds Service Workers only to production builds (you can run `npm run build` which incorporates the flag previously mentioned).

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
