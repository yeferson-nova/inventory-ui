# Inventory UI

Este proyecto es una aplicación web frontend desarrollada en Angular para gestionar un inventario. La aplicación incluye un módulo principal `Dashboard` con un componente `Home` que sirve como punto de entrada.

## Estructura del Proyecto

El proyecto sigue una estructura modular que facilita la escalabilidad y el mantenimiento. A continuación se describe la estructura principal:

- **src/**: Carpeta principal que contiene el código fuente del proyecto.
  - **app/**: Carpeta que contiene el módulo principal de la aplicación y sus componentes.
    - **modules/**: Carpeta que contiene los módulos específicos de la aplicación.
      - **dashboard/**: Módulo que gestiona el dashboard de la aplicación.
        - **component/**: Carpeta que contiene los componentes específicos del módulo dashboard.
          - **home/**: Componente `Home` dentro del módulo `Dashboard`.
        - **pages/**: Carpeta que contiene las páginas principales del módulo `Dashboard`.
          - **dashboard.component.ts**: Componente principal del módulo `Dashboard`.
        - **dashboard-routing.module.ts**: Módulo de enrutamiento para el módulo `Dashboard`.
        - **dashboard.module.ts**: Módulo `Dashboard` que agrupa los componentes y rutas.
      - **router-child.module.ts**: Módulo que gestiona las rutas secundarias dentro del `Dashboard`.
    - **app-routing.module.ts**: Módulo de enrutamiento principal de la aplicación.
    - **app.component.ts**: Componente raíz de la aplicación.
    - **app.module.ts**: Módulo principal de la aplicación.

## Scripts Disponibles

En el directorio del proyecto, puedes ejecutar:

### `ng serve`

Inicia la aplicación en modo de desarrollo. Abre [http://localhost:4200](http://localhost:4200) para verlo en el navegador.

### `ng build`

Compila la aplicación para producción en la carpeta `dist/`.

### `ng test`

Ejecuta las pruebas unitarias utilizando [Karma](https://karma-runner.github.io).

### `ng lint`

Ejecuta la herramienta de linting para asegurar que el código siga las mejores prácticas.

## Dependencias

El proyecto utiliza varias dependencias clave:

- **Angular**: Framework principal utilizado para el desarrollo de la aplicación.
- **Angular Router**: Utilizado para la navegación y enrutamiento dentro de la aplicación.
- **TypeScript**: Lenguaje utilizado para desarrollar la aplicación.

## Instalación

Para configurar el proyecto en tu entorno local, sigue estos pasos:

1. Clona este repositorio: `git clone https://github.com/yeferson-nova/inventory-ui.git`
2. Navega al directorio del proyecto: `cd inventory-ui`
3. Instala las dependencias: `npm install`
4. Inicia la aplicación: `ng serve`

## Contribuciones

Las contribuciones son bienvenidas. Puedes hacerlo a través de pull requests.

## Licencia

Este proyecto está bajo la licencia MIT.
