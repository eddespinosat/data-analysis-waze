# data-analysis-waze

# Análisis Exploratorio de Datos (EDA) en Waze

Este repositorio agrupa una serie de notebooks en los que se analiza el comportamiento de casi 15,000 usuarios de la aplicación Waze. A lo largo de las diferentes partes se aborda el estudio del abandono de usuarios (churn) y se comparan los patrones de uso entre quienes continúan utilizando la aplicación y quienes dejan de hacerlo.

**Contenido:**

- **Parte 1: (..._2.ipynb)** análisis inicial de la deserción de usuarios, enfocándose en las diferencias en el comportamiento de conducción y uso de la app.
- **Parte 2 (..._3.ipynb):** exploración de datos con visualizaciones y técnicas para el manejo de valores atípicos, examinando la relación entre variables como sesiones, viajes, kilómetros recorridos, días de actividad y tipo de dispositivo.
- **Parte 3 (..._4.ipynb):** estudio más profundo utilizando un enfoque estructurado para identificar patrones de comportamiento que distinguen a los usuarios retenidos de los que abandonaron la aplicación.
- **Parte 4 (..._5.ipynb):** investigación de la relación entre el tipo de dispositivo (Android/iPhone) y la cantidad de viajes en Waze, a través de análisis de deserción, exploración de datos y pruebas de hipótesis, revelando patrones de uso diferenciados.
- **Parte 5 (..._6.ipynb):** se construyó un modelo de regresión logística para predecir churn (deserción) en usuarios de Waze. Se realizó EDA, limpieza de datos y selección de variables, detectando outliers y multicolinealidad.
- **Parte 6 (..._7.ipynb):** se construyeron y compararon dos modelos avanzados de machine learning (Random Forest y XGBoost) para predecir el churn. Se realizoó ingeniería de características para crear variables más predictivas y optimización de hiperparámetros con GridSearchCV. El modelo XGBoost destacó por su mayor recall. Finalmente, se exploró una técnica para ajustar el umbral de decisión del modelo, adaptándolo a las necesidades del negocio para identificar de manera más efectiva a los usuarios con probabilidad de abandonar la app.
