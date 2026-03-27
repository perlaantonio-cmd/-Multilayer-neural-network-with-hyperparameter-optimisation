# -Multilayer-neural-network-with-hyperparameter-optimisation
# Predicción de Cultivares de Vino mediante Redes Neuronales Multicapa
Este repositorio contiene la implementación de una Red Neuronal Multicapa (MLP) diseñada para clasificar vinos italianos en tres cultivares distintos, basándose en sus características químicas. 
El proyecto incluye el Análisis Exploratorio de Datos (EDA), el diseño de la arquitectura de la red, la optimización de hiperparámetros (mediante Optuna) y la evaluación de métricas de rendimiento.

## 📂 Contenido del Repositorio

* `Assignment6.ipynb`: Libreta de Jupyter principal con el código, análisis y resultados.
* `wine.csv`: Dataset original (*Wine Recognition Data*).
* `wine_multilayer_nn_optimized.keras`: Modelo final entrenado y exportado (listo para inferencia).

## 🛠️ Requisitos Previos
Para ejecutar este proyecto localmente, asegúrate de tener instalado Python 3.8+ y las siguientes librerías:
* `tensorflow` (o `keras`)
* `pandas`
* `numpy`
* `matplotlib` / `seaborn`
* `scikit-learn`
* `optuna`

## 🚀 Instrucciones de Ejecución

### Opción A: Ejecución en Google Colab (Recomendado)
1. Abre [Google Colab](https://colab.research.google.com/).
2. Selecciona `Archivo > Abrir bloc de notas > GitHub`.
3. Pega el enlace de este repositorio y selecciona el archivo `Assignment6.ipynb`.
4. Asegúrate de subir el archivo `wine.csv` al entorno de ejecución temporal de Colab (icono de carpeta a la izquierda) antes de correr las celdas.
5. Ejecuta el cuaderno celda por celda (`Entorno de ejecución > Ejecutar todas`).

### Opción B: Ejecución Local
1. Clona este repositorio:
   ```bash
   git clone [https://github.com/perlaantonio-cmd/-Multilayer-neural-network-with-hyperparameter-optimisation]
