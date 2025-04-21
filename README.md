# Modelo de Predicción de Ventas por Día

Este proyecto implementa un modelo de predicción de ventas utilizando regresión lineal. El objetivo es predecir las ventas diarias basándose en un conjunto de datos históricos.

## Descripción

El modelo toma un conjunto de datos con las ventas de cada día, realiza un escalado de las características y entrena un modelo de regresión lineal. Luego, predice las ventas para un día específico y calcula el error cuadrático medio (RMSE) como medida de la precisión del modelo.

### Funciones principales:
- **Predicción de ventas**: Predice las ventas para cualquier día solicitado.
- **Cálculo de RMSE**: Mide la precisión del modelo.
- **Entrenamiento dinámico**: El modelo se reentrena cada vez que se hace una predicción, usando un subconjunto aleatorio de los datos.

## Requisitos

- Python 3.x
- Bibliotecas necesarias:
  - numpy
  - matplotlib
  - scikit-learn
  - gradio
  - uuid

## Instalación

Para instalar las dependencias necesarias, usa el siguiente comando:

pip install -r requirements.txt

##cUso
Ejecuta el script de Python para iniciar la interfaz de Gradio.

Ajusta el control deslizante para seleccionar el día a predecir.

El modelo predice las ventas para ese día y muestra la precisión (RMSE) del modelo.
