# 1. ¿Qué es Lazypredict?

- Lazypredict es una biblioteca de Python que permite entrenar y evaluar rápidamente múltiples modelos de Machine Learning con el mínimo esfuerzo.

- Su objetivo principal es facilitar la comparación de distintos algoritmos sin necesidad de realizar una extensa configuración manual, lo que resulta especialmente útil en la fase exploratoria de un proyecto.

- Funciona tanto en tareas de regresión como de clasificación.

- Software libre: licencia MIT


# 2. Características principales

- **Entrenamiento rápido:** Ejecuta múltiples modelos de aprendizaje automático con solo unas pocas líneas de código.

- **Comparación automática:** Genera un resumen con métricas de rendimiento (Accuracy, RMSE, R², etc.) para facilitar la selección del mejor modelo.

- **Compatibilidad:** Funciona con scikit-learn y es fácil de integrar en flujos de trabajo de Machine Learning.

- **Facilidad de uso:** No requiere ajustar hiperparámetros ni realizar preprocesamiento avanzado.


# 3. Recomendaciones

- Lazypredict no realiza tratamiento de datos como imputación de valores faltantes o normalización de variables de manera automática.

- Lazypredict no optimiza los hiperparámetros y solo usa los valores predeterminados de scikit-learn. Para mejorar el rendimiento de los modelos, se recomienda hacer ajuste de hiperparámetros manual o automático después de identificar los modelos más prometedores.
