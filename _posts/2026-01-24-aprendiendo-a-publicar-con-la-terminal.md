---
title: "Aprendiendo a publicar con la Terminal"
author: Cruz Mendoza
date: 2026-01-24 18:00:00 +01:00
tags:
  - blogging
  - frikismos
---

He creado el primer borrador dentro de la carpeta de `_drafts` de mi repositorio, y ahora estoy editándolo con la esperanza de convertirlo en artículo y publicarlo en el blog.  

La primera duda es si tengo que poner el título del artículo al comienzo. Ya está dentro del *frontmatter* o cabecera, así que espero que eso sea suficiente para que el blog muestre el título sin tener que volver a escribirlo en el cuerpo del artículo.  

Otra duda se refiere también al lenguaje Markdown, o mejor dicho a la forma en la que Jekyll y GitHub Pages, o su plantilla Minimal, muestran la separación entre párrafos. 

Ahora mismo no estoy poniendo líneas adicionales entre párrafos, cada párrafo va en una línea, y espero que luego se muestre con suficiente espacio intermedio.  

> (ACTUALIZACIÓN: El formato inicial no funcionaba correctamente, ya que no había espacio entre las líneas. Para solucionarlo, he tenido que hacer dos pruebas. Primero, he añadido dos espacios al final de cada línea, lo que ha creado nuevos párrafos pero no ha generado un doble espacio. Por lo tanto, he tenido que editar el archivo por segunda vez, añadiendo líneas adicionales para conseguir el formato deseado).

El caso es que ahora estoy intentando recordar de memoria qué es lo que tendría que hacer para pasar este borrador a la carpeta de artículos, para proceder a publicarlo.  

Creo que tengo que dar los siguientes pasos:

- Guardar este artículo en GitHub para que tenga constancia de la nueva versión.
- Para eso tendré que hacer `git status`, `git add`, `git commit`y `git push`.
- Luego moveré el borrador a la carpeta de `_posts`, le pondré fecha, tanto en el nombre de archivo como en el *frontmatter*, y le daré un último repaso.
- Y a partir de ahí, de nuevo `git status`, `git add`, `git commit`y `git push` para publicar.  

Voy a dejarlo aquí y a hacer la prueba. Si no funciona así, tendré que volver a repasar las instrucciones.