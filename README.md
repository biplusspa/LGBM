# LGBM
Clasificación utilizando LightGBM (LGBM) (Core)
Clasificación utilizando LightGBM (LGBM) (Core)
Objetivo

Implementar un pipeline completo de machine learning para un problema de clasificación utilizando LightGBM (LGBM). Se hará especial énfasis en el Análisis Exploratorio de Datos (EDA), preprocesamiento, entrenamiento del modelo y optimización de hiperparámetros.



Dataset: Loan Prediction Dataset

Descripción del Dataset: El dataset de predicción de préstamos contiene información sobre solicitantes de préstamos, como sus ingresos, historial crediticio y otras características personales. El objetivo es predecir si un solicitante será aprobado para un préstamo basándose en estos factores.


Instrucciones

Parte 1: Carga y Exploración Inicial de Datos

Carga del Dataset:
Cargar el dataset desde Kaggle.
Exploración Inicial:
Revisar la estructura del dataset.
Describir las variables y su distribución.
Identificar y documentar valores faltantes y outliers.
Parte 2: Análisis Exploratorio de Datos (EDA)

Análisis Estadístico Descriptivo:
Calcular estadísticas descriptivas básicas (media, mediana, desviación estándar, etc.).
Analizar la distribución de las variables categóricas.
Visualizaciones:
Crear histogramas y gráficos de barras para entender la distribución de las variables.
Crear un mapa de calor para visualizar las correlaciones entre las variables.
Utilizar gráficos de dispersión para identificar posibles relaciones entre las variables.
Valores Faltantes y Outliers:
Detectar y tratar valores faltantes.
Identificar y manejar outliers.
Parte 3: Preprocesamiento de Datos

Transformación de Columnas:
Codificar variables categóricas utilizando One-Hot Encoding.
Escalar características numéricas utilizando StandardScaler.
División del Conjunto de Datos:
Dividir el dataset en conjuntos de entrenamiento y prueba.
Parte 4: Implementación de LightGBM (LGBM)

Entrenamiento del Modelo:
Entrenar un modelo de LGBM con hiperparámetros básicos.
Evaluar el modelo utilizando métricas de rendimiento como la exactitud, precisión, recall, F1-Score y ROC-AUC.
Optimización de Hiperparámetros:
Utilizar GridSearchCV para optimizar los hiperparámetros del modelo de LGBM.
Evaluación del Modelo Optimizado:
Evaluar el rendimiento del modelo optimizado y compararlo con el modelo inicial.
