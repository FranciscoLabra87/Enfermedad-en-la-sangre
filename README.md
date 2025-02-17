Análisis de Enfermedad en la Sangre - Machine Learning

Descripción

Este repositorio contiene un Jupyter Notebook titulado Desafío - Enfermedad en la sangre.ipynb, en el cual se lleva a cabo un análisis de datos para predecir la presencia de una enfermedad en la sangre mediante algoritmos de Machine Learning.

El notebook incluye:

Carga y exploración de datos para entender la distribución de las variables.

Análisis estadístico de las características con herramientas como statsmodels.

Preprocesamiento de datos, incluyendo escalado, normalización y balanceo con SMOTE.

Entrenamiento de modelos de clasificación, como Regresión Logística, Árbol de Decisión y XGBoost.

Evaluación de modelos con métricas como precisión, recall, F1-score y matriz de confusión.

Tecnologías Utilizadas

Jupyter Notebook (Entorno interactivo para desarrollo y análisis de datos)

Python

Pandas, NumPy (Manejo y preprocesamiento de datos)

Matplotlib, Seaborn (Visualización de datos)

Scikit-learn (Modelos de Machine Learning y evaluación)

XGBoost (Optimización del modelo)

Statsmodels (Análisis estadístico y detección de multicolinealidad)

SMOTE (Balanceo de datos desbalanceados)

Uso del Notebook

Para abrir y ejecutar el archivo Desafío - Enfermedad en la sangre.ipynb, sigue estos pasos:

Abre una terminal y navega hasta el directorio donde se encuentra el archivo.

Ejecuta el siguiente comando:

jupyter notebook

Se abrirá Jupyter en el navegador, donde podrás seleccionar el archivo y ejecutar las celdas de código de forma secuencial.

Estructura del Notebook

El notebook está organizado en las siguientes secciones:

Importación de librerías: Se cargan todas las dependencias necesarias.

Carga de datos: Se importa el dataset y se realiza una revisión inicial.

Análisis exploratorio: Se generan estadísticas descriptivas y visualizaciones.

Preprocesamiento: Se eliminan valores nulos, se normalizan variables y se balancea el dataset.

Entrenamiento de modelos: Se prueban diferentes algoritmos de clasificación.

Evaluación de modelos: Se comparan los resultados con diversas métricas.

Conclusiones: Se analizan los hallazgos y se plantean mejoras futuras.

Evaluación de Resultados

Se analiza la importancia de las variables en la predicción.

Se comparan los modelos para determinar el mejor rendimiento.

Se revisa la multicolinealidad para evitar problemas de sobreajuste.

Contribución

Si deseas contribuir, por favor:

Haz un fork del repositorio.

Crea una nueva rama (git checkout -b feature/nueva-funcionalidad).

Realiza tus cambios y haz un commit (git commit -m 'Descripción del cambio').

Sube tus cambios (git push origin feature/nueva-funcionalidad).

Abre un Pull Request.
