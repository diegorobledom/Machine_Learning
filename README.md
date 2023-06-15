# Machine_Learning

Este cuarderno es el resultado de una evidencia de aprendizaje, de la especialización en Analítica y Big Data, de la Institución Universitaria Digital de Antioquia.

En este cuaderno, se usa un set de 16.000 imágenes, que se puede descargar en el siguiente enlance: https://data.mendeley.com/datasets/6ps7gtp2wg/1

Lo que se pretende en este cuaderno, es evaluar la exactitud de una red neuronal, usando diferentes capas de convolución, así como diferentes Tamaños de Baches y diferentes tamaños de Épocas usanto las librerias torch y torchvision.

Primero se crear un set de datos a partir de datos propios, que posteriormente se partirán en 2 dataset (Train y Test).

Posteriormente se crean 3 modelos de redes neuronales, con difentes capas de convolución, por lo que se pretende examinar el comportamiento del modelo de acuerdo al número de capas suministradas.

Luego se examina el comportamiento de los modelos cambiando el número de baches y épocas en el entrenamiento, para sacar conclusiones

Para correr adecuadamente el cuaderno en Google Colab, es necesario:

1. Descargar el archivo en: https://data.mendeley.com/datasets/6ps7gtp2wg/1
2. cargar el archivo anterior a la carpeta raíz.
3. Configurar el entorno de ejecución, para permitir la utilización de GPU

DIEGO ALEJANDRO ROBLEDO MEJÍA
