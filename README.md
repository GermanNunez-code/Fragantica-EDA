# 🌸 Análisis Exploratorio de Datos (EDA) y Sistema de Recomendación de Perfumes

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Plotly](https://img.shields.io/badge/Plotly-Interactive-green)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-yellow)

## 📖 Descripción del Proyecto

Este proyecto es un análisis exhaustivo del dataset de **Fragantica**, diseñado para explorar el fascinante mundo de la perfumería a través de los datos. El objetivo principal es descubrir tendencias ocultas, analizar el comportamiento de las marcas y entender las preferencias de los consumidores basándose en notas olfativas y acordes.

Además del análisis exploratorio, el proyecto incluye un **Sistema de Recomendación de Perfumes** basado en contenido, que utiliza técnicas de Procesamiento de Lenguaje Natural (NLP) para sugerir fragancias similares.

## 🚀 Características Principales

*   **Limpieza y Preprocesamiento de Datos**: Tratamiento de valores nulos, normalización de texto y conversión de tipos de datos.
*   **Análisis Univariante y Multivariante**:
    *   Distribución de puntuaciones y popularidad.
    *   Análisis de tendencias temporales (lanzamientos por año).
    *   Preferencias olfativas por género.
*   **Visualizaciones Avanzadas e Interactivas** (Plotly):
    *   **Sunburst Charts**: Para visualizar la jerarquía de acordes principales.
    *   **Radar Charts**: Comparación de perfiles olfativos entre marcas de lujo (Chanel, Dior, Tom Ford).
    *   **Scatter Plots**: Relación entre la valoración media y la popularidad de las marcas.
*   **Sistema de Recomendación**:
    *   Implementación de **TF-IDF** (Term Frequency-Inverse Document Frequency) para vectorizar las notas y acordes.
    *   Cálculo de **Similitud del Coseno** para encontrar y recomendar los 10 perfumes más similares a uno dado.

## 🛠️ Tecnologías Utilizadas

*   **Python**: Lenguaje principal.
*   **Pandas & NumPy**: Manipulación y análisis de datos.
*   **Plotly Express & Graph Objects**: Visualizaciones interactivas de alto nivel.
*   **Matplotlib & WordCloud**: Visualizaciones estáticas y nubes de palabras.
*   **Scikit-learn**: Implementación del sistema de recomendación (TF-IDF, Linear Kernel).

## 📂 Estructura del Proyecto

```
📁 Fragantica-EDA
│
├── 📄 Fragantica_EDA.ipynb   # Cuaderno principal con todo el análisis y código
├── 📄 fra_cleaned.csv        # Dataset utilizado (asegúrate de tenerlo en la misma carpeta)
└── 📄 README.md              # Documentación del proyecto
```

## 📊 Ejemplos de Visualizaciones

El cuaderno genera visualizaciones interactivas que permiten:
*   Explorar qué notas (Salida, Corazón, Fondo) son las más populares.
*   Ver cómo ha evolucionado la industria del perfume en las últimas décadas.
*   Comparar visualmente la "firma olfativa" de diferentes marcas.

## 🤖 Cómo usar el Sistema de Recomendación

Al final del cuaderno `Fragantica_EDA.ipynb`, encontrarás la sección del sistema de recomendación.

1.  Ejecuta todas las celdas para cargar los datos y entrenar el modelo TF-IDF.
2.  Usa la función `get_recommendations('Nombre del Perfume')`.
3.  ¡Obtén una lista de los 10 perfumes más parecidos basados en sus componentes!

```python
# Ejemplo de uso
get_recommendations('Acqua Di Gio')
```

## 👤 Autor

**Germán** - *Data Analyst & Data Scientist*

---
*Este proyecto forma parte de mi portfolio profesional en Data Science.*
