# Taller de análisis de imágenes por software

## Propósito

Introducir el análisis de imágenes/video al implementar las siguientes operaciones de análisis para imágenes/video tanto por software como por hardware (empleando [shaders](https://github.com/VisualComputing/FragmentShaders)):

## Tareas

Implementar las siguientes operaciones de análisis para imágenes/video:

* Conversión a escala de grises: promedio _rgb_ y [luma](https://en.wikipedia.org/wiki/HSL_and_HSV#Disadvantages).
* Aplicación de algunas [máscaras de convolución](https://en.wikipedia.org/wiki/Kernel_(image_processing)).
* (solo para imágenes) Despliegue del [histograma](https://en.wikipedia.org/wiki/Image_histogram) y [segmentación](https://en.wikipedia.org/wiki/Image_segmentation) a partir del mismo.
* (solo para video) Medición de la [eficiencia computacional](https://processing.org/reference/frameRate.html) para las operaciones realizadas.

Emplear dos [canvas](https://processing.org/reference/PGraphics.html), uno para desplegar la imagen/video original y el otro para el resultado del análisis.

#### Alternativas para video en Linux y `gstreamer >=1`

Distribuciones recientes de Linux que emplean `gstreamer >=1`, requieren de [esta](https://github.com/gohai/processing-video/releases/tag/v1.0.2) versión alternativa de la librería de video. Descomprimir el archivo `*.zip` en la caperta de `libraries` del sketchbook (e.g., `$HOME/sketchbook/libraries`).

## Discusión

(describa brevemente las actividades realizadas y los resultados obtenidos)

## Entrega

* Por definir...
