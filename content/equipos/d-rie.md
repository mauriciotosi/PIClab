---
title: D-RIE
author: Mauricio Tosi
date: 2018-10-16
slug: rie
categories:
- DeepRIE
tags:
- Etching
- RIE
mathjax: true
output:
  blogdown::html_page:
    toc: true

---
# Apuntes de operación básico

1. La temperatura de trabajo se setea en 15°C.
2. Se carga la muestra. Si la muestra es más chica que una oblea, se utiliza una especie de grasa silicona para mejorar el contacto térmico y se apoya la muestra sobre una oblea de soporte.
3. Para hacer vacío en la pre-cámara primero se pone **STOP** y luego se evacua.
4. Se selecciona la receta.
5. Se verifican los valores de la receta.
6. **RUN NOW** para ejecutar la receta.
7. Para sacar la muestra cuando termina primero se aprieta **STOP** y luego se ventea la precámara.

# Recetas

## PICShallowEtch

Esta receta se utilizó para atacar silicio. Con el tiempo del Etch step se ajusta el espesor a atacar.

Cuatro etapas:

1. to 5e-6 Torr
2. Cool step

   a) Tiempo: 1 minuto.

   b) Helium Backing: 10 Torr

   c) Chiller Temp.: 15°C
3. Etch step

   a) Tiempo: VARIABLE

   b) APC/LPS: Pressure: 15 mTorr

   c) Gases:

   ​		- C4F8 60 sccm

   ​		- SF6 50 sccm

   d) HF: Foward: 35W

   e) ICP: Forward: 1200W
4. to 5e-6 Torr

# Historial de ataques

## _08/10/2018_

Realizamos un ataque por **RIE** a la Muestra 01 (oblea de silicio protegida por la AZ1518 (4:3) con fotolitografía con masterizador). La receta utilizada es **PICshallowEtch** y se atacó un total de 1:30 (un minuto y treinta segundos). El perfil se midió con el perfilómetro óptico y se obtuvo un escalón de aproximadamente 1.4 µm (buscábamos atacar un total de 500nm). La fotoresina se removió con el **ASHER**.

## _16/10/2018_

Realizamos tres ataques por **RIE** a las Muestras 02: C2, C3 y C4. La receta utilizada es **PICshallowEtch** y se atacó cada cuadrante un total de 25, 35 y 45 segundos respectivamente. El perfil se midió con el perfilómetro de contacto y se obtuvieron los resultados de la siguiente tabla:

| Muestra | Tiempo de ataque | Escalón de Si |
| :---: | :---: | :---: |
| C2 | 25 seg | 500 nm |
| C3 | 35 seg | 400 nm |
| C4 | 45 seg | 200 nm |

​