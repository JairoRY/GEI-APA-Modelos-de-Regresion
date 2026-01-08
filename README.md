# Predicción del Rendimiento Estudiantil

Este repositorio contiene la implementación y el análisis de un proyecto de aprendizaje automático centrado en la predicción del rendimiento académico de los estudiantes. El trabajo ha sido realizado para la asignatura de Aprenentatge Automàtic (APA) del Grau en Enginyeria Informàtica (GEI) en la Universitat Politècnica de Catalunya.

El objetivo fundamental es aplicar y comparar diferentes modelos de regresión y clasificación utilizando el conjunto de datos "Student Performance" para determinar qué factores influyen de manera más significativa en las calificaciones finales.

## Estructura del Proyecto

* **PracticaAPA.ipynb**: Notebook de Jupyter que contiene todo el código para la limpieza de datos, el entrenamiento de los modelos y la generación de tablas y resultados.
* **student-mat.csv**: Archivo de datos que incluye variables sobre el entorno social, demográfico y escolar de los alumnos.
* **Informe pràctica APA.pdf**: Documento que detalla los objetivos, la metodología empleada, el análisis de los resultados y las conclusiones finales.

---

## Introducción al Uso

### Requisitos previos

Para ejecutar el código en un entorno local, es necesario contar con las siguientes librerías de Python:

* **numpy**
* **matplotlib** (pyplot)
* **seaborn**
* **pandas**
* **statsmodels**
* **scikit-learn**
* **yellowbrick**
* **scikit-optimize** (skopt)
* **dtreeviz**

### Instrucciones de ejecución

Se recomienda utilizar Google Colab para la ejecución, ya que el entorno ya incluye la mayoría de las librerías necesarias y facilita la visualización de los árboles de decisión.

1. Subir el archivo `.ipynb` a Drive y abrirlo con Google Colab.
2. Conectar el entorno de ejecución en la opción superior derecha.
3. En el margen izquierdo, abrir la sección de archivos y colocar el archivo `student-mat.csv` dentro de la ruta `content/sample_data/`.
4. Ejecutar todas las celdas mediante la opción "Entorno de ejecución > Ejecutar todas".

---

## Análisis y Modelos Realizados

El proyecto aborda el problema del rendimiento académico mediante el uso de diversas técnicas de modelado para evaluar su capacidad predictiva:

* **Métodos Lineales**: Se implementan y analizan modelos de Regresión Lineal, Regresión LASSO y K-Nearest Neighbors (KNN).
* **Métodos No Lineales**: Se exploran modelos más complejos como Multi-Layer Perceptron (MLP), Gradient Boosting y Random Forest.
* **Interpretabilidad**: Se incluye un análisis profundo para identificar las variables críticas, como el tiempo de estudio o el consumo de alcohol, que afectan las notas finales.
* **Protocolo de Remuestreo**: Se aplican técnicas para validar la robustez de los modelos y evitar el sobreajuste, asegurando que los resultados sean generalizables.
