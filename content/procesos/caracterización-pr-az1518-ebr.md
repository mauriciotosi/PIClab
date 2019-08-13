+++
author = "MT"
categories = ["fotoresina"]
date = "2018-08-01T03:00:00+00:00"
mathjax = true
slug = "caracterizacion_az1518"
tags = ["PR", "ebr", "az1518"]
title = "Caracterización PR az1518+EBR"
[output."blogdown::html_page"]
toc = false

+++
## Objetivo

El objetivo de esta nota es analizar el espesor de fotoresina [AZ1518](https://www.microchemicals.com/products/photoresists/az_1518.html) diluída en distintas concentraciones con [EBR](https://microchemicals.net/micro/az_ebr.pdf).

## Procedimiento

* En primer lugar clivamos una oblea de Si<100> (4") en muestras de aproximadamente 2x2cm².
* Utilizamos un frasco de vidrio limpio donde realizamos la mezcla AZ1518 con EBR en las distintas concentraciones.
* Medimos la cantidad de fotoresina y solvente con pipetas descartables.
* Depositamos la fotoresina sobre algunas muestras (una por una) con el _spin coating_ según la siguiente receta:

| Proceso | Caracteristica | Tiempo |
| :---: | :---: | :---: |
| Deposito (spin coat) | 4000 RPM (receta 21) | 2:30 min |
| Post-cocido | 100°C | 45 seg |

* Luego utilizamos el alineador de máscaras para exponer la fotoresina durante 8 segundos con una máscara genérica (matriz de cuadrados del orden de 1mm²).
* Revelamos con AZ400K (1:4) durante 40 segundos.
* Finalmente medimos el espesor de la fotoresina con el alpha step.

### Concentraciones

Sin diluir a 4000 RPM la fotoresina AZ1518 tiene un espesor del orden de 1.8µm. Para caracterizar probamos las siguiente concentraciones AZ1518:EBR (listadas en el orden en el cuál realizamos cada prueba):

1. **4:1**
2. **2:1**
3. **1:1**
4. **4:3**

## Resultados

Las pruebas con la concentración 2:1 la repetimos dos veces debido a que la primera vez dejamos reposar la solución durante más de una semana y es posible que el solvente se haya evaporado cambiando la concentración de la mezcla y por lo tanto los resultados no eran confiables.

Los resultados obtenidos se muestran en la siguiente tabla

| Concentración | Concentración EBR \[%\] | Espesor \[nm\] |
| --- | --- | --- |
| sin EBR | 0 | 1800 |
| 4:1 | 20 | 1207 |
| 2:1 | 33.33 | 905 |
| 1:1 | 50 | 308 |
| 4:3 | 42.8 | 550 |

Luego con los valores obtenidos realizamos un ajuste lineal para obtener una relación entre la concentración de EBR y el espesor de fotoresina obtenido:

![](/images/espesor_vs_concentracionEBR.png)

<img src="/PIClab/images/espesor_vs_concentracionEBR.png" width="700"/>