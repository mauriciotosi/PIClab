+++
author = "MT"
categories = ["DWL"]
date = "2019-08-08T03:00:00+00:00"
draft = true
mathjax = true
slug = "2mmSiN01"
tags = ["2mm", "Fotolitografía", "SiN", "DWL"]
title = "DWL w/2mm sobre SiN 01"
[output."blogdown::html_page"]
toc = false

+++
Utilizamos una oblea del batch de obleas nitruradas [Oblea](/PIClab/obleas/sin_wo_annealing). Proceso:

### Limpieza

Previamente se había utilizado la oblea en otras pruebas con el cabezal de 10mm, para remover la fotoresina limpiamos con acetona, isopropanol y agua. 

### Fotoresina

Se depositó [Ti Prime](/PIClab/recetas/ti-prime) para mejorar la adherencia de la fotoresina.

Se depositó [AZ1518](/PIClab/recetas/az1518)(4:3). Realizamos la preparación de la solución AZ1518+EBR en el momento con pipetas pasteur: 4ml de az1518 y 3ml de ebr (los 7ml alcanzaron para 2 obleas). 

### Litografía

Utilizamos el masterizador con el cabezal de 2mm. Con la configuración del [mapa de exposición](/PIClab/recetas/dwl-mapa-exp) para obleas de 4".

El foco sobre la oblea es de -5436.

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