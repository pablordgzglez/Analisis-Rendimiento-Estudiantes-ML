# Predicción del rendimiento académico con aprendizaje automático

Este proyecto aplica técnicas de aprendizaje automático supervisado y no supervisado para analizar datos de estudiantes y predecir su nota final (T3). Además, se realiza una exploración de perfiles estudiantiles mediante clustering.

## Archivos necesarios

Coloca todos los siguientes archivos en la misma carpeta:

- **ProyectoFinal.ipynb**: notebook principal con todo el flujo del proyecto.
- **rendimiento_estudiantes_train.csv**: conjunto de entrenamiento con la variable T3.
- **rendimiento_estudiantes_test_vacio.csv**: conjunto de test sin T3.

## Ejecución

1. Abre el notebook **ProyectoFinal.ipynb** en Jupyter o VSCode.
2. Selecciona **Run All** para ejecutar todo el análisis de principio a fin, incluyendo limpieza, entrenamiento, evaluación de modelos y clustering.

## Salidas

El notebook genera:

- Métricas de rendimiento de los modelos (MAE, RMSE, R²).
- Visualizaciones del análisis exploratorio y de los resultados.
- Un archivo **predicciones_finales.csv** con las predicciones sobre el conjunto de test real.

## Requisitos

Este proyecto usa las siguientes librerías de Python:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn


