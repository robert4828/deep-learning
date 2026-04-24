# Deep Learning — Evaluacion Parcial N1
## DLY0100 | Duoc UC

Implementacion de una red neuronal multicapa (MLP) para clasificacion de imagenes del dataset Fashion MNIST usando TensorFlow/Keras.

## Descripcion

El modelo clasifica imagenes de ropa en 10 categorias (camisetas, pantalones, zapatillas, etc.) a partir de imagenes en escala de grises de 28x28 pixeles.

## Requisitos

```
tensorflow
numpy
matplotlib
seaborn
pandas
scikit-learn
```

Instalar dependencias:

```
pip install tensorflow numpy matplotlib seaborn pandas scikit-learn
```

## Estructura del notebook

- Parte 1: Introduccion y descripcion del problema
- Parte 2: Carga y preprocesamiento de datos
- Parte 3: Definicion y entrenamiento del modelo base, experimentos controlados
- Parte 4: Funciones de activacion, error y salida
- Parte 5: Optimizacion, regularizacion y ajuste de hiperparametros
- Parte 6: Evaluacion con metricas (accuracy, precision, recall, F1-score)
- Parte 7: Conclusiones

## Como ejecutar

1. Abrir el archivo `deeplearning_v4.ipynb` en Google Colab o Jupyter Notebook
2. Ejecutar las celdas en orden desde la primera
3. El dataset Fashion MNIST se descarga automaticamente desde Keras

## Resultados

El modelo final (MLP con Dropout, BatchNormalization y regularizacion L2) alcanza aproximadamente 87% de accuracy sobre el conjunto de test, con mejor desempeno en clases de formas distintivas como Trouser y Bag, y menor precision en prendas de silueta similar como Shirt, Pullover y Coat.
