+++
author = "Mauricio Tosi"
categories = []
date = "2019-10-08T03:00:00+00:00"
mathjax = true
slug = "rie_chico"
tags = ["Etching", "RIE"]
title = "RIE Chico"
[output."blogdown::html_page"]
toc = true

+++
# Apuntes de operación básico

## Revisar antes de empezar

1. Bomba de refrigeración (RIE-chico)
2. Gases encendidos

## Encendido

1. Botón verde del RIE.
2. Se prende el chiller y se setea en T=0°C y se activa manteniendo apretado el enter.
3. Se prende la computadora.
4. Luego de abrir el programa todas las verificaciones de abajo tienen que estar en verde menos la entrada de los gases a la camara.

## Limpieza

1. Primero hacer vacío en la cámara.
2. Utilizar la receta de limpieza de cámara (se puede cortar antes de que termine)

En general hay que mirar el valor de tensión DC(bias). Un valor tipico cuando la cámara está limpia es 300V. Si oscila mucho es señal de suciedad.

## Muestras

1. Sobre el wafer carry montar las muestras con un poco de grasa para mejorar la conducción térmica.
2. Colocar las muestras lo mas cercano al centro del WC.
3. Cerrar la cámara y hacer vacío.
4. Ejecutar la receta.

# Recetas

## SiN(PECVD)\_SiO\_PIC

Esta receta sirve para atacar el nitruro de silicio. Se creó a partir de la receta SiN(50nm).

Observamos que para PECVD la tasa de ataque es 4.5 nm/seg. Se configuró en 1:30 minutos para comer todo el nitruro de silicio.

# Historial de ataques

## _08/10/2019_

Realizamos un ataque por **RIE** a una muestra de 1x1cm2 de nitruro de silicio sobre SiO2. Antes de realizar el ataque medimos el espesor con el elipsómetro. La receta utilizada es **SiN(50nm)** y se atacó un total de 45 seg. Luego medimos el espesor resultante y obtuvimos los siguientes valores:

| | Espesor [nm] |
|---|---|
| Antes del RIE | 315.2 |
| Luego del RIE | 112.9 |

Por lo tanto concluímos que la tasa de ataque es 4.5nm/seg.

## _08/10/2018_

Realizamos ataque por **RIE** a las Muestras: P3_C3 y P3_C4. La receta utilizada es **SiN(PECVD)\_SiO\_PIC** con un total de 1:30 minutos de atauqe.