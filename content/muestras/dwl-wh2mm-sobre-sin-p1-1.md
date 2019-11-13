+++
author = "MT"
categories = ["DWL"]
date = 2019-09-19T18:00:00Z
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

### Corte

Utilizando el wafer dicing cortamos la oblea en cuadrados de 1x1cm². Cada muestra estaba formada por cuatro de los cuadrados de 0.5x0.5cm².

* **P3_M1**: Correccion de spot de -500nm, Defoc: 1700 y 1800, y energía: 70 y 80
* **P3_M2**: Correccion de spot de -400nm, Defoc: 1700 y 1800, y energía: 70 y 80
* **P3_M3**: Correccion de spot de -500nm, Defoc: 1700 y 1800, y energía: 70 y 80
* **P3_M4**: Correccion de spot de -400nm, Defoc: 1700 y 1800, y energía: 70 y 80

## Resultados

### Litografía

Utilizando el microscopio de la sala de ataque observamos las muestras una vez cortadas.

En las imagenes pudismo observar en el eje x la presencia de escalones periodicos, como se observa en algunas de las imagenes.

![](/images/escalon.png)
<img src="/PIClab/images/escalon.png" width="700"/>

#### P3_M1 (spot -500nm)

* D: 1700 y E: 70
  ![](/images/F1.jpg)
  <img src="/PIClab/images/F1.jpg" width="700"/>
* D: 1700 y E: 80
  ![](/images/F5.jpg)
  <img src="/PIClab/images/F5.jpg" width="700"/>
* D: 1800 y E: 70
  ![](/images/F2.jpg)
  <img src="/PIClab/images/F2.jpg" width="700"/>
* D: 1800 y E: 80
  ![](/images/F6.jpg)
  <img src="/PIClab/images/F6.jpg" width="700"/>

#### P3_M2 (spot -500nm)

* D: 1700 y E: 70
  ![](/images/F3.jpg)
  <img src="/PIClab/images/F3.jpg" width="700"/>
* D: 1700 y E: 80
  ![](/images/F7.jpg)
  <img src="/PIClab/images/F7.jpg" width="700"/>
* D: 1800 y E: 70
  ![](/images/F4.jpg)
  <img src="/PIClab/images/F4.jpg" width="700"/>
* D: 1800 y E: 80
  ![](/images/F8.jpg)
  <img src="/PIClab/images/F8.jpg" width="700"/>

### RIE

El ataque de RIE se realizó con el [RIE chico](/PIClab/equipos/rie_chico) con SF6 con la receta _SiN(PECVD)_SiO_PIC_ durante 45segundos.

Atacamos las muestras P3_M3 y P3_M4. La idea original era comparar con las muestras sin atacar el antes y despues de la fotoresina. Finalmente solo observamos en el FIB las muestras atacadas.

En el FIB nos concentramos en mirar la muestra P3_M4 porque en el microscopio vimos que con corrección de spot de -400nm el resultado fue mejor que con -500nm.

![](/images/SiN_DRIE_89.jpg)
<img src="/PIClab/images/SiN_DRIE_89.jpg" width="700"/>

#### Perfil de la guía de onda

![](/images/SiN_DRIE_34.jpg)
<img src="/PIClab/images/SiN_DRIE_34.jpg" width="700"/>
![](/images/SiN_DRIE_25.jpg)
<img src="/PIClab/images/SiN_DRIE_25.jpg" width="700"/>

De las mediciones de los anchos arriba y abajo de la guía concluimos que el ángulo de la pared es de 10+-2 grados.

#### Efecto de ondulación

Observamos un efecto de modulación sobre las líneas tanto verticales como horizontales. Medimos el ancho de la línea en distintos puntos y concluímos que la desviación estándar del ancho es de 50nm

![](/images/SiN_DRIE_94.jpg)
<img src="/PIClab/images/SiN_DRIE_94.jpg" width="700"/>

#### Escalon en el eje x

En las siguientes imagenes se muestra el efecto del escalón en el eje x que mencionamos antes. Este error parece ser un problema del masterizador al cargar la configuración para el cabezal de 2mm.

![](/images/SiN_DRIE_57.jpg)
<img src="/PIClab/images/SiN_DRIE_57.jpg" width="700"/>

![](/images/SiN_DRIE_004.jpg)
<img src="/PIClab/images/SiN_DRIE_004.jpg" width="700"/>

### Mediciones

#### Espesores:

| Capa | Espesor promedio \[nm\] | 
|---|---| 
| SiO2 | 470+-60 | 
| SiN  | 410+-20 |
| PR   | 180+-10  |

#### Ancho guía

Midiendo en la parte de arriba de la guía, la diferencia entre el ancho medido y el ancho esperado es de

$180\\pm30\\text{nm}$

Midiendo abajo, la diferencia es de:

$50\\pm20\\text{nm}$