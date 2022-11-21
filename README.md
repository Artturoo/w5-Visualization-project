![Ironhack logo](https://i.imgur.com/1QgrNNw.png) 
# Visualization Project

![portada](https://discoverthenew.ituser.es/files/201604/analitica-datos.jpg)


## Introducción:

El proyecto de esta semana consiste en hacer un ETL: extracción, transformación y carga, para luego visualizar/analizar esos datos y sacar conclusiones de los mismos. 

En este proyecto se utilizará Tableau Public para la elboración de los gráficos, tablas etc.

Para el análisis, se ha extraido información relacionada con las subastas de inmuebles(vivienda) en España. 

Posteriormente se observará si existe alguna relación entre el precio del metro cuadrado de alguna provincia con el crecimiento evolutivo de los últimos 5 años en España.

---


## Análisis del número de subasta por provincia y su crecimiento poblacional.

En primer lugar, tras la extracción de subastas por provincia donde el estado actual sea 'celebrándose' y cuyo tipo de bien subastado sea 'inmuebles y viviendas' se observa que, actualmente Barcelona y Madrid son aquellas donde se subasta un mayor número de viviendas. 

El número total de subastas en estas dos provincias es altamente más significativo que en el resto de provincias. 

Posteriormente se analiza la evolución del crecimiento poblacional y se observa que tanto Madrid como Barcelona vuelven a ser las dos provincias con mayor crecimiento. Tiene sentido que aquellas provincias cuya densidad poblacional sea mayor tengan un mayor número de subastas.

Sin embargo, se observa que Barcelona tiene menor crecimiento poblacional que Madrid (10 millones por debajo) y aún así celebra un mayor número de subastas.
 

Tras analizar el crecimiento evolutivo por comunidades autónomas, se observa que Andalucia es la comunidad que mas ha crecido en estos útlimos cinco años, seguida de Cataluña y Madrid respectivamente. En esta ocasión, Cataluña se situa por encima de Madrid.

Por lo tanto, se concluye que no existe ningún tipo de relación entre el crecimiento poblacional y el número de subastas.




## Relación entre el precio del metro cuadrado, el crecimiento poblacional y el valor de la subasta.

En este apartado, se analizará si existe algún tipo de correlación entre el precio del metro cuadrado, el crecimiento poblacional y el impacto en el valor de la subasta.

En primer lugar, se realizó una gráfica de barras para analizar el precio del metro cuadrado en las diferentes ciudades de España.

En este caso, la comunidad autónoma con mayor precio del metro cuadrado es el Pais Vasco, en concreto la ciudad de San Sebastian, seguido de Madrid con un precio del 20% menor. La tercera comunidad autónoma es Navarra. Por lo tanto, no existe evidencia de que el precio del metro cuadrado está correlacionado con el número de subastas. 

A continuación, tras el analisis entre el valor de la subasta y el precio del metro cuadrado, se concluye que:

- Al realizar la media del valor de cada subasta en cada comunidad autónoma, se aprecia un mayor valor de la subasta en Madrid con respecto al resto de comunidades. Pais Vasco le sigue con un 50% menos, llegando actualmente a una media de 400mil euros. Ambas comunidades autónomas cuentan con un elevado precio en el metro cuadrado.

- Con los datos extraidos, se confirma que existe una relación significativa entre la media del precio del metro cuadrado en las comunidades autónomas con la media del valor de las subastas. A mayor precio de metro cuadrado se aprecia un mayor valor de la subasta. 

Sin embargo, con los datos obtenidos no hay evidencia que tanto el precio del metro cuadrado como el valor de la subasta, estén relacionados con una mayor crecimiento poblacional.




