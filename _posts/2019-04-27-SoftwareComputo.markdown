---
layout: post
title:  "Software de cómputo numérico"
image: ''
date:   2019-03-27 11:00:00
comments: true
categories: software
---

## Introducción

Los paquetes de software de cómputo númerico se componen de varias partes. En
general tiene un núcleo que lo compone un intérprete para un lenguaje de
programación de alto nivel. Un unidad que hace de IO (input/output) para
operaciones varias, además de una consola de texto para que el usuario tenga
acceso a las posibilidades que da la herramienta. Tienen algún módulo para hacer
el nexo con alguna herramienta para graficar, siempre con el objetivo de
resolución numérica.

 Octave helps in solving linear and nonlinear problems numerically, and for
 performing other numerical experiments using a language that is mostly
 compatible with MATLAB. It may also be used as a batch-oriented language.
 Since it is part of the GNU Project, it is free software under the terms of the
 GNU General Public License. 

## Lista

La [siguiente](https://en.wikipedia.org/wiki/List_of_numerical-analysis_software)
es una lista de software multiplataforma que sirven para el cómputo numérico en
wikipedia.
Además de esto, me gustaría destacar las siguientes herramientas, por varias
razones, las más importantes serían su licencia que los convierten en
[FOSS](https://en.wikipedia.org/wiki/Free_and_open-source_software), lo que los
alinean perfectamente con el uso universitario y el entorno académico, además
personalemente los utilizo o he utilizado con muy buenos resultados.

### GNU Octave

El software [GNU Octave](https://www.gnu.org/software/octave/), es una
herramienta con gran presencia dentro del ambiente de cómputo númerico. La
primera versión fue liberada en el año 1988, con una gran historia y desarrollo.
Actualmente es [software libre](https://es.wikipedia.org/wiki/Software_libre).

Algunas de las ventajas es que es compatible con otros paquetes de software
comerciales, es relativamente liviano para las posibilidades que brinda. Está
portado a varios sistemas operativos. Una herramienta que permite usar módulos
que incrementan la posibilidades de resolución. Tiene drivers para manejar
diferentes salidas de los datos al graficarlos.

### Scilab

El software [Scilab](http://www.scilab.org/), es [libre y open-source](https://en.wikipedia.org/wiki/Free_and_open-source_software)
es también un paquete multiplataforma de alto nivel con un lenguaje de
programación orientado a cómputo numérico. Por defecto viene con un front-end
visual intentando proveer más sencillez de uso. Fue creado en el año 1990, a lo
largo de los años se han ido haciendo cargo de su desarrollo diferentes
consorcios.

### Torch

El software [Torch](http://torch.ch/) es un conjunto de herramientas que tiene
como lenguaje de scripting el impresionante lenguaje [Lua](https://www.lua.org/).
Destaca por su optimización puesto que utiliza [LuaJIT](https://luajit.org/),
que hace una implementación [JIT](https://en.wikipedia.org/wiki/Just-in-time_compilation)
de la [VM](https://en.wikipedia.org/wiki/Virtual_machine) de [Lua](https://www.lua.org/).

### Julia

El lenguaje [Julia](https://julialang.org/), es un lenguaje de alto nivel de
propósito general para análisis numérico de alta eficiencia y computación
científica, además de algunas características muy interesante. Este lenguaje ha
ido ganando mucha popularidad en los últimos años por sus constantes mejoras y
características avanzadas. Se comenzó con el desarrollo en el año 2009,
actualmente se usa en proyectos de análisis de gran evergadura.

## Conclusión

Las anterios recomendaciones no son lás únicas y por supuesto que mi itención no
es cercenar la curiosidad en el uso de quienes requieran este tipo de
herramientas. En principio las recomendaciones son en base a muchos parámetros
que no expondré aquí, principalmente pienso que [GNU Octave](https://www.gnu.org/software/octave/)
es una gran herramienta para la materia que nos concentra. Podría proponerla
como un buen punto de partida por su versatilidad y relativa sencillez, una
buena cantidad de módulos y con un lenguaje bien orientado a la computación
numérica.
Pero, como he comentado, hay muchas herramientas más, cada una con mayor o menor
posibilidades, más eficientes o bien más versatiles, sólo resta decir que
ojalá prueban varias y den con la que les parezca más cómoda y se adapte a sus
necesidades.
