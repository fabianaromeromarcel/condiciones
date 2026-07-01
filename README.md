# Desafío - Condiciones

Este proyecto corresponde al desafío **Condiciones** del módulo **JavaScript para la Web** de Desafío Latam.

## Descripción

La aplicación está compuesta por tres requerimientos independientes que utilizan estructuras condicionales en JavaScript.

### Requerimiento 1

- Al hacer clic sobre una imagen, se agrega un borde rojo de 2 píxeles.
- Al volver a hacer clic, el borde desaparece.

### Requerimiento 2

- El usuario puede ingresar la cantidad de tres tipos de stickers.
- Se calcula el total de stickers seleccionados.
- Si el total es menor o igual a 10, se muestra la cantidad seleccionada.
- Si el total supera los 10 stickers, se informa que lleva demasiados.
- También se valida que no se ingresen números negativos.

### Requerimiento 3

- El usuario selecciona un número en cada uno de los tres `<select>`.
- Se forma un password de tres dígitos.
- Si el password es **911**, se muestra el mensaje:
  - `Password 1 correcto 🥳`
- Si el password es **714**, se muestra el mensaje:
  - `Password 2 correcto 🥳`
- Para cualquier otra combinación, se muestra:
  - `Password incorrecto 🔐`

## Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript

## Estructura del proyecto

```
desafio-condiciones/
│
├── index.html
├── requerimiento1.html
├── requerimiento2.html
├── requerimiento3.html
│
└── assets/
    ├── css/
    │   └── style.css
    ├── img/
    └── js/
        └── script.js
```

## Demo

- **GitHub Pages:** https://fabianaromeromarcel.github.io/condiciones/