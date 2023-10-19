# deepgmi4
Deep learning aplicado a gammagrafía industrial versión 4:

En la notebook está la red neuronal con Keras usando un dataset de imágenes de perros y gatos de Kagle. Al ser una clasificación binaria, aplica para el dataset de imágenes de soldaduras como "Soldadura con falla/ Soldadura sin falla" que no tengo preparadas (Imágenes sin tagear, ilegibles, etc).

El output del modelo en Keras será un 0 o un 1 dependiendo de si la soldadura tiene una falla o no, siendo "1 = soldadura con falla" el caso positivo. Esto se reemplazó con un random generator de 0 y 1 en python ya que las imágenes quedaban en un arreglo de 150x150x3 (Esto está en la notebook).
Link:

http://deepgmi4.us-east-1.elasticbeanstalk.com/classify?var1=4&var2=7
