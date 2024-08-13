En este proyecto, el objetivo fue mejorar un modelo base de series temporales para predecir las ventas totales de octubre de 2015 en distintas tiendas y ciudades. Se trabajó con un dataset que contenía 426 series temporales de ventas mensuales de enero de 2013 a septiembre de 2015.

Objetivos del Proyecto:
1. Establecimiento de un Benchmark: Se comenzó estableciendo un benchmark inicial utilizando el modelo base, lo que permitió tener una referencia clara para medir las mejoras subsecuentes.

2. Manipulación Eficiente del Dataset: Se utilizó pandas para realizar operaciones de resampling y agrupación, lo que facilitó la manipulación de las series temporales y la creación de nuevas características.

3. Generación de Variables: Se combinaron series temporales para generar nuevas variables predictoras, como las ventas totales de un artículo o de todos los artículos en una tienda, las cuales fueron utilizadas para alimentar un modelo XGBoost.

4. Identificación de Variables Autoexplicativas: Se identificaron y analizaron las variables que explican por sí mismas una parte significativa de la variabilidad en las ventas.

5. Iteración Rápida y Experimentación: Se realizaron múltiples experimentos y se probaron diferentes hipótesis para mejorar continuamente el rendimiento del modelo, enfatizando la importancia de la iteración rápida en el desarrollo de modelos de machine learning.

Al final del proyecto, se logró una mejora en la predicción de las ventas mensuales, subrayando la importancia de cada uno de los pasos mencionados en la construcción de un modelo efectivo para series temporales.
