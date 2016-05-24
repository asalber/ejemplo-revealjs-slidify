---
title       : Ejemplo de presentación con Revela.js y Slidify
subtitle    : 
author      : Alfredo Sánchez Alberca
framework   : revealjs              # {io2012, html5slides, shower, dzslides, ...}
revealjs    : {
  theme: night,                     # {black(default), white, league, sky, beige, blood, night, moon, solarized}
  transition: convex,               # {convex(default), fade, slide, concave, zoom, none}
  center: "true"}
mode        : selfcontained         # {standalone, draft}
knit        : slidify::knit2slides
---

# Título principal

---

## Título de la diapositiva

Texto de la diapositiva

--- &vertical

## Listas
Ver tipos de listas en diapositivas verticales

***

## Lista ordenada

1. Primer item
2. Segundo item
3. Tercer item
4. ...

***

## Lista desordenada

- Un item
- Otro item
- Otro item más
- ...

***

## Lista descubiertas

- .fragment Un item
- .fragment Otro item
- .fragment Otro item más
- .fragment ...

--- &vertical

## Imágenes

Imagen de tamaño original

![Molinos de Campo de Criptana](img/molinos.jpg)

***

## Imágen de tamaño personalizado

<img src="img/molinos.jpg" alt="Molinos de Campo de Criptana" width="400px">

--- ds:alert

## Diapositiva resaltada

Este contenido es importante.

--- &twocol &vertical

## Columnas
Diapositiva con columnas

*** =left

- point 1
- point 2
- point 3

*** =right

- point 1
- point 2
- point 3

***

## Prueba

