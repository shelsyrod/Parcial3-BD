# Parcial Final - Big Data

En este repositorio se encuentra el proyecto correspondiente al tercer corte de la materia Big data, se encuentra el proceidmiento, las fuentes de informacion, erra mientas usadas y finalmente una muestra de los resultados

## Desarrollo ⚙️

1) Dibujar franjas de Bollinger con una ventana de 20 horas en Quick Sight para el proyecto del precio del dólar (posiblemente se necesite una consulta en athena).

https://www.fidelity.com/learning-center/trading-investing/technical-analysis/technical-indicator-guide/bollinger-bands#:~:text=Bollinger%20Bands%20are%20envelopes%20plotted,Period%20and%20Standard%20Deviations%2C%20StdDev.

2) Crear un pipeline de procesamiento para los datos de noticias del parcial 2 usandoPyspark ML. Se debe vectorizar usando TFxIDF. Implementar el pipeline en AWS GLUE o ejecutarlo en EMR con spark submit.
Usar de guía:

https://spark.apache.org/docs/latest/ml-pipeline.html

3) Implementar 2 productores que envíen datos de las acciones(como el ejemplo de clase) a un stream en AWS Kinesis. Implementar un consumidor que se encargue de tomar de la cola y muestre una alerta cada vez que el precio de alguna acción supera la franja superior de Bollingener. Implementar un segundo consumidor que se encargue de tomar de la cola y muestre una alerta cada vez que el  precio de alguna acción esté por debajo de la franja inferior de Bollingener. Cada uno de los productores y consumidores deben estar en una máquina EC2.


Entregar código en github con pruebas unitarias.
Se debe sustentar el parcial en la fecha prevista.

## Construido con 🛠️

Herramientas que utilizamos para el proyecto

* [AWS](https://www.awsacademy.com/vforcesite/LMS_Login) - servicios en la nube
* [Terminal]
* [Scripts en python]

## Fuentes de informacion 📖

* https://www.fidelity.com/learning-center/trading-investing/technical-analysis/technical-indicator-guide/bollinger-bands#:~:text=Bollinger%20Bands%20are%20envelopes%20plotted,Period%20and%20Standard%20Deviations%2C%20StdDev.
* https://spark.apache.org/docs/latest/ml-pipeline.html
* https://docs.aws.amazon.com/es_es/quicksight/latest/user/adding-a-calculated-field-analysis.html
* https://spark.apache.org/docs/latest/api/python/

## Resultados ✅

#### * Punto 1

![Bollinger](https://github.com/shelsyrod/Parcial3-BD/blob/master/GraficaFranjaBollinger.JPG)

#### * Punto 2

![ElTiempo](https://github.com/shelsyrod/Parcial3-BD/blob/master/ElTiempo.png)
![ElEspectador](https://github.com/shelsyrod/Parcial3-BD/blob/master/ElEspectador.png)

#### * Punto 3

![ElEspectador](https://github.com/shelsyrod/Parcial3-BD/blob/master/Punto3.JPG)
![ElEspectador](https://github.com/shelsyrod/Parcial3-BD/blob/master/Punto3.1.JPG)
![ElEspectador](https://github.com/shelsyrod/Parcial3-BD/blob/master/Punto3.2.JPG)

## Autores ✒️

* **Juan Carlos Castro Guevara**  - [Correo](juan.castro03correo.usa.edu.com)
* **Shelsy Natalia Rodriguez Barajas**  - [Correo](shelsy.rodriguez01@correo.usa.edu.co)
