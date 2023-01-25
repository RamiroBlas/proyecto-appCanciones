# proyecto-appCanciones
# Proyecto Unidad 07
_Integrantes_
* Ramiro Blas Galicia

Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas.
Mira **Instalación** para conocer como desplegar el proyecto.

## Pre-requisitos 

_Que cosas necesitas para instalar el software y como instalarlas_

## Pasos a realizar para ejecutar:

Instalar dependencias

```
  npm install
```
Instalar el directorio dist
```
  npx tsc --init
```

Realizar migraciones

```
  npx prisma migrate dev --name init
```

Correr el proyecto

```
  npm run dev
```