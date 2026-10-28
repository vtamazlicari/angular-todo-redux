# RedProject

A todo app built with Angular 6 and NgRx (Redux pattern). You can list, add, edit and delete tasks.

- **State:** `@ngrx/store` holds the todo list, and `@ngrx/effects` makes the HTTP calls (`src/app/modules/todo/`).
- **Backend:** a REST API at `http://localhost:3004/todo`, backed by `db.json`. The API URL is set in `src/environments/environment.ts`.
- **UI:** Bootstrap 3 and ngx-bootstrap. Adding and editing tasks happens in a modal.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.0.8.

## Development server

Start the mock API (it uses [json-server](https://github.com/typicode/json-server), which isn't in `package.json`):

```
npx json-server --watch db.json --port 3004
```

Then run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

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
