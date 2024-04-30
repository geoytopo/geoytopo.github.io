+++
title = 'Curso 4: Obtención de MDT desde Nubes de Puntos 2'
date = 2024-04-27T16:32:37-06:00
draft = false
+++
# Curso Nube de Puntos 3 Obtención de MDT 2

**Tiempo:** 8 horas.

**Objetivo:** 
* Conocerás otra metodología para obtener el Modelo Digital de Terreno y harás algunos cambios en los sistemas de coordenadas, a partir de una Nube de Puntos LIDAR en formato LAS.

**Nivel:** Intermedio

**Qué aprenderás en este curso:**

Al terminar este curso sabrás:
* Cómo obtener un DMT desde una nube de puntos usando el algorito llamado Filtro Morfológico Simple, provisto en el software pdal.
* Analizarás como elegir los parámetros del filtro de terreno.
* Cambiarás la proyección cartográfica y el datum vertical de la nubes de puntso.

## Temas:

### Parte II: DTM con pdal

### 1. Instalación y revisión de licencias de pdal, proj y gdal.
* Instalación de Anaconda
* Crear un enviroment
* Instalar pdal

### 2. Algunos ejercicios con pdal
* Revisar metadados
* Obtener Densidad
* Obtener Perímetros del mapeo con LIDAR (boundary)
* Hacer un recorte (clip)

### 3. El algoritmo SFM para obtención de DTM con pdal
* Operaciones Morfológicas Elementales
* Revisión del algoritmo SMF (Filtro Morfológico Simple)
* Elegir parámetros del SMF: el provisto en el paper y los sugeridos en foros.
* Armar el archivo JSON con los filtros y los parámetros adecuados.
* Aplicación del filtro
* Exportar a CSV
* Visualizar con CloudCompare

### 4. Transformación de coordenadas
* Ejercicios de transforamación de coordenadas con PROJ
* Cambio de Datum Vertical
* Cambio de Proyección Cartográfica
* Armar el archivo JSON con los filtros y los parámetros adecuados.
* Filtrado
* Revisar resultados desde metadatos y con CloudCompare

### 5. Conclusiones y sesión de preguntas y respuestas
