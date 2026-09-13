# RRHH Angular

Frontend desarrollado con **Angular** para la gestión de empleados: listado, alta, edición y eliminación de registros (nombre, puesto y cargo). Consume la API REST de [rrhh-flask-api](https://github.com/brianmatiasllampa/rrhh-flask-api).

## Tecnologías

- Angular
- TypeScript

## Requisitos previos

- Node.js (v18+ recomendado)
- El backend [rrhh-flask-api](https://github.com/brianmatiasllampa/rrhh-flask-api) corriendo en `http://localhost:8080`

## Instalación

1. Cloná el repositorio:
   ```bash
   git clone https://github.com/brianmatiasllampa/rrhh-angular.git
   cd rrhh-angular
   ```

2. Instalá las dependencias:
   ```bash
   npm install
   ```

## Uso

```bash
ng serve
```

La aplicación queda disponible en `http://localhost:4200`.

> Asegurate de tener el backend Flask corriendo antes de levantar el frontend, ya que la app consume la API en `http://localhost:8080/api/empleados` (configurado en `src/app/empleados/empleado.service.ts`).

## Funcionalidades

- Listado de empleados
- Alta de nuevo empleado
- Edición de empleado existente
- Eliminación de empleado

## Proyecto relacionado

- Backend: [rrhh-flask-api](https://github.com/brianmatiasllampa/rrhh-flask-api)
