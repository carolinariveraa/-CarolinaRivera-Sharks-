# Shark Attacks

![Sharks](./pics/megalodon.jpg)

## 1. Contexto
La limpieza de datos es una tarea crucial y que consume mucho tiempo en cualquier proyecto de análisis de datos. Esto se debe a que los datos del mundo real pueden ser desordenados y desestructurados, lo que requiere un esfuerzo significativo para limpiar y prepararse antes de realizar cualquier análisis significativo.

El conjunto de datos Shark Attacks contiene datos en varios formatos y no permite sacar conclusiones por eso este proyecto se centra en la limpieza y organización de los datos.


## 2. Objetivo

El objetivo consiste en limpiar el DataFrame lo máximo posible para obtener conclusiones según lo que interese, los requisitos mínimos es que no se pueden eliminar columnas y el mínimo de filas debe ser 6000. Esto complica el ejercicio ya que hay columnas y filas llenas de valores nulos o de valores irrelevantes. 

## 3. Distribución

En la carpeta Notebook hay dos archivos, main.ipnyb contiene todos los pasos que he seguido para la limpieza del dataFrame, en la última linea exporto el dataframe como un csv y lo guardo en la carpeta de data. El otro archivo visual.ipnyb lo he creado para la visualización de los datos por lo tanto importo el csv ya limpio, llamado cleaned_shark.csv.

## 4. Metodologia

Se comienza con una exploración inicial para ver a qué nos enfrentamos, se observa que la mayor parte de valores son nulos por lo tanto hay que tomar la decisión de cómo se va a tratar la mayoría de valores dependiendo de la columna. 

Como he tratado los valores nulos:
- Rellenando con datos obtenidos de otras columnas
- Transformando columnas y sacando otros datos relevantes
- Mediante estimaciones o creando nuevas  categorías de información
- Rellenando con ‘Unknown’ ya que en algunos casos hacer estimaciones iba a provocar falsedad en las conclusiones 

Después de la exploración inicial voy columna tras columna analizando que tipo de datos hay, eliminando aquellos que no sirven y guardando en otras columnas los que podrían interesar más adelante. 

Una vez se han eliminado los valores nulos y aprovechado las columnas vacías, convierto una de las columnas en el índice ya que aunque no se pueden eliminar si que las puedo transformar.

Se han agregado nuevos datos obtenidos a partir de los existentes como
- Estación del año
- Continente
- Mar


## 5. Resultados y analisis

Una vez llegados a este punto enumero qué análisis se podrían hacer a partir de los datos obtenidos:

- Casos por
    - Año 
    - Mes
    - Pais
    - Dia de la semana
    - Estación
- Edad más atacada
- Relación de pais con mes
- Porcentaje de fatalidad

## 6. Conclusiones

Como era de esperar la mayoría de accidentes se producen en verano en USA, además el grupo de edad más atacado es entre 15 y 25 años. 
Por último el porcentaje de fatalidad es del 24,4%

## 7. Bibliografi

- https://www.kaggle.com/teajay/global-shark-attacks 



