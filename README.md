
# Implementación de una Red Neuronal para Clasificación Binaria

Este cuaderno presenta la implementación de una red neuronal multicapa para resolver un problema de clasificación binaria. El objetivo es demostrar los conceptos fundamentales de las redes neuronales, incluyendo la generación de datos sintéticos, la inicialización de parámetros, las funciones de activación, la función de pérdida y el proceso de entrenamiento (propagación hacia adelante y hacia atrás).

## Contenido

1.  **Generación del Conjunto de Datos:**
    *   Se crea un conjunto de datos sintéticos utilizando distribuciones gaussianas para simular dos clases separables en un espacio bidimensional.

2.  **Funciones Clave de la Red Neuronal:**
    *   `initialize_parameters_deep`: Función para inicializar aleatoriamente los pesos y bias de la red.
    *   Funciones de activación: Implementación de las funciones `sigmoid` y `relu` junto con sus derivadas.
    *   `cross_entropy_loss`: Implementación de la función de pérdida de entropía cruzada binaria.

3.  **Función de Entrenamiento (`train`):**
    *   Implementación del proceso de propagación hacia adelante para calcular las predicciones.
    *   Implementación del proceso de retropropagación para calcular los gradientes.
    *   Actualización de los parámetros mediante el descenso de gradiente.

4.  **Entrenamiento de la Red:**
    *   Se define la arquitectura de la red neuronal (número de capas y neuronas).
    *   Se inicializan los parámetros.
    *   Se entrena la red utilizando el conjunto de datos generado, mostrando la disminución de la función de pérdida a lo largo de las iteraciones.

5.  **Evaluación y Visualización:**
    *   Se prueba la red entrenada con datos nuevos para observar su capacidad de generalización.
    *   Se visualiza la frontera de decisión aprendida por la red, mostrando cómo clasifica los puntos en el espacio de características.

## Requisitos

Este cuaderno utiliza las siguientes librerías:

*   `numpy`
*   `matplotlib`
*   `sklearn` (para `make_gaussian_quantiles`)
*   `IPython`

Asegúrate de tener estas librerías instaladas en tu entorno Python. Si estás utilizando Google Colab, la mayoría de ellas ya estarán disponibles.

## Uso

Puedes ejecutar las celdas de este cuaderno secuencialmente para seguir el flujo de trabajo. Experimenta con diferentes arquitecturas de red, tasas de aprendizaje y número de iteraciones para ver cómo afectan el rendimiento del modelo.

Este proyecto es parte del curso "Fundamentos de Redes Neuronales con Python y Keras" de Platzi, diseñado para comprender los principios básicos detrás de la construcción y el entrenamiento de redes neuronales.

## Autora
Nydia Mejía Zavala
