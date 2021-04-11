# Práctica de imagen de Análisis de datos no estructurados

Detección y segmentación de tumores en MRI cerebral utilizando transfer learning en redes convolucionales.

Se han obtenido los datos de Kaggle: https://www.kaggle.com/mateuszbuda/lgg-mri-segmentation

Hay que descomprimir el zip en la raíz antes de ejecutar el notebook.

El modelo de detección se ha implementado utilizando transfer learning con ResNet50. Para el modelo de segmentación se han seguido los mismos pasos que en este notebook: https://www.kaggle.com/shanan93/brain-mri-segmentation-95-5-accuracy. Se incluye en el repositorio este último modelo en formato h5, de modo que solo hay que cargarlo, ya que el objetivo principal era implementar un modelo de detección.

Trabajo realizado con Guillermo Becquer: gbecquer.

Imagen con los resultados:

![Resultados de la detección y segmentación de tumores](https://github.com/angelromo97/practica_imagen/blob/main/resultados.PNG)
