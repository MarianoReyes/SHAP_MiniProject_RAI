# SHAP - Interpretación de Predicciones de Churn en el Sector de Telecomunicaciones

## Integrantes del Proyecto
- Juan Angel Carrera 20593
- Esteban Aldana 20591
- Luis Pedro Gonzales 20008
- Juan Carlos Baján 20109
- José Mariano Reyes 20074

Este proyecto se centra en la aplicación de métodos de interpretación modelo-agnósticos, con un enfoque en SHAP (SHapley Additive exPlanations), para analizar y explicar las predicciones de churn de clientes en el sector de telecomunicaciones. Utilizando un dataset de churn de clientes de una compañía de telecomunicaciones disponible en Kaggle, se implementan modelos de predicción de churn y se aplica SHAP para entender la influencia de diversas características en las predicciones del modelo.

## Objetivo del Proyecto

El objetivo principal es demostrar cómo los métodos de interpretación modelo-agnósticos pueden proporcionar insights claros y comprensibles sobre las predicciones de modelos de machine learning. Específicamente, se busca:

1. **Implementar y evaluar modelos predictivos** como árboles de decisión y Random Forest.
2. **Aplicar SHAP** para analizar cómo diferentes características contribuyen a las predicciones de churn.
3. **Visualizar y comunicar la importancia y el efecto de las características** en las decisiones del modelo, utilizando visualizaciones de SHAP.
4. **Facilitar la toma de decisiones basadas en datos** en el sector de telecomunicaciones.

## Dataset

El dataset utilizado es el "Telco Customer Churn" disponible en Kaggle. Puedes descargarlo desde [aquí](https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data).

## Estructura del Proyecto

El proyecto está estructurado en un Jupyter Notebook que incluye:

1. **Setup**:
   - Importación de librerías necesarias.
   - Configuración inicial.
2. **Exploratory Data Analysis (EDA)**:
   - Descripción de las columnas.
   - Verificación de datos faltantes.
   - Análisis gráfico de datos.
3. **Modelos de Predicción**:
   - Implementación y evaluación de modelos de árboles de decisión y Random Forest.
   - Análisis SHAP para interpretar los modelos.
4. **Conclusión**:
   - Resumen de los hallazgos y discusión sobre la aplicabilidad de los resultados.

## Requisitos

- Python 3.x
- Librerías: pandas, numpy, matplotlib, seaborn, scikit-learn, shap

## Ejecución

- Ejecutar el notebook shap_miniproject.ipynb
