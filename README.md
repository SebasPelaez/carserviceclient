# CarServiceClient

## Detalle del desarrollo del laboratorio

* **Componentes:** Se crearon dos componentes totalmente nuevos _Owner-edit_ y _Owner-list_ y se modificaron los componentes _Car-list_ y _Car-edit_
> Owner-edit: Por medio de este componente podremos actualizar la información personal de cada uno de los propietarios de los vehículos.

> Owner-list: Este componente nos muestra la lista actual de propietarios de vehículos, por medio de ella también podemos seleccionar para editar o borrar propietarios.

> Car-list: En este componente se agrego la capacidad de visualizar quien es el propietario del vehículo en cuestión.

> Car-edit: En este componente ahora se puede agregar el propietario del vehículo.

* **Servicios**: Se crearon 4 servicios para los componentes desarrollados, todos estos estan construidos en el archivo _owner.service_
> getAll(): Me permite traer todos los propietarios de vehículos.

> get(owner): Me trae en partícular un propietario.

> save(owner): Me guarda la información de un propietario.

> remove(href): Este servicio me ayuda a eliminar un propietario.

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
