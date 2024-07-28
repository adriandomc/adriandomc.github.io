---
title: 'Controlador MIDI basado en Arduino'
description: 'Diseño de un controlador MIDI para controlar software musical utilizando una tarjeta Arduino MEGA 2560.'
image:
    url: '/project1a.jpg'
    alt: 'Proyecto Arduino MIDI'
worksImage1:
    url: '/project1a.jpg'
    alt: 'first image of your project.'
worksImage2:
    url: '/project1a.jpg'
    alt: 'first image of your project.'

platform: Arduino
stack: C++, Arduino
website: None
github: https://github.com/cosmicdinodog/arduino2560-midi-controller
---

El objetivo principal de armar este controlador es crear un dispositivo de fácil construcción y asequibilidad, con funcionalidad simple, personalizable y escalable. La elección de usar una tarjeta de desarrollo Arduino atiende al propósito de que pueda ser modificado su código fuente, además de que permite que la interfaz sea casi inmediata.
El controlador en su versión 1.0 cuenta con las siguientes características:

- 4 potenciómetros lineales para Control Change (CC)
- 4 botones para CC
- 2 displays de 7 segmentos para lectura de valor actual
- Montado en una protoboard y conectado por medio de cables jumper para fácil depuración y escalabilidad
