# MonitoringCpuFrontend [DEPRECATED]

Frontend for Monitoring-CPU-Useage Service. Provides the ability to add/edit/delete CpuObersvationEndpoints, wich the Monitoring-CPU-Useage Service should observe. Communicates with Monitoring-CPU-Useage Service via Sockets, to recieve the latest Cpu Status for each CpuObservationEndpoint.

![Frontend for Monitoring-CPU-Useage Service Screenshot](https://github.com/ccims/monitoring-cpu-frontend/blob/master/readme-screenshot.png)


This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.0.

## Usage

When running the frontend, make sure the Monitoring-CPU-Useage Service (Backend) is also running and for best demo services, also have the Database Service (or any other Service with Cpu Monitoring capabilities) running, to observe Cpu Load changes.

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
