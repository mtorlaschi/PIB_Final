# PIB_Final
Final deliverable for Biomedical Image Processing course regarding White Blood Cells Classification.

/////
La clasificacion de globulos blancos es de gran importancia para patologos. El
recuento diferencial de estas celulas es un trabajo tedioso por tres principales razones:
la amplia variacion en la forma de los globulos blancos, el solapamiento de celulas, la
presencia de artefactos y por la complejidad del fondo de las imagenes sanguıneas.
Por lo tanto, es sensible a errores, pero es de gran utilidad para el diagnostico de
diversas enfermedades. Al generar un metodo automatico, se pueden
eliminar ciertos errores que provienen de la naturaleza humana y, ademas, acelerar el
tiempo de analisis.
El objetivo del siguiente trabajo es generar la segmentacion y clasificacion de
un conjunto de imagenes histologicas dado. Para la segmentacion, se realizo un ajuste
de color de las imagenes y se procedio a obtener las mascaras totales y las mascaras
de nucleos aplicando tecnicas como la resta de capas de las imagenes, operaciones
morfologicas y el umbralizado. Las mascaras de citoplasma se obtuvieron realizando la
resta de las mascaras con nucleos a las mascaras totales. En cuanto a la clasificacion
se analizaron distintas metricas para poder identificar los
distintos tipos de celulas.
