<p align="center">
  <img src="https://github.com/Mariq12/challenge-aluraflix/assets/101030215/5c142c8f-588f-460f-94e8-d3c20b975917" alt="LogoMain"/>
</p>

# Challenge AluraFlix v2
<p align="right">
   <img src="https://img.shields.io/badge/STATUS-%20COMPLETADO-green">
   </p>

## Índice

* [Título e imagen de portada](#Título-e-imagen-de-portada)

* [Insignia](#insignia)

* [Índice](#índice)

* [Descripción del proyecto](#descripción-del-proyecto)

* [Características](#características)

* [Creación del proyecto](#creación-de-proyecto)

* [Instalación](#instalación-🔧)
* [Acceso al proyecto](#📁-acceso-al-proyecto)

* [Tecnologías](#✔️-tecnologías)

* [Tecnologías secundarias](#tecnologías-secundarias)

* [Herramientas](#🛠️-herramientas)

* [Personas colaboradoras](#personas-colaboradoras)

* [Autora](#autora)

## Descripción del proyecto
Aluraflix es una plataforma diseñada para gestionar vídeos, con funcionalidades como listar, registrar, actualizar y eliminar videos, implementando React con JavaScript. Ayudará a poner en práctica y reforzar tus conocimientos en esta librería, tales como componentización, uso de hooks, consumo de API, rutas entre otros.

### ⚠️ Atención
Este proyecto utiliza un servidor falso creado con [My JSON Server](https://my-json-server.typicode.com/).

## Características
### Gestión de Videos:

- Listar videos
- Registrar (agregar) videos
- Actualizar información de videos
- Eliminar videos

### Funcionalidades de React:
- `Componentización:`Desarrollar una aplicación modular dividiendo la interfaz de usuario en componentes reutilizables.
- `Uso de Hooks:`Implementar y manejar estados y efectos secundarios en componentes funcionales usando hooks como useState, useEffect, etc.
- `Consumo de API:`Realizar peticiones HTTP a una API para obtener, enviar, actualizar y eliminar datos de videos.
- `Manejo de Rutas:`Implementar navegación entre diferentes vistas o páginas dentro de la aplicación utilizando herramientas como React Router.

## Creación de proyecto
Ejecutar el comando:

    npm create vite@latest

Nombre: 
    
    challenge-aluraflix

Seleccionar:

    React
    JavaScript
Ejecutar:

    cd challenge-aluraflix
    npm install
    npm rin dev

### Opcional
En el script del package.json se agrega `start` 

        "scripts": {
        "start": "vite",
        "dev": "vite",
        },

Se ejecuta el proyecto con:

     npm start
Inicia el proyecto en [http://localhost:5173/](http://localhost:5173/) 

## Instalación 🔧
1. Instalar [react-router-dom](https://www.npmjs.com/package/react-router-dom), ejecutando el comando:

        npm i react-router-dom

    Es una dependecia de react que se utiliza para trabajar con las rutas.


2. Instalar [react-icons](https://react-icons.github.io/react-icons/search/#q=MdFavorite)

        npm install react-icons

3. Instalar del paquete de **[React-Loaders-Kit](https://seimodei.github.io/react-loaders-kit-examples/)**, ejecuando en cmd dentro del proyecto:

    npm i --save react-loaders-kit

    Creación del componente Loading.
    Conectar en el App.jsx.

4. Instalar [Styled Components](https://www.npmjs.com/package/styled-components), para escribir css en el JavaScript.

        npm i styled-components

    Documentación de [styled-components](https://styled-components.com/docs/basics)

5. Descargar [Normalize.css](https://necolas.github.io/normalize.css/), para que los navegadores muestren los elementos de forma consistente y acorde con los estándares modernos.

    **Pasos a realizar:**
    1. Ingresar a Normalize.css.
    2. Dar clic en descargar.
    3. Seleccionar el contenido con:
    
            Ctrl + a (selecciona)

            Ctrl + v (pega)

        Se pega el dentro del archio GlobalStyles.jsx, pero se debe eliminar los comentarios.

        *Ruta:*

            src
            ├── components
            │   ├── globalStyles
            │   │   ├── GlobalStyles.jsx

**🚨 Importante**

6. Instalar el paquete de rollup -D

        npm install rollup -D

   Para solucionar el siguiente error que muestra al deplegar el proyecto en Vercel:

   ![error](https://github.com/Mariq12/challenge-aluraflix-v2/assets/101030215/b1a17de6-ca32-44c2-befe-367ee2fe34e4)


## 📁 Acceso al proyecto

### Deploy del proyecto en Vercel
1. Se crea una carpeta dist ejecutando el comando:

        npm run build

2. Comentar la carpeta "dist" en gitignore

            #dist

3. Subir la carpeta dist a GitHub.*


### Demo
![challenge-aluraflix-v2](https://github.com/Mariq12/challenge-aluraflix-v2/assets/101030215/80aee34d-c381-430e-9a8b-3a8674e8ec02)

Ver demo en [Vercel](https://challenge-aluraflix-v2.vercel.app/)

Ver API falsa en [GibHub](https://github.com/Mariq12/api-challenge-aluraflix)

---
## ✔️ Tecnologías
* [React + Vite](https://vitejs.dev/guide/)
* JavaScript

## Tecnologías secundarias
* Node.js y npm (incluyendo node_modules)
* [My JSON Server](https://my-json-server.typicode.com/)
* VsCode
* Git
* GitHub



## 🛠️ Herramientas
### Gestión
* **Trello:** Se encuentran las tareas para realizar el proyecto.

### Diseño
* [Figma](https://www.figma.com/design/fq7mKIvvVXYylv8eti3hjm/New-AluraFlix---ESP?node-id=1-106&t=HWLfNcrrMRgRcBBC-0) el quipo de Alura creó un modelo que muestra una representación visual del AluraFlix. Sin embargo, pueden haber algunos cambios en el proceso.

## Personas colaboradoras
**Alura Latam** organizó el Challenge AluraFlix y proporcionó las herramientas de gestión y diseño.


## Autora
[<img src="https://avatars.githubusercontent.com/u/101030215?v=4" width=155><br><sub>Flor María Labanda Puchaicela</sub>](https://github.com/Mariq12)
