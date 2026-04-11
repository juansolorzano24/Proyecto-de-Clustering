# Análisis de Clustering y Selección de Factores 
Este repositorio contiene un flujo de trabajo completo para la segmentación de datos mediante técnicas de aprendizaje no supervisado. El proyecto pone un énfasis especial en la **Selección de Factores**, asegurando que las variables utilizadas para el clustering aporten valor estadístico y reduzcan la dimensionalidad innecesaria.

## Resumen del Proyecto

El objetivo de este análisis es identificar patrones ocultos y agrupar observaciones similares dentro de un conjunto de datos. A diferencia de otros enfoques directos, este proyecto integra una fase crítica de preprocesamiento basada en la relevancia de las variables.

### Componentes Clave:
1.  **Análisis de Correlación**: Identificación de relaciones lineales entre variables numéricas para evitar la redundancia y la multicolinealidad.
2.  **Selección de Factores**: Filtrado y preparación de datos para optimizar el rendimiento de los algoritmos de clustering.
3.  **Agrupamiento (Clustering)**: Implementación de algoritmos para descubrir estructuras naturales en los datos.

## 📂 Estructura del Repositorio

* **`Clustering - Seleccion de Factores.ipynb`**: Notebook principal que documenta el proceso completo, desde la carga de librerías y preparación de datos hasta la selección de factores y ejecución del clustering.
* **`data/`** *(Carpeta sugerida)*: Directorio para almacenar los datasets utilizados (ej. archivos `.csv`).

## Tecnologías Utilizadas

El proyecto está desarrollado en **Python** utilizando el ecosistema estándar de Ciencia de Datos:

* **Pandas**: Manipulación y limpieza de estructuras de datos.
* **NumPy**: Operaciones matriciales y cómputo numérico.
* **Matplotlib / Seaborn**: Visualización de datos y matrices de correlación.
* **Scikit-learn**: Implementación de herramientas de preprocesamiento y algoritmos de clustering.

## Flujo de Trabajo

1.  **Preparación de Datos**: Importación de librerías y carga del set de datos inicial.
2.  **Análisis Exploratorio**: Inspección de variables numéricas y distribuciones.
3.  **Selección de Factores**:
    * Cálculo de matrices de correlación.
    * Evaluación de la importancia de las variables.
4.  **Modelado**: Aplicación del algoritmo de clustering seleccionado (ej. K-Means, Clustering Jerárquico).
5.  **Interpretación**: Análisis de los centroides o perfiles de los grupos resultantes.

