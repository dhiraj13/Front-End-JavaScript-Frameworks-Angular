# ConFusion

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.2.1.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

#json-server

I have load my data in the json-serve, which is a simple server to support a REST API server. It is also used for static content from a folder
  i) Setting up json-server
    -> Install the json-server globally by typing the following command
       npm install json-server -g
    -> If you're using OSX or Linux, use sudo at the front of the command
  ii) Configuring the server
    -> Create a folder named json-server and move to this folder
    -> Download db.json file
    -> Create a folder named public inside json-server folder and place any resources within it, it will served by the server.
    -> In Our case,
