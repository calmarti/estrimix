# Proyecto de plataforma web de streaming 'Estrimix'

### Ivan Martínez Calcaño
---

## ¿Que es esto? 

Un intento de reproducir la  estructura (layout) de una plataforma de contenido multimedia 
de tipo *streaming*. 

---

## ¿Como?
Utilizando unicamente  HTML5 y CSS3.

---
## Contenido
**HTML**

    1. Página de Inicio o login (index.html)
    2. Página principal (main.html) que incluye un carrusel de contenido destacado 
    3. Página con información detallada de un item (feature.html)

**CSS**

    1. Estilos generales (reset.css y styles.css)
    2. Estilos de la barra de navegación (navbar.css)
    3. Estilos del pie de página (footer.css)
    4. Estilos específicos de cada página (index.css, main.css y feature.css)
    5. Estilos del carrusel (carrusel.css) 

**Otros**

-Carpetas de imágenes (img), de tipografía (fonts) y de desechos. 

## Posicionamiento ##

### Barra de navegación ###
Móvil: Flexbox y posicionamiento fijo.

Pantalla grande: posicionamiento fijo.


### Index.html ###
Móvil
1. Flexbox vertical para el formulario

Pantalla grande
1. Flexbox externo horizontal de dos elementos (header y formulario)
2. Flexbox interno vertical para el formulario


### Main.html ###

Móvil

CSS Grid: rejilla de miniaturas

Pantalla grande: 

CSS Grid: rejilla de miniaturas

### Carrusel (incluido en main.html) ###
Móvil
1. Flexbox horizontal para el carrusel
2. Flexbox vertical para los botones del carrusel

Pantalla grande 
1. Flexbox horizontal para el carrusel
2. Flexbox horizontal para los botones del carrusel

### Feature.html ###

Móvil
1. Flexbox externo vertical con todas las secciones menos el footer.
2. Flexbox interno vertical para la sección 'feature-main' que contiene 2 elementos ('feature-trailer' y 'feature-info) 
3. Flexbox interno horizontal para la sección de contenido relacionado ('feature-related') que contiene 3 items (películas relacionadas)

Pantalla grande
1. CSS Grid externo con cuatro áreas: navbar, header, main y related-content
2. CSS Grid interno para la sección principal ('feature-main') que contiene dos elementos (feature-trailer y feature-info)
3. Flexbox interno horizontal para la sección de contenido relacionado ('feature-related) que contiene 3 items (películas relacionadas)


### Footer ###
Móvil y pantalla grande:

Flexbox horizontal

---

Nota: Todos los ficheros CSS que tienen código *responsive* comienzan por la versión móvil y acaban con una media-query para la versión en pantalla
grande **a excepción de 'carrusel.css', donde ocurre justo lo contrario**. 
