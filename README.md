# MasterWay

MasterWay es un proyecto web enfocado en las recomendaciones a través de publicaciones de usuarios para que otros conozcan nuevos lugares, ya sean restaurantes, lugares imperdibles, etc.  

Este proyecto fue realizado con React, JavaScript y TypeScript.

![Banner](https://cdn.phototourl.com/uploads/2026-02-27-eaca587f-c9c4-4b47-a8d6-209f571ff9dc.png)  

## ✨ Características principales
- Interfaz Home donde los usuarios pueden ver publicaciones de lugares de otros usuarios. 
- Las publicaciones tienen descripción, país y ciudad, calificación de estrellas de 1 a 5, categoría: hoteles, restaurantes, tours, sitios turísticos.
  También cuenta con una sección de comentarios publicados y añadir nuevo.
- Interfaz Favoritos para guardar publicaciones que le gusten al usuario.
- Interfaz de dashboard donde se encuentran el perfil de usuario y el calendario.
- Sistema de calendario donde se pueden crear eventos con nombre, descripción, fecha inicial y final, hora inicial y final. Los eventos se mostrarán marcados en el calendario.
- Interfaz de usuario donde se puede editar el nombre de usuario, nombre completo, email, teléfono, descripción, foto de perfil.

## 🛠️ Tecnologías principales
- **JavaScript** / **TypeScript**
- **Node.js** 
- **React** 
- **VS Code**
- **Firebase**

## 🚀 Instalación y ejecución local

### Prerrequisitos 
- Node.js ≥ 18
- npm / pnpm / yarn
- VS Code instalado

### Pasos rápidos
1. Clona el repositorio
   ```bash
   git clone https://github.com/SebastianBustosDev/MasterWay.git
   cd MasterWay

2. Reemplazar keys de Firebase en archivo .env
   ```bash
   EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_test_ZmxlZXQtcG9sZWNhdC03OS5jbGVyay5hY2NvdW50cy5kZXYk
   EXPO_PUBLIC_FIREBASE_API_KEY=AIzaSyAsAoX0BF5MBZhxF3HHQYCOlGPfYipS16E
   
3. Instalar las librerías en la terminal
   ```bash
   npm install

4. Acceder a la carpeta raíz del proyecto
   ```bash
   cd App-MasterWay

5. Instalar librerías y dependencias necesarias de la carpeta raíz
   ```bash
   npm install

6. Ejecutar proyecto
   ```bash
   npm start

7. Copiar url del proyecto en el navegador. La url se ve así:
   ```bash
   http://localhost:8081
   


## 📂 Estructura del proyecto

| Carpeta / Archivo       | Descripción principal                                          |
|-------------------------|----------------------------------------------------------------|
| `App-MasterWay`         | Carpeta principal del proyecto que contiene el código fuente   |
| `app`                   | Contiene el calendario, index, tabs y auth de usuarios         |
| `components`            | Contiene toda la lógica de las interfaces home, favoritos, etc.|
| `node_modules`            | carpeta de dependencias|
| `.gitignore`            | Ignorar node_modules, .env, etc.                               |
| `README.md`             | Esta documentación                                             |
| `package.json` (raíz)   | Dependencias globales                                          |


## 🤝 Contribuidores
- Thiago7603 — Desarrollador fullstack
- MarianaGaleano — Desarrollador fullstack
- SebastianBustosDev — Desarrollador fullstack
