# Segmentacion-de-Manzanas

Segmentación de imágenes mediante umbralizacion 

Este notebook es parte de preposamiento de imagenes para obtener la imagen recortada de una manzana para ser ocupado en un clasificador de manzanas 

La entrada de proceso es una imagen en un medio ideas de tamaño 800x600.

Para la segemtacion se realizaron los siguientes pasos:

1.- Leer la imagen y quedarse con el Canal Azul.

2.- Se difumino la imagen mediante un filtro Gaussiano.

3.- Se binarizo la imagen mediante el metodo Otsu.

4.- Aplicacion de dos operaciones morfologicas: OPEN y CLOSE.

5.- Busqueda de control.

6.- Recorte de la imagen solo de la manzana.
