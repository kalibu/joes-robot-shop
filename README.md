# JoesRobotShop

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.0.0.

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


##Backend do projeto - serviços
Pasta: api-server -> Node
URL: http://localhost:8081

1) get:  /api/products -> lista de produtos
2) post: /api/cart     -> recebe lista de produtos do carrinho
3) get:  /api/cart     -> retorna lista de produtos no carrinho
4) post: /api/register -> registra usuario
5) post: /api/sign-in  -> valida usuario para login

##Frontend
Arquivo proxy.conf.json -> tem o de/para para apontar para os serviços em localhost...
Sobe em http://localhost:4200/

##Passo a Passo
Inicializar o projeto:
1) npm install
2) npm start

* precisa inicializar o back e o front