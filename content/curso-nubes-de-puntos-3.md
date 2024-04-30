+++
title = 'Curso 3: Obtención de MDT desde Nubes de Puntos 1'
date = 2024-04-25T22:15:15-06:00
draft = false
+++
## Curso Nube de Puntos 3 Obtención de MDT 1

**Tiempo:** 8 horas.

**Objetivo :**
* Aprenderás a obtener el Modelo Digital de Terreno partir de un Modelo Digital de Superficie, teniendo como insumo principal una Nube de Puntos Fotogramértica en formato LAS.

**Nivel:** Intermedio

**Qué aprenderás en este curso:**

Al terminar este curso sabrás:
* Cómo obtener un DMT desde una nube de puntos a partir de un flujo de trabajo.
* Analizarás como elegir los parámetros de un filtro de terreno.
* Importarás los resultados a AutoCAD, triagularás y obtendrás curvas de nivel.

## Temas

### Parte I: DTM con LAStools

### Instalación y revisión de licencias de LAStools.

### Revisión de la Metodologías para obtener MDT con Lastools (ver video: https://www.youtube.com/watch?v=mUrlMhBbrIE)

### Trabajos preliminares
* Preparar el directorio de trabajo
* Visualizar la nube de puntos
* Obtener información de la nube de puntos
* Ajustar nivel de detalle, punto de partida, eliminar clasificaciones
* Calcular densidad

### Obtención del DTM
* Partir la nube de puntos en teselas y/o en zonas
* Reordenar puntos
* Filtrar ruido
* Tomar una muestra de punto cercanos al suelo
* Aplicar filtro para obtener el suelo desnudo
* Obtención de suelo grueso
* Obtención de suelo medio
* Juntar teselas en un solo archivo
* Tomar una muestra equiespaciada de suelo medio
* Exportar de LAS a CSV o TXT

### Dibujar Curvas de Nivel en AutoCAD
* Crear archivo de Autocad
* Asignar proyección cartográfica (MAPCSLIBRARY)
* Cargar archivo CSV o TXT con CivilCAD
* Triangular y obtener curvas.

### Usando QGIS como interface gráfica de LAStools
* Configuración del plugin de LAStools en QGIS
* Ejecutar filtros usando el plugin

### Conclusiones y sesión de preguntas y respuestas
