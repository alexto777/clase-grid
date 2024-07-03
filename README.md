# Clase de CSS Grid

## Descripción

Esta clase está diseñada para enseñar los conceptos básicos y avanzados de CSS Grid, una herramienta poderosa para crear diseños web responsivos y complejos de manera sencilla. A través de ejemplos prácticos y ejercicios, aprenderás cómo utilizar CSS Grid para organizar y alinear contenido en tus páginas web.

## Estructura del Proyecto

- **index.html**: El archivo HTML principal que contiene la estructura básica de la página.
- **styles.css**: El archivo CSS que contiene las definiciones de estilo y las configuraciones de CSS Grid.

## Contenido

### 1. Introducción a CSS Grid

CSS Grid es un sistema de diseño bidimensional que te permite crear complejos diseños de cuadrícula en tu sitio web. Puedes definir filas y columnas, y colocar elementos de manera precisa en la cuadrícula.

### 2. Propiedades Básicas

#### Display Grid

Para empezar a usar CSS Grid, necesitas establecer el contenedor como una cuadrícula:
```css
.contenedor {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(3, 150px);
}
