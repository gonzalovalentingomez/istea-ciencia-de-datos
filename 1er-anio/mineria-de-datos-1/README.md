# Minería de Datos I

**ISTEA — 1er año, 2do cuatrimestre 2026** · Prof. Kevin Kovacs

Notebooks de la materia Minería de Datos I: desde la limpieza y preparación de datos hasta modelos supervisados y no supervisados, procesamiento de texto y redes neuronales. Cada notebook empieza con un resumen (objetivo, datos, resultado principal) y termina con sus conclusiones.

| # | Notebook | Tema | Resultado principal |
|---|---|---|---|
| 01 | [Outliers con el criterio de Tukey](01_outliers_criterio_tukey.ipynb) | Detección y tratamiento de valores atípicos (IQR, boxplots) | Un outlier no siempre es un error: el 11% de las filas eliminadas eran gastos médicos altos pero reales |
| 02 | [Transformación de variables](02_transformacion_de_variables.ipynb) | LabelEncoder, OneHotEncoder y MinMaxScaler | Dataset 100% numérico y en la misma escala, listo para un modelo |
| 03 | [Estadística descriptiva](03_estadistica_descriptiva.ipynb) | Medidas de resumen, correlación y distribuciones | Una correlación de 0,89 con 5 casos no es concluyente |
| 04 | [Árbol de decisión (Iris)](04_arbol_de_decision_iris.ipynb) | Primer modelo de clasificación e interpretación del árbol | 100% de accuracy en un dataset de práctica |
| 05 | [Rotación de empleados](05_rotacion_empleados_eda_y_arbol.ipynb) | Análisis exploratorio y árbol de decisión sobre datos de RRHH | Con clases desbalanceadas, el accuracy (79,6%) engaña: decir "nadie se va" da 86,2% |
| 06 | [Clustering: KMeans y DBSCAN](06_clustering_kmeans_dbscan.ipynb) | Agrupamiento no supervisado, método del codo y silhouette | DBSCAN separa formas irregulares que KMeans no puede |
| 07 | [Detección de sarcasmo](07_nlp_deteccion_de_sarcasmo.ipynb) | NLP: limpieza de texto, stemming, lematización y bolsa de palabras | La regresión logística (73,0%) supera al Random Forest (71,2%) |
| 08 | [Clasificación de imágenes CIFAR-10](08_clasificacion_imagenes_cifar10.ipynb) | Red densa vs. red convolucional (Keras) | La CNN sube el accuracy de 48% a 69% |

## Cómo ejecutarlos

Se pueden abrir en Google Colab. Los que usan datasets de Kaggle tienen el link de descarga en la celda **Datos**; los datasets no se incluyen en el repositorio.
