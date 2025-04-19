# TFG_ALZHEIMER
# TFG: Desarrollo de un Modelo Predictivo para Identificar el Riesgo de Alzheimer

Este proyecto de fin de grado (TFG) tiene como objetivo desarrollar un modelo predictivo para clasificar a pacientes en función de sus datos clínicos y biomarcadores en tres categorías: **CN (Cognición Normal)**, **MCI (Mild Cognitive Impairment)** y **AD (Alzheimer's Disease)**. El proyecto se basa en el uso de técnicas de **Machine Learning (ML)** para la predicción temprana de Alzheimer, utilizando datos clínicos y biomarcadores como **P-tau181** y **Neurofilament Light (NfL)**. Los datos son sacados del repositorio de ADNI. 

## Descripción

El propósito de este trabajo es explorar la posibilidad de predecir el riesgo de Alzheimer utilizando un modelo de clasificación basado en datos clínicos y biomarcadores. El análisis se enfoca en:

1. **Preprocesamiento de datos**: Análisis y limpieza de un conjunto de datos de pacientes con información clínica y biomarcadores.
2. **Selección de modelos de Machine Learning**: Comparación de diferentes modelos para determinar cuál ofrece una mejor precisión y capacidad predictiva (Random Forest, Redes Neuronales Artificiales, etc.).
3. **Análisis de las métricas**: Evaluación de las métricas clave como precisión, sensibilidad, F1-score, y el impacto del balanceo de clases.
4. **Visualización e interpretación de resultados**: Generación de visualizaciones interactivas en Power BI para la interpretación de los resultados desde una perspectiva médica.

## Estructura del Proyecto

El proyecto está estructurado en varias fases:

### 1. **Preprocesamiento de Datos**
   - Limpieza de los datos: Se manejaron las fechas no alineadas, se resolvieron inconsistencias y se realizó un balanceo de clases utilizando técnicas de **downsampling**.
   - Integración de los datos: Se combinaron los datos clínicos y biomarcadores en un único dataset, eliminando duplicados y manejando datos faltantes.
   
### 2. **Modelos de Machine Learning**
   - **Random Forest (RF)**: Utilización de Random Forest multinomial para la clasificación de los tres grupos (CN, MCI y AD).
   - **Redes Neuronales Artificiales (ANN)**: Modelos ANN (FNN/MLP) para evaluar el rendimiento en la clasificación.
   - **Otros Modelos**: Comparación con otros enfoques como SVM y k-NN.

### 3. **Métricas de Evaluación**
   - Análisis detallado de métricas de rendimiento como **precisión**, **sensibilidad**, **especificidad**, **F1-score** y **AUC**.
   - Análisis del impacto del desbalance de clases y cómo se manejó en el preprocesamiento.

### 4. **Visualización de Resultados**
   - Creación de gráficos interactivos en Power BI para facilitar la interpretación de los resultados y su aplicación práctica en el diagnóstico médico.

## Objetivos de Investigación

El trabajo busca responder a las siguientes preguntas de investigación:

1. ¿Es necesario combinar biomarcadores y datos clínicos para mejorar la precisión del modelo?
2. ¿Qué modelos de Machine Learning son más efectivos para predecir el riesgo de Alzheimer?
3. ¿Qué variables tienen mayor peso predictivo en la clasificación de CN, MCI y AD?
4. ¿Qué técnicas de preprocesamiento mejoran el rendimiento del modelo?
5. ¿Cómo influye la combinación de datos longitudinales en la precisión del modelo?
6. ¿Cómo manejar el desbalance de clases en la modelización de los datos?

## Resultados Esperados

Se espera que este trabajo proporcione un modelo eficiente y preciso para la predicción temprana del Alzheimer, destacando las variables más importantes en el diagnóstico y mostrando cómo las técnicas de Machine Learning pueden ser útiles en la práctica médica.

## Herramientas y Tecnologías Utilizadas

- **Lenguaje de Programación**: Python 3.x
- **Librerías**: 
  - `scikit-learn` (para Machine Learning)
  - `pandas` y `numpy` (para procesamiento de datos)
  - `matplotlib`, `seaborn` (para visualización)
  - `Power BI` (para la creación de visualizaciones interactivas)
- **Plataforma**: Jupyter Notebook

## Instrucciones para Ejecutar el Proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tuusuario/TFG-Alzheimer-Predictive-Model.git
