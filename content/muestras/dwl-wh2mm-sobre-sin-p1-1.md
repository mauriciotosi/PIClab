+++
author = "MT"
categories = ["DWL"]
date = "2019-09-19T18:00:00+00:00"
mathjax = true
slug = "2mmSiN03"
tags = ["2mm", "Fotolitografía", "SiN", "DWL"]
title = "DWL WH2mm sobre SiN: P3"
[output."blogdown::html_page"]
toc = false

+++
Utilizamos una oblea del batch de obleas nitruradas [Oblea](/PIClab/obleas/nitruro-de-silicio-sobre-sio2-01). Proceso:

### Limpieza

Previamente se había utilizado la oblea en otras pruebas con el cabezal de 2mm [(muestra)](/PIClab/muestras/2mmsin01), para remover la fotoresina limpiamos con acetona, isopropanol y agua.

### Fotoresina

Se depositó [Ti Prime](/PIClab/recetas/ti-prime) para mejorar la adherencia de la fotoresina.

Se depositó [AZ1518](/PIClab/recetas/az1518)(4:3). Realizamos la preparación de la solución AZ1518+EBR en el momento con pipetas pasteur: 4ml de az1518 y 3ml de ebr (los 7ml alcanzaron para 2 obleas).

### Litografía

Utilizamos el masterizador con el cabezal de 2mm. Con la configuración del [mapa de exposición](/PIClab/recetas/dwl-mapa-exp) para obleas de 4".

El foco sobre la oblea es de z = -5579.

El trabajo realizado es el siguiente:

![](/images/MExp_19Septiembre2019.png)

<img src="/PIClab/images/MExp_19Septiembre2019.png" width="700"/>

Utilizamos el [archivo GDSII](/PIClab/diseños/PICcal2mm_with_PIC) de calibración para el cabezal de 2mm con distintas correcciones de spot (N500: -500nm y N400: -400nm).

### Revelado

Para revelar utilizamos **AZ351** en una solución 1:3 con agua DI.
Revelamos un total de 25 segundos.

### Resultados

![](/images/F4_N400_DF1800_E70_01.jpg)![](/images/F8_N400_DF1800_E80_04.jpg)![](/images/F8_N400_DF1800_E80_09.jpg)![](/images/F8_N400_DF1800_E80_10.jpg)

<img src="/PIClab/images/F4_N400_DF1800_E70_01.jpg" width="700"/><img src="/PIClab/images/F8_N400_DF1800_E80_04.jpg" width="700"/><img src="/PIClab/images/F8_N400_DF1800_E80_09.jpg" width="700"/><img src="/PIClab/images/F8_N400_DF1800_E80_10.jpg" width="700"/>