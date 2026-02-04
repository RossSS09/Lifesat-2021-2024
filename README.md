# Lifesat-2021-2024
Este proyecto aplica técnicas de Machine Learning para analizar la relación entre el desarrollo económico (PIB per cápita) y el bienestar social (Satisfacción de vida) a nivel global durante el periodo post-pandemia.

# Objetivo del Proyecto
El propósito es construir un modelo predictivo capaz de estimar la satisfacción vital de una nación basándose en su desempeño económico, utilizando datos reales de la OCDE y el Banco Mundial.

# Metodología
El flujo de trabajo se divide en cuatro etapas críticas:
- Ingesta y Limpieza de Datos: Fusión de datasets del Better Life Index (OCDE) y el PIB per cápita (World Bank) para los años 2021, 2022, 2023 y 2024.
- Análisis de Outliers: Identificación de países con economías extremas o comportamientos atípicos para evitar el sobreajuste (overfitting), centrando el modelo en el rango representativo ($23,500$ a $62,500$ USD).
- Modelado: * Regresión Lineal: Modelo paramétrico para encontrar la tendencia global.K-Nearest Neighbors (KNN): Modelo basado en instancias para validación por similitud local.
- Inferencia: Caso de estudio con la predicción de satisfacción para Chipre a través de los cuatro años analizados.

# Tecnologías Utilizadas
- Lenguaje: Python 3.10+
- Librerías de Ciencia de Datos: pandas, numpy, matplotlib.
- Machine Learning: scikit-learn (LinearRegression, KNeighborsRegressor).
- Deep Learning (Tensors): pytorch para validación manual de parámetros.
