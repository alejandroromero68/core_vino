# core_vino

# Predicción de la Calidad del Vino 🍷

Este proyecto utiliza técnicas de clasificación para predecir la calidad del vino basándose en sus características físico-químicas. 
Es una aplicación práctica para consolidar conceptos de preprocesamiento de datos, selección de características, 
entrenamiento y evaluación de modelos de clasificación, y análisis de resultados mediante métricas y visualizaciones.

## Objetivo

El objetivo principal es desarrollar un modelo de clasificación que prediga la calidad del vino utilizando un conjunto de datos conocido 
como **Wine Quality Dataset**. A lo largo del proyecto, se implementan varias técnicas de machine learning 
y análisis de datos para optimizar el rendimiento de los modelos.

## Dataset: Wine Quality Dataset

El conjunto de datos incluye información sobre muestras de vino tinto con las siguientes características físico-químicas:

- **Acidez fija**
- **Acidez volátil**
- **Ácido cítrico**
- **Azúcar residual**
- **Cloruros**
- **Dióxido de azufre libre**
- **Dióxido de azufre total**
- **Densidad**
- **pH**
- **Sulfatos**
- **Alcohol**

La calidad del vino está clasificada en una escala de 0 a 10, donde valores más altos indican mejor calidad.

## Estructura del Proyecto

1. **Carga y Exploración de Datos**:
   - Revisión de la estructura del dataset y sus distribuciones.
   - Tratamiento de valores nulos y outliers.
2. **Preprocesamiento de Datos**:
   - Selección de características relevantes.
   - Escalado de las características.
   - División en conjuntos de entrenamiento y prueba.
3. **Entrenamiento de Modelos**:
   - Implementación de al menos tres modelos de clasificación: KNN, Random Forest y Regresión Logística.
   - Optimización de hiperparámetros mediante validación cruzada.
4. **Evaluación de Modelos**:
   - Evaluación mediante métricas como exactitud, precisión, recall, F1-Score y matriz de confusión.
   - Visualización de curvas ROC y cálculo del AUC.
5. **Análisis y Comparación**:
   - Comparación del rendimiento de los modelos.
   - Discusión de fortalezas y debilidades de cada enfoque.

## Requisitos

Para ejecutar el proyecto necesitas las siguientes dependencias:

- Python 3.8+
- Bibliotecas:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

Instala las dependencias ejecutando:

```bash
pip install -r requirements.txt

