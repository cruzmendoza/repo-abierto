# Repo Abierto

Blog personal escrito en Markdown con BBEdit y publicado en GitHub Pages desde la terminal.

Este repositorio contiene:
- borradores versionados,
- artículos publicados,
- y la configuración mínima del blog.

No hay backend, base de datos ni CMS.

---

## Estructura del repositorio

```
repo-abierto/
├── _drafts/     # Borradores (no se publican)
├── _posts/      # Artículos publicados
├── _config.yml  # Configuración del blog
└── index.md     # Portada
```
---

## Flujo de trabajo

### 1. Crear un borrador

Crear un archivo nuevo en `_drafts/` (sin fecha):

_drafts/articulo-ejemplo.md

Contenido mínimo recomendado:

```markdown
---
title: "Título provisional"
author: Cruz Mendoza
tags:
  - ejemplo
  - notas
---

Texto en elaboración.
```

⸻

### 2. Versionar un borrador

Cada avance relevante se guarda en Git.
```
git status
git add _drafts/articulo-ejemplo.md
git commit -m "Borrador: describir el cambio realizado"
```
Los borradores:
	•	no se publican,
	•	no aparecen en el RSS,
	•	pero sí quedan respaldados en GitHub.

⸻

### 3. Publicar un artículo

#### 3.1 Mover el archivo a _posts/
Elegir la fecha de publicación (YYYY-MM-DD) y mover el archivo:
```
git mv _drafts/articulo-ejemplo.md \
       _posts/2026-02-01-articulo-ejemplo.md
```

#### 3.2 Actualizar el front matter
Editar el archivo ya en _posts/ y añadir la fecha:
```
---
title: "Título definitivo"
date: 2026-02-01
author: Cruz Mendoza
tags:
  - ejemplo
  - opinion
---
```
Guardar.

#### 3.3 Publicar (regla segura)
Antes del commit de publicación, añadir siempre el archivo:
```
git add _posts/2026-02-01-articulo-ejemplo.md
git commit -m "Publicar: Título definitivo"
git push
```

⸻

### Reglas importantes
	•	Nada se publica si no está en _posts/ con fecha.
	•	git mv conserva el historial del borrador.
	•	Editar un archivo siempre requiere git add antes del commit.
	•	El feed RSS se actualiza automáticamente con cada publicación.

⸻

### Convenciones de commits
	•	Borrador: … → cambios en _drafts/
	•	Publicar: … → publicación de un artículo
	•	Otros commits → configuración o ajustes técnicos

⸻

### Tecnología
	•	Markdown
	•	Jekyll (GitHub Pages)
	•	Tema: minima
	•	Feed RSS: /feed.xml

⸻

### Publicación

El blog se publica automáticamente en GitHub Pages al hacer git push.
La URL y el dominio dependen de la configuración de Pages.
