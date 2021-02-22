---
layout: post
title: "Entornos Virtuales en Python"       # Title of the post
description: Los entornos virtuales permiten aislar recursos.       # Description of the post, used for Facebook Opengraph & Twitter
headline: Markdown Syntax Test      # Will appear in bold letters on top of the post
modified: 2021-2-19                 # Date
category: class
tags: []
image: 
comments: true
mathjax:
---

Normalmente en Python cuando requerimos instalar algun paquete para nuestro proyecto lo hacemos con ***pip***. ***pip*** es un gestor de paquetes y su función es administrar las dependencias en Python. Muchas de las dependencias disponibles se encuentran en <a href="https://pypi.org/">PyPi</a>

Que pasa cuando tenemos cientos de proyectos los cuales necesitan hacer uso de versiones diferentes de estas dependencias?

Por ejemplo, al trabajar en proyectos basados en la web podemos tener uno que usa Django 1.0 y otro que usa Django 2.0, sobre una misma maquina sin ningun tipo de configuración no se podría tener estos paquetes funcionando al tiempo, es aquí donde los entornos virtuales hacen su trabajo.

Los entornos virtuales tienen el objetivo de aislar nuestros proyectos, de manera tal que cada proyecto puede usar paquetes de manera independiente (diferentes versiones de depentendias sin afectar otros proyectos). En otras palabras, los entornos virtuales son una herramienta que ayuda a mantener separadas las dependencias requeridas por nuestros proyectos, permitiendo así mantener diferentes versiones de un mismo paquete funcionado para diferentes proyectos.

Veamos algunas de las opciones que podemos tener para usar entornos virtuales:

