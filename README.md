# Ocuppacy_Model
Este proyecto aplica técnicas avanzadas de machine learning y ciencia de datos para predecir la ocupación de una sala utilizando datos sensoriales. En el corazón del análisis está un modelo SVM con kernel RBF que fue entrenado y validado. 

# Predicción de Ocupación de Sala con SVM y PCA

Este repositorio contiene un proyecto de ciencia de datos y machine learning que utiliza sensores de sala para predecir la ocupación en tiempo real. El modelo utiliza un clasificador de vectores de soporte (SVM) con un kernel de función de base radial (RBF) y se beneficia de una reducción de dimensionalidad preliminar a través del Análisis de Componentes Principales (PCA).

## Estructura del Repositorio

- `occupancy_prediction.ipynb`: Cuaderno de Jupyter con todo el proceso de análisis de datos, desde la exploración inicial hasta el entrenamiento y la evaluación del modelo SVM.
- `data/`: Directorio que contiene el conjunto de datos utilizado (nota: agregar datos si es posible/legal compartirlos).
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
