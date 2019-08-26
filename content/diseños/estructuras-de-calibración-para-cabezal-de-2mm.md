+++
author = "Mauricio Tosi"
categories = ["gds"]
date = "2019-08-08T03:00:00+00:00"
mathjax = true
slug = "PICcal2mmv1"
tags = ["diseño", "gds", "2mm", "calibracion"]
title = "Layout de calibración para WH de 2mm - V1"
[output."blogdown::html_page"]
toc = false

+++
# Layout completo

El diseño tiene $1\\times1,$mm$^2$. Está formado por líneas para medición y para analizar la resolución tanto en campo claro como campo oscuro.
![](/images/pic_cal_2mm.png)
<img src="/PIClab/images/pic_cal_2mm.png" width="700"/>

# Lineas de medición

Consisten en dos bloques, el primero tiene lineas que van de 1µm a 10µm con un paso de 1µm. La separación entre los centros es de 20µm para facilitar la medición. El segundo bloque son lineas de 600nm a 1µm con un paso de 100nm (se repite 4 veces) también con separación de 20µm EC.

Ambos bloques están en campo oscuro y campo claro.

![](/images/pic_cal_2mm_lines1.png)
<img src="/PIClab/images/pic_cal_2mm_lines1.png" width="700"/>

# Lineas de resolución

Este bloque consiste en líneas de ancho variable (por fila) y separación variable (por columna).  Desde lineas de 600nm separadas 600nm hasta lineas de 1.2µm separadas 1.2µm.

![](/images/pic_cal_2mm_lines2.png)
<img src="/PIClab/images/pic_cal_2mm_lines2.png" width="700"/>

# Cuadrados y círculos

Matrices de cuadrados y círculos de lado y radio variable, respectivamente.

![](/images/pic_cal_2mm_b.png)
<img src="/PIClab/images/pic_cal_2mm_b.png" width="700"/>

# Pruebas con acopladores direccionales

Acopladores direccionales con separación de 600nm, 800nm y 1µm.

![](/images/pic_cal_2mm_c.png)
<img src="/PIClab/images/pic_cal_2mm_c.png" width="700"/>

# Lineas

asdddddddddddd