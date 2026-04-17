# Trabajo Práctico 3 – Visión por Computadora

## Descripción

En este trabajo práctico se implementa un detector de logos mediante Template Matching, aplicando técnicas de correlación normalizada y búsqueda multi-escala sobre un conjunto de imágenes de productos Coca-Cola.

El objetivo es:

* Detectar el logotipo de la gaseosa en cada imagen provista sin falsos positivos, usando un único template
* Plantear y validar un algoritmo de detecciones múltiples sobre la imagen `coca_multi.png`
* Generalizar el algoritmo de detección múltiple para todas las imágenes del dataset

## Contenido

### Notebook

El desarrollo completo, junto con los resultados, visualizaciones y conclusiones, se encuentra en el siguiente notebook:

* `TP3_VPC.ipynb`

### Estructura del notebook

1. **Setup**: carga del template y las imágenes desde Google Drive
2. **Funciones base**: implementación de funciones utilizadas
3. **Ítem 1 – Detección única**: detección del logo en cada imagen sin falsos positivos, usando búsqueda multi-escala con template normal e invertido
4. **Ítem 2 – Detecciones múltiples**: ajuste empírico de escala y umbral para detectar la mayoría de los logos en `coca_multi.png`, con NMS para eliminar detecciones duplicadas
5. **Ítem 3 – Generalización**: aplicación del algoritmo del punto 2 sobre todas las imágenes del dataset

## Ejecución

Colocar las imágenes en `Material_TPs/TP3/images/` y el template en `Material_TPs/TP3/template/` dentro de Google Drive, luego abrir el notebook en Google Colab y ejecutar las celdas en orden. De todas formas, se encuentra ejecutado el notebook completo.

## Autora

Lourdes Gonzalez Branchi
