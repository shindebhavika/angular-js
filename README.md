
#two way binding with ngmodal

<h1>Books</h1>
<button (click)="handleClick()" [disabled]="isDisabled">books</button>
<input type="text" [(ngModel)]="myName">
<p>{{myName}}</p>

<ul>
  <li>{{ name }}
    <img [src]="src" [alt]="name" />
  </li>
  <li>{{ name2 }}
    <img [src]="src2" [alt]="name2" />
  </li>
</ul>

# MyApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.1.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

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
