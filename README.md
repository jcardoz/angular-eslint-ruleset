# MyAccessibleApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.2.8.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Lint

Run `ng lint` to lint the files using the standard es lint rules + accessibility rules.
Accessibility rules are set to throw an error (2). Change this to warning as per your requirement.
* Steps performed to setup eslint
    1. run the following command
        ```
        ng add @angular-eslint/schematics
        ```
    2.  Before v12, the Angular CLI shipped with a TSLint setup, so you should run the conversion schematic to automatically convert your new project from TSLint to ESLint:
        ```
        ng g @angular-eslint/schematics:convert-tslint-to-eslint --remove-tslint-if-no-more-tslint-targets --ignore-existing-tslint-config
        ```
        __Note__: If the above step fails with npm - run the following yarn command - 
        ```
        yarn add tslint-to-eslint-config@^2.3.0 --dev
        ```
        and then rerun step #2
    3. Rules are present here: [angular-eslint rules]( https://github.com/angular-eslint/angular-eslint#functionality)
## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
