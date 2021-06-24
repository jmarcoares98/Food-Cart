# CertificationProject

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.0.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

# To run the app

You have to setup two json servers. Install json-server globally `npm install -g json server`.

## start json server by providing the json file

My json files are food.json and users.json. In one terminal write `json-server --watch src/assets/data/users.json` (this would automatically watch through port 3000) and in another terminal write `json-server --watch src/assets/data/food.json -p 4000`

## Now run the app

You can run the app with another terminal by doing `ng serve -o` and you can login through email: frankocean@email.com password: godspeed
