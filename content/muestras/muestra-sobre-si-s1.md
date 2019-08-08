---
title: 'Muestra sobre Si: S1'
author: Mauricio Tosi
date: 2018-09-27
slug: muestra-sobre-si-s1
categories:
- Muestras
tags: []
mathjax: true

---
Sobre una oblea de Si <100> de 4" realizamos el siguiente proceso:

### Limpieza

Como la oblea había sido utilizada previamente en un intento fallido, se limpió con acetona, isopropanol y agua.

### Fotoresina

Se depositó [Ti Prime](/recetas/ti-prime) para mejorar la adherencia de la fotoresina.

Se depositó [AZ1518](/recetas/az1518)(4:3). No se analizó el espesor de la fotoresina, esto no es recomendable porque en otras ocasiones se observó que la solución de AZ1518+EBR se modifica con el tiempo, probablemente por evaporación del solvente. Estimamos un espesor entre 500 nm y 600 nm. Lo ideal es realizar la preparación de la solución AZ1518+EBR al momento de utilizarla para lograr el espesor deseado.

Como resultado no se observa una distribución homogénea de la fotoresina. En el centro vemos que se forma una especie de espiral debido al proceso de spin coating, esto puede ser producto de una aceleración de spineado muy grande.

### Litografía

Utilizamos el masterizador con el cabezal de 10mm. Con la configuración del [mapa de exposición](/recetas/dwl-mapa-exp) para obleas de 4".

El foco sobre la oblea es de 5480.

El trabajo realizado es el siguiente:

<img src="/PIClab/images/muestras/muestra-sobre-si-s1/muestra2_mapa.png" alt="mapaexp" width="700"/>

Utilizamos el archivo GDSII de calibración para el cabezal de 10mm tanto en campo oscuro como en campo claro.

El tiempo total de exposición de toda la oblea fue de **2:50:47** (45 segundos por campo aproximadamente).

### Revelado

Utilizamos AZ400 en una preparación 1:4 con agua DI.

El tiempo de revelado fue de 10 segundos.

Se enjuagó con agua suavemente para evitar el desprendimiento de la fotoresina.

<img src="/PIClab/images/muestras/muestra-sobre-si-s1/CAL_CO_E100_0012.jpg" alt="mapaexp" width="400"/>

### RIE

El ataque por [RIE](/equipos/rie) se realizó con la receta PICshallowEtched y se atacó un total de 1:30 (un minuto y treinta segundos).

Como resultado se obtuvo un escalón de 1.4 µm.