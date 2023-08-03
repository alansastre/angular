
## 1. Nodejs

https://nodejs.org/en

* `node --version`

## 2. Visual Studio Code IDE

https://code.visualstudio.com/

Extensiones:

* vscode-icons
* Angular Essentials
* Angular Language Service

## 3. Instalar Angular

https://angular.io/guide/versions

npm install -g @angular/cli@latest

ng version

## 4. Crear proyecto Angular

ng new frontend --routing=true --skip-git --style=css

ng serve

`Ctrl + C` permite parar la aplicación.

## 5. Crear modelo, componentes y servicio

ng generate component book-list
ng generate component book-detail
ng generate component book-form

ng generate interface models/book --type=model --prefix=I
ng generate service services/book

## 6. Enrutado

app-routing.module.ts

## 7. Angular Material

https://material.angular.io/

https://fonts.google.com/icons

ng add @angular/material

Importar los siguientes módulos en app.module.ts:

MatTableModule,
MatIconModule,
MatButtonModule,
MatGridListModule,
MatCardModule,
MatDividerModule,
MatToolbarModule

Hacer el listado de libros book-list y el detalle de un libro book-detail.

ng generate component layout/navbar
ng generate component layout/footer