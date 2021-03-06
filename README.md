
# 馃悵 Bees App

Es una aplicaci贸n web que permita el registro, eliminaci贸n, b煤squeda de contactos (bees 馃悵) y paginaci贸n de resultados.

![App Screenshot](https://res.cloudinary.com/images-alex-projects/image/upload/v1635231627/Portfolio/bees-app/screenshots/desktop-version_b9coor.png)

## Features

- Listar contactos
- Paginaci贸n de contactos
- Registrar contactos
- Eliminar contactos
- Desktop y Mobile version
  
## Lessons Learned

Yo aprend铆 y practiqu茅 m谩s acerca de React.js, React Hooks, Redux (Reducers, Actions, Store), React Context y TypeScript.

  
## Run Locally

Clonar el proyecto

```bash
  git clone https://github.com/alxmcr/bees-app
```

Ir donde se encuentra el directorio del proyecto.

```bash
  cd bees-app
```

Install dependencies

```bash
  npm install
```

Iniciar el Frontend server

```bash
  npm run start
```

Extra: Iniciar [Backend server](https://github.com/Beetrack/frontend-test) (Backend API)

```bash
cd frontend-test
npm install
npm run start
```

Nota.- Es probable, que necesite:
- Cambiar el puerto del backend de 3000 a 4000 (Conflicto de puertos entre React y API).
- Instalar Nodemon para una r谩pida actualizaci贸n de la base de datos.
- Actualizar algunos links de imagenes, algunos links fuer贸n necesarios modificarlos.
 
## Environment Variables

Para arrancar el proyecto se necesita de variables de entorno(`.env`). Donde se puede, colocar en la ra铆z del proyecto: `bees-app/.env` (ver: `.env-sample`)

```
REACT_APP_BACKEND_API_BASE_URL=http://localhost:4000
```

## Rutas Habilitadas

- Inicio (`/`)
- Contacto (`/contacts/:id`)
  
## Tech Stack

HTML, CSS, Sass, JavaScript, Typescript, React.js, and Redux.

## Screenshoots

![Lista de Contactos - Screenshot](https://res.cloudinary.com/images-alex-projects/image/upload/v1635231627/Portfolio/bees-app/screenshots/desktop-version_b9coor.png)

![Create modal - Screenshot](https://res.cloudinary.com/images-alex-projects/image/upload/v1635391277/Portfolio/bees-app/screenshots/desktop-version-create-contact_rj4fsl.png)

![Mobile Version - Lista de Contactos - Screenshot](https://res.cloudinary.com/images-alex-projects/image/upload/v1635231627/Portfolio/bees-app/screenshots/mobile-version_bkm85c.png)

![Mobile Version - Eliminar Screenshot](https://res.cloudinary.com/images-alex-projects/image/upload/v1635231627/Portfolio/bees-app/screenshots/mobile-version-remove_hrnfbs.png)

  
## Authors

- [Alejandro M. Coca Rojas (@alxmcr)](https://www.github.com/alxmcr)
  
## Feedback

If you have any feedback, please reach out to me at amcocarojas@gmail.com.

  