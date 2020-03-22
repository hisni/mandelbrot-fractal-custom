# Fractal Image Standalone Component

This standalone component works as a generic component to display fractal-images using the the input request, rendered on a webserver. 

*This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.1.0.*

## Local Build

* Install Angular CLI version 7.1.0.
* Clone this repository and run `npm install` in the project root.
* Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.
* **Using it as a component:**
  After building the project, you may use it as a component in some different webapp.
  * Import the files `main.js`, `polyfills.js` and `runntime.js` present in the `dist/fractal-custom` directory.
  * Use `<fractal-image>` with the parameters in the form of a JSON string passed as the `settings` argument, and `position` or `velocity` mode as the `motion` argument.
  * Eg. `<fractal-image motion='position' settings={"max_depth":1225,"renderer":"cpp","darken":true,"colors":2,"edge":0,"modes":66,"texture":0,"three_d":false,"eye_adjust":0,"var1":0,"var2":0,"brighten":0}>`

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
