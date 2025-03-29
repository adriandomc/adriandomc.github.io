---
title: 'Heramienta para visualizar rutinas de transporte de personal'
description: 'Desarrollo de una herramienta de visualización dentro una plataforma web, para un cliente de la industria del transporte turístico y de personal'
image:
    url: '/project5a.jpg'
    alt: 'Herramienta de visualización tipo timeline'
worksImage1:
    url: '/project5a.jpg'
    alt: 'first image of your project.'
worksImage2:
    url: '/project5a.jpg'
    alt: 'first image of your project.'

platform: Javascript
stack: Javascript, PHP, CSS, RESTful API
website: https://waak.dev
github: https://waak.dev
---

Como parte del desarrollo de un sistema para la asignación y monitoreo de rutas de transporte de personal, el cliente requería de una herramienta que mostrara el avance del autobús a lo largo de la ruta asignada. Por medio de una "línea del tiempo", se representa una ruta como un conjunto de paraderos (utilizando puntos) y un ícono de autobús para mostrar el paradero actual de la unidad.

La herramienta está desarrollada principalmente con CSS y Javascript vanilla, para dotar de dinamismo a los elementos que la componen, ya que al poner el mouse sobre cada punto o sobre el ícono de autobús, muestra información acerca del paradero, hora estimada de llegada, nombre del operador y la unidad que está realizando la rutina. La información del avance de la unidad se obtiene por medio de una API, cuya autorización y token es enviado desde el servidor usando PHP. Por medio de la Fetch API de Javascript, se obtiene la información de forma asíncrona, actualizando silenciosamente la posición del ícono del autobús y marcando los paraderos que han sido visitados.