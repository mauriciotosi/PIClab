---
title: 'Muestra sobre Si: S2'
author: Mauricio Tosi
date: 2018-10-09
slug: muestra-sobre-si-s2
categories:
- Muestras
tags: []
mathjax: true

---
Sobre una oblea de Si <100> de 4" realizamos el siguiente proceso:

### Limpieza

Limpieza con acetona, isopropanol y agua.

### Fotoresina

Se depositó [Ti Prime](/PIClab/recetas/ti-prime) para mejorar la adherencia de la fotoresina.

Se depositó [AZ1518](/PIClab/recetas/az1518)(4:3). Previamente realizamos la preparación de la solución AZ1518+EBR y medimos el espesor en una pequeña muestra haciendo litografía con el alineador de máscaras. Obtuvimos un espesor de 580 nm medidos con el perfilómetro de contacto.

Como resultado no se observa una distribución homogénea de la fotoresina. En el centro vemos que se forma una especie de espiral debido al proceso de spin coating, esto puede ser producto de una aceleración de spineado muy grande.

### Litografía

Utilizamos el masterizador con el cabezal de 10mm. Con la configuración del [mapa de exposición](/PIClab/recetas/dwl-mapa-exp) para obleas de 4".

El foco sobre la oblea es de 5436.

El trabajo realizado es el siguiente:

<img src="/PIClab/images/muestras/muestra-sobre-si-s2/muestra2_mapa.png" width="700"/>

Utilizamos el archivo GDSII de calibración para el cabezal de 10mm tanto en campo oscuro como en campo claro.

El tiempo total de exposición de toda la oblea fue de **2:40 hrs**

La oblea la clivamos en cuatro partes como se muestra a continuación

<img src="/PIClab/images/muestras/muestra-sobre-si-s2/muestra2.png" width="400"/>

### Revelado

Para revelar utilizamos **AZ351** en una solución 1:3 con agua DI.

Revelamos los cuadrantes **C1** (campo oscuro) y **C3** (campo claro) un total de 20 segundos, mientras a los cuadrante **C2** (campo oscuro) y **C4** (campo claro) revelamos durante 15 segundo.

A continuación se muestran capturas de las estructuras en cada cuadrante.

<img src="/PIClab/images/muestras/muestra-sobre-si-s2/c1_field_n.png" width="300"/> <img src="/PIClab/images/muestras/muestra-sobre-si-s2/c2_field_n.png" width="300"/> <img src="/PIClab/images/muestras/muestra-sobre-si-s2/c3_field_n.png" width="300"/> <img src="/PIClab/images/muestras/muestra-sobre-si-s2/c4_field_n.png" width="300"/>

### RIE

El ataque por [RIE](/PIClab/equipos/rie) se realizó con la receta PICshallowEtched y se atacaron los cuadrantes C2, C3 y C4 un total de 25, 35 y 45 segundos respectivamente.

La fotoresina se removió con el [ASHER](/PIClab/equipos/asher) durante 1 minuto.

Los escalones obtenidos se presentan en la siguiente tabla

| Muestra | Tiempo de ataque | Escalón de Si |
| :--- | :--- | :--- |
| C2 | 25 segundos | 500 nm |
| C3 | 35 segundos | 400 nm |
| C4 | 45 segundos | 200 nm |

<img src="/PIClab/images/muestras/muestra-sobre-si-s2/figure-html/unnamed-chunk-1-1.png" alt="rie" width="700"/>