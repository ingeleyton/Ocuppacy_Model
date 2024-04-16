# Ocuppacy_Model
Este proyecto aplica técnicas avanzadas de machine learning y ciencia de datos para predecir la ocupación de una sala utilizando datos sensoriales. En el corazón del análisis está un modelo SVM con kernel RBF que fue entrenado y validado. 

# Predicción de Ocupación de Sala con SVM y PCA

Este repositorio contiene un proyecto de ciencia de datos y machine learning que utiliza sensores de sala para predecir la ocupación en tiempo real. El modelo utiliza un clasificador de vectores de soporte (SVM) con un kernel de función de base radial (RBF) y se beneficia de una reducción de dimensionalidad preliminar a través del Análisis de Componentes Principales (PCA).

## Características Clave:
Análisis Exploratorio de Datos (EDA): Profunda inmersión en los patrones y correlaciones de los datos sensoriales.
Preprocesamiento y Reducción de Dimensionalidad: Normalización de datos y PCA para simplificar los conjuntos de datos sin comprometer la información esencial.
Modelización Predictiva: Implementación de SVM con kernel RBF, optimizado para lograr la máxima precisión.
Validación Cruzada: Uso de k-fold cross-validation para garantizar la generalización del modelo.
Interpretación de Resultados: Evaluación detallada del rendimiento del modelo utilizando métricas como la precisión, recall y F1-score.

## Estructura del Repositorio

- `occupancy_prediction.ipynb`: Cuaderno de Jupyter con todo el proceso de análisis de datos, desde la exploración inicial hasta el entrenamiento y la evaluación del modelo SVM.
- `data`: Contenida en el archivo 'Occupancy_Estimation.csv' 
- `requirements.txt`: Archivo que lista todas las dependencias necesarias para ejecutar el proyecto.
- `LICENSE`: El archivo de licencia del proyecto.

## Configuración del Entorno

Para instalar las dependencias necesarias, ejecute el siguiente comando:

```bash
pip install -r requirements.txt
```

## Ejecución del Cuaderno
Para ejecutar el cuaderno, asegúrate de que Jupyter Notebook o JupyterLab esté instalado en tu entorno y corre el siguiente comando desde la terminal en el directorio del proyecto:
```bash
jupyter notebook
```
