# 🚴‍♂️ Análisis Predictivo – Probabilidad de Compra (Dataset Bikebuyer)

Notebook para predecir la intención de compra de clientes mediante cinco modelos de clasificación, con enfoque en segmentación.

## 🎯 Objetivos

- Documentar paso a paso en un notebook.
- Aplicar el proceso SEMMA al dataset `bikebuyer`.
- Realizar limpieza de datos, análisis exploratorio y entrenamiento de 5 modelos de machine learning.
- Evaluar desempeño de los modelos de clasificación
- Extraer conclusiones relevantes basadas en los resultados.

## 📌 Acciones Principales

- Carga y exploración inicial del dataset.
- Análisis exploratorio de datos (EDA) con visualizaciones para variables clave como ingreso, hijos, autos y distancia de traslado.
- Limpieza y transformación del dataset: manejo de valores nulos y eliminación de columnas irrelevantes.
- Codificación de variables categóricas para preparar los datos para el modelado.
- División del dataset en conjuntos de entrenamiento y prueba.
- Entrenamiento de cinco modelos de clasificación: Árbol de Decisión, KNN, Gradient Boosting, Random Forest y Extra Trees.
- Evaluación de modelos mediante F1-score, matriz de confusión y curva ROC-AUC.

## ✅ Conclusiones

- En términos de **exactitud** y **AUC-ROC**, el **Árbol de Decisión** mostró el mejor rendimiento global, seguido de cerca por el **KNN**, mientras que el **Gradient Boosting** tuvo un rendimiento sólido pero ligeramente inferior.
- El **Árbol de Decisión** se destacó en la identificación de la clase 0 (compradores) y mostró la mejor **sensibilidad**. Sin embargo, el **Gradient Boosting** y **KNN** también demostraron capacidades fuertes en términos de **precisión** y **recall**.
- En general, el **Árbol de Decisión** se posiciona como el modelo más robusto para este conjunto de datos, seguido por **KNN**, mientras que **Gradient Boosting**, aunque efectivo, podría beneficiarse de ajustes adicionales para mejorar la identificación de la clase positiva.

## 📩 Contacto

Si tienes alguna pregunta o sugerencia, contáctame por [LinkedIn](https://linkedin.com/in/roberto-eustaquio/)
