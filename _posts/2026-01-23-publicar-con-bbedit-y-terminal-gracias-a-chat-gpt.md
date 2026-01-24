---
title: "Publicar un blog en GitHub Pages desde la terminal (sin saber casi nada)"
date: 2026-01-23 18:11:27 +01:00
author: Cruz Mendoza
tags:
  - aprendizaje
  - escribir
  - ia
  - github
---

No tengo formación como programador ni experiencia previa creando páginas web. Sé escribir, sé usar un editor de texto y me defiendo en la terminal lo justo para no tenerle miedo. Y, aun así, este blog existe y está publicado.

El reto que me he planteado ha sido muy concreto: **¿puedo publicar un blog usando solo las herramientas que ya tengo en el ordenador, sin servicios de terceros, sin CMS, sin pagar nada y sin “magia”?**  
La respuesta ha sido sí.

## El punto de partida

Partía de algo muy simple:

- Uso **BBEdit** desde hace años para escribir en Markdown.
- Trabajo habitualmente en la **terminal** de macOS.
- Tengo cuenta en **GitHub**, pero la uso poco. La [calculadora de plazos](https://umerez.eu/2026/01/06/calculadora-de-plazos-procesales-y.html), alojada en GitHub, ha sido un buen primer experimento.
- No sabía nada de Jekyll, GitHub Pages ni de cómo “se publica” una web.

La idea era escribir como siempre —archivos de texto— y que esos archivos acabasen convertidos en una página pública, accesible desde cualquier sitio.

## El acompañamiento de ChatGPT

Aquí entra ChatGPT. No como una varita mágica, sino como **alguien que va explicando qué hacer y por qué**, paso a paso, sin dar nada por supuesto.

El proceso ha sido deliberadamente artesanal:

- entender qué es Git y qué no es,
- crear una carpeta vacía,
- inicializar un repositorio,
- escribir archivos Markdown,
- aprender cuándo hay que hacer `git add`, `git commit` y `git push`,
- equivocarme,
- atascarme en un *merge*,
- salir de un editor que no sabía ni que existía (sí, vim),
- y seguir.

Nada ha sido automático, pero **todo ha sido comprensible**.

## Escribir sin cambiar de hábitos

Una de las cosas más atractivas de este sistema es que **no me obliga a cambiar cómo escribo**.

- Escribo en BBEdit.
- Archivos Markdown planos.
- Sin formularios web.
- Sin editores enriquecidos.
- Sin dependencias raras.

Los borradores viven en una carpeta `_drafts`.  
Los textos publicados pasan a `_posts`, con una fecha en el nombre.  
Ese simple gesto decide qué es privado y qué es público.

No hay botones de “publicar”.  
Hay una terminal y un comando.

## Publicar como un artesano

Cuando un texto está listo:

1. Muevo el archivo.
2. Añado la fecha.
3. Hago un commit.
4. Hago un push.

Un par de minutos después, el artículo está online y aparece en el RSS.

No hay base de datos.  
No hay backend.  
No hay suscripciones.  

Solo texto, control de versiones y un servicio gratuito que hace exactamente lo que promete.

## La satisfacción inesperada

Lo más interesante de todo el proceso no ha sido “tener un blog”, sino **entender cómo funciona**.

Saber:
- dónde están mis textos,
- qué se publica y por qué,
- qué ocurre cuando algo falla,
- cómo arreglarlo.

Hay algo muy atractivo en publicar así:  
con herramientas que ya tienes, de forma consciente, casi manual, **como lo haría un programador**, aunque no lo seas.

## Un blog como cuaderno de pruebas

Este blog no tiene una temática cerrada. Será un lugar para:

- opinión,
- notas personales,
- productividad,
- uso de IA,
- herramientas,
- experimentos.

Y también para seguir aprendiendo cómo funciona todo esto.

No es un producto.  
No es una marca.  
Es un cuaderno publicado.

Y eso, gracias a una buena guía y a un poco de paciencia, está al alcance de cualquiera.
