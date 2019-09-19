+++
author = "MT"
categories = ["DWL"]
date = "2019-08-08T03:00:00+00:00"
draft = true
mathjax = true
slug = "2mmSiN01"
tags = ["2mm", "Fotolitografía", "SiN", "DWL"]
title = "DWL WH2mm sobre SiN: P1"
[output."blogdown::html_page"]
toc = false

+++
Utilizamos una oblea del batch de obleas nitruradas [Oblea](/PIClab/obleas/nitruro-de-silicio-sobre-sio2-01). Proceso:

### Limpieza

Previamente se había utilizado la oblea en otras pruebas con el cabezal de 10mm, para remover la fotoresina limpiamos con acetona, isopropanol y agua.

### Fotoresina

Se depositó [Ti Prime](/PIClab/recetas/ti-prime) para mejorar la adherencia de la fotoresina.

Se depositó [AZ1518](/PIClab/recetas/az1518)(4:3). Realizamos la preparación de la solución AZ1518+EBR en el momento con pipetas pasteur: 4ml de az1518 y 3ml de ebr (los 7ml alcanzaron para 2 obleas).

### Litografía

Utilizamos el masterizador con el cabezal de 2mm. Con la configuración del [mapa de exposición](/PIClab/recetas/dwl-mapa-exp) para obleas de 4".

El foco sobre la oblea es de z = -5580.

El trabajo realizado es el siguiente:

![](/images/MExp_08Agosto2019.png)

<img src="/PIClab/images/MExp_08Agosto2019.png" width="700"/>

Utilizamos el [archivo GDSII](/PIClab/diseños/PICcal2mm) de calibración para el cabezal de 2mm con distintas correcciones de spot (N500: -500nm y P500: +500nm).

El tiempo total de exposición de toda la oblea fue de **4:26 hrs** (3 minutos por mm$^2$)

### Revelado

Para revelar utilizamos **AZ351** en una solución 1:3 con agua DI.

Revelamos un total de 20 segundos.

## Resultados

![](/images/MExp_08Agosto2019_res.png)

<img src="/PIClab/images/MExp_08Agosto2019_res.png" width="700"/>