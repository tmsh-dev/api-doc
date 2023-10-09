# Documentación de API RESTFUL con Swagger-cli

## Descripción
Este proyecto contiene la estructura básica para la documentación de una API RESTFUL con Swagger-cli, el cual es un generador de documentación de API's RESTFUL.

La documentación se distribuye en varios archivos .*yaml* para posteriormente ser compilados en un solo archivo .*json* el cual puede ser leído por Swagger UI.

- [Documentación de API RESTFUL con Swagger-cli](#documentación-de-api-restful-con-swagger-cli)
  - [Descripción](#descripción)
  - [Requerimientos](#requerimientos)
  - [Preparación del proyecto](#preparación-del-proyecto)

## Requerimientos
Para poder ejecutar este proyecto es necesario tener instalado [NodeJS](https://nodejs.org/es/) y [NPM](https://www.npmjs.com/). en las versiones especificadas.

- NodeJS: v18.17.0, o superior.
- NPM: v9.6.7, o superior.

## Preparación del proyecto
Para preparar el proyecto es necesario ejecutar el siguiente comando en la raíz del proyecto:

```bash
npm install
```
Este comando instalará todas las dependencias necesarias para el proyecto, que en este caso es solo una, la cual es [Swagger-cli](https://www.npmjs.com/package/swagger-cli).