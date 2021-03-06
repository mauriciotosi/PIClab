+++
author = "Mauricio Tosi"
categories = ["gds"]
date = "2019-08-26T03:00:00+00:00"
mathjax = true
slug = "PICcal2mmv2"
tags = ["diseño", "gds", "2mm", "calibracion"]
title = "Layout de calibración para WH de 2mm - V2"
[output."blogdown::html_page"]
toc = false

+++
# Layout completo

El diseño tiene $1\\times1,$mm$^2$. Está formado por líneas para medición y para analizar la resolución tanto en campo claro como campo oscuro.
![](/images/pic_cal_2mmv2.png)
<img src="/PIClab/images/pic_cal_2mmv2.png" width="700"/>

# Lineas de medición

Igual que en el [diseño anterior](/PIClab/diseños/piccal2mmv1).

# Lineas de resolución

Igual que en el [diseño anterior](/PIClab/diseños/piccal2mmv1/).

# Cuadrados y círculos

Igual que en el [diseño anterior](/PIClab/diseños/piccal2mmv1/).

# Pruebas con acopladores direccionales

Acopladores direccionales con separación de 600nm, 800nm y 1µm. Horizontal y vertical, ambos en campo claro. A diferencia del diseño anterior, no incluímos en campo oscuro.

Las verticales tienen separacion de 600nm, 800nm, 1µm, 800nm y 600nm:

![](/images/pic_cal_2mmv2_DC1.png)
<img src="/PIClab/images/pic_cal_2mmv2_DC1.png" width="700"/>

Las horizontales tienen sep. de 600nm, 800nm y 1µm.

![](/images/pic_cal_2mmv2_DC2.png)
<img src="/PIClab/images/pic_cal_2mmv2_DC2.png" width="700"/>