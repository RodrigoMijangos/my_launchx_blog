---
title: "Siempre hay nuevos trucos que dominar"
date: 2022-04-30
description: 'Validando los despliegues de cada cambio'
---

# Nuevas experiencias a las viejas barreras.

En pocos lugares he visto el requerimiento de validar los cambios mediante un despliegue automatizado. La experiencia más cercana que tuve fue usar __Heroku__ para desplegar una landing page con __React__. 

Recuerdo que el servicio de Heroku estaba vinculado al repositorio de Github que contenía la landing page. Cada que se hacía un cambio dentro de la rama master, los cambios eran construidos dentro de Heroku y muchas veces el cambio dejaba algún error dentro de la página. 
Mediante esa experiencia aprendí a hacer commits en ramas aparte de la rama principal (__main__ o __mster__) y siempre tener un servicio local funcionando para validar mis cambios, si las cosas se miraban bien era en ese momento donde combinaba los cambios de la rama en la que estaba trabajando con la rama principal.

Con algún tiempo aprendí que al momento de probar los elementos de nuestro software como los formularios, botones o la información que es mostrada en los elementos de nuestro software se llaman pruebas unitarias manuales.

## Pruebas unitarias automatizadas.

Ya sabía que las pruebas podían automatizarse, pero lo que no sabía era que Github tenía las herramientas que nos permiten validar los cambios que hacemos a los repositorios.
EL nuevo truco que aprendí en esta mision es la sección de páginas de Github. Se me ocurren 2 o 3 proyectos en los que esa herramienta puede ser muy útil, pero tambien veo algunas limitaciones como en la arquitectura cliente-servidor.

Me emociona mucho poder seguir aprendiendo más herramientas útiles. 
