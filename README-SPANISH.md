# Fashion-autoencoder
Desarrollado en el curso de Redes Neuronales por: Diego Quezada y Kevin Reyes.
## Objetivos
- Obtener representaciones de baja dimensionalidad de imágenes de prendas de ropa utilizando Autoencoders.
- Identificar clases similares que podrían resultar conflictivas para el modelo.
- Evaluar el efecto de la profundidad del autoencoder en la reconstrucción de la imagen inicial.
- Comparar autoencoder con arquitectura de red neuronal fully connected y autoencoder convolucional.
- Utilizar autoencoder para eliminar ruido de los datos.
- Generar imágenes de prendas de ropa utilizando un autoencoder.

## Descripción
Análisis de casos de uso de Autoencoders en imágenes de prendas de ropa.

## Conclusiones
- La arquitectura de autoencoder convolucional tiene resultados muy superiores al autoencoder con red fully connected.
- Utilizando un autoencoder convolucional es posible representar la información de más alto nivel (bordes) en una menor dimensionalidad.
- El denoising autoencoder logra limpiar una imagen con ruido blanco, sin embargo, solo preserva información de bordes y algunos cambios de color en la imagen.
- Las imagenes generadas solo tienen algunas siluetas similares a prendas de ropa, sin embargo el resultado es deficiente.
## Stack de tecnologías
- Tensorflow.
- Keras.
- Numpy.
- Matplotlib.