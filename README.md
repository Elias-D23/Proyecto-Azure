# Proyecto-Azure

Descripción de la Aplicación: Análisis de Imágenes con Custom Vision

¿Cómo funciona esta aplicación?

Esta aplicación web permite a los usuarios subir una imagen y analizar su contenido utilizando Microsoft Azure Custom Vision, un servicio de inteligencia artificial especializado en el reconocimiento de objetos dentro de imágenes.

El proceso se divide en tres pasos:

Subir una imagen: El usuario selecciona una imagen desde su dispositivo. Se mostrará una vista previa de la imagen antes del análisis.

Procesamiento con Custom Vision: Al hacer clic en "Analizar Imagen", la imagen se envía al servicio de Custom Vision de Azure, donde se procesa utilizando un modelo previamente entrenado.

Visualización de resultados: La aplicación redirige al usuario a la página de resultados, donde se muestran los dos valores más relevantes del análisis:

El objeto con la mayor probabilidad de coincidencia.

El objeto con la menor probabilidad de coincidencia.
Además, se presenta un gráfico visual para una mejor comprensión de los datos.

