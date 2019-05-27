---
title: Horno de oxidación
author: Mauricio Tosi
date: '2018-11-16'
slug: horno-de-oxidacion
categories:
  - Oxidación
tags:
  - Horno
  - SiO2
  - Óxido
  - Solar
mathjax: true
output:
  blogdown::html_page:
    toc: true
---

# Historial de oxidaciones

## *26/10/2018* 
Realizamos el proceso de oxidación en el horno de solar de 25 obleas DSP (*double side polished*) de silicio <100>. Utilizamos la siguiente receta diseñada para conseguir 400nm de SiO2:

| Etapa | Temp [°C]        | Tiempo [m]   | N<sub>2</sub> [l/min]  | O<sub>2</sub> [l/min]  |     Obs              |
|:-----:|:----------------:|:------------:|:-------------:|:-------------:|:--------------------:|
|   1   |        700       |      50      |      1        |      0        |                      |
|   2   |        700       |      10      |      1        |      0        |                      |
|   3   |       1190       |      40      |      2        |      2        | entran las 25 obleas |
|   4   |       1190       |      240     |      0        |      4        |       oxidación      |
|   5   |        700       |      60      |      1        |      0        |     enfriamiento     |

Luego medimos en el elipsómetro utilizando el modelo prediseñado **SiO2 (200-1000A) on Si**. Medimos tres obleas y obtuvimos los resultados de la siguiente tabla:

| Oblea | Pts    | $\overline{L}$ [nm] | $L_{max}$ [nm] | $L_{min}$ [nm] | $\sigma$ [nm] |
|:-----:|:------:|:-------------------:|:--------------:|:--------------:|:-------------:|
|   1   |    9   |       406           |      410       |      403       |      2        |
|   2   |    5   |       412           |      416       |      409       |      3        |
|   3   |    5   |       406           |      409       |      404       |      2        |

<img src="/images/equipos/horno-de-oxidacion/obleas.jpg" alt="horno" width="300"/>

___

## *16/11/2018*

Realizamos el proceso de oxidación en el horno de solar de 25 obleas SSP (*single side polished*) de silicio <100>. Utilizamos la siguiente receta diseñada para conseguir un espesor mayor a 400nm de SiO2:

| Etapa | Temp [°C]        | Tiempo [m]   | N<sub>2</sub> [l/min] | O<sub>2</sub>  [l/min] |     Obs              |
|:-----:|:----------------:|:------------:|:-------------:|:-------------:|:--------------------:|
|   1   |        700       |      50      |      1        |      0        |                      |
|   2   |        700       |      10      |      1        |      0        |                      |
|   3   |       1190       |      40      |      1        |      1        | entran las 25 obleas |
|   4   |       1195       |      300     |      0        |      1        |       oxidación      |
|   5   |        700       |      60      |      1        |      0        |     enfriamiento     |

Los valores bajos de ambos gases se debe a que ese día disponían de poco óxigeno en los laboratorios de Solar. Para no quedarnos sin O2 durante el proceso de oxidación utilizamos un caudal más chico. Esto se notó en el resultado final ya que observamos una gran diferencia de los colores de óxidos obtenidos. El efecto es una especie de degrade.

Separamos las obleas entre los dos porta-obleas (*carry*) del horno **c1** y **c2**. Al ingresar al horno, **c1**, quedó posicionado más cerca de la entrada de gas. Por este motivo observamos mayores espesores y uniformidades en las obleas oxidadas pertenecientes al primer carry (color rosado).

Los espesores los medimos en el elipsómetro utilizando el modelo prediseñado **SiO2 (200-1000A) on Si**. Debido al degrade de colores, medimos en 6 obleas diferentes, tres de cada porta-oblea. Los resultados obtenidos se muestra en la siguiente tabla:

| Oblea |  Carry | Pts  | $\overline{L}$ [nm] | $L_{max}$ [nm] | $L_{min}$ [nm] | $\sigma$ [nm] |
|:-----:|:------:|:----:|:-------------------:|:--------------:|:--------------:|:-------------:|
|   1   |   c1   |  9   |       447           |      455       |      441       |      4        |
|   2   |   c1   |  9   |       450           |      462       |      443       |      6        |
|   3   |   c1   |  9   |       443           |      452       |      437       |      5        |
|   4   |   c2   |  9   |       435           |      446       |      430       |      4        |
|   5   |   c2   |  9   |       404           |      407       |      398       |      6        |
|   6   |   c2   |  9   |       368           |      380       |      355       |      5        |

