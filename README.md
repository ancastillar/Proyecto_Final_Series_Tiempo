# Proyecto_Final_Series_Tiempo



En este repositorio se encuentra el proyecto final a la materia series de tiempo.
Este trabajo fue realizado por:

* Astrid Natalia Castilla Reyes
* Miguel Angel Quintero Martínez
* Juan Pablo Saenz



# **Introducción**


Bitcoin es la criptomoneda más antigua y conocida, lanzada por primera vez como código abierto en 2009 por el anónimo Satoshi Nakamoto. Bitcoin funciona como un medio de intercambio digital descentralizado, con transacciones verificadas y registradas en un libro de contabilidad público distribuido (el blockchain) sin necesidad de una autoridad de registro de confianza o un intermediario central. Actualmente esta criptomoneda es noticia en todo el mundo y su popularidad aumenta diariamente a medida que más y más personas/organizaciones comienzan a adoptarla. El objetivo de este tratabajo es realizar el pronóstico del precio del Bitcoin empleando 4 modelos diferentes: SARIMA, ARIMA, LSTM y árboles de desición. A partir de los resultados se realizó el contraste del desempeño de cada modelo mediante la métrica RMSE (Raíz del error cuadrático medio) para poder de encontrar el mejor modelo que permitiera obtener mejores predicciones. Por otra parte, quisimos analizar la existencia de una posible correlación entre Elon Musk y el precio del Bitcoin, debido a que este empresario en los últimos años ha invertido gran cantidad de dinero en Bitcoin. Para realizar este análisis se emplearon los datos de su Twitter personal y mediante técnicas de mineria ded texto extraemos los temas de nuestro interés: El Bitcoin. Finalmente, creamos un modelo que permite extraer las emociones que Elon transmite en sus tweets, con el fin de analizar su comportamiento y de que manera puede influenciar a sus seguidores.

# **Contenido del Git**


**Datos**

* Tweets de Elon Musk entre los años 2010 y 2021. Estos datos fueron obtenido mediante el API Tweepy: https://www.tweepy.org/
* Data histórica de la evolución del precio del Bitcoin desde el 2011- 2021. Datos obtenidos de Kaggle: https://www.kaggle.com/mczielinski/bitcoin-historical-data

**Lenguaje de programación empleados**

* Python 3.7

**Modelos adicionales empleado**

* Modelo LSTM que extrae las emociones de un texto determinado


**Dashboard**

El Dashboard del proyecto se encuentra en el siguiente enlace: https://wandb.ai/nata_123/Bitcoin/runs/10fk2crm?workspace=user-

Nota: Para visualizar el Dashboard se debe esperar un tiempo de 2-3 minutos para que se generen todas las visualizaciones.
Para encontrar las diferentes partes del análisis hay que dirigirse a la pestalla de "runs" y elegir la de interés.
