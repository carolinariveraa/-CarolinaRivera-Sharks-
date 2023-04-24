# -CarolinaRivera-Sharks-

## 1. Contexto

Data cleaning is a crucial and time-consuming task in any data analysis project, often taking up to 60–70% of the total time. This is because real-world data can be messy and unstructured, requiring significant effort to clean and prepare before any meaningful analysis can be done.

One such dataset that required extensive cleaning is the Shark Attacks dataset, which is available on Kaggle. The dataset contained data in various formats and was not ready for analysis, so I decided to undertake the task of cleaning and organizing it to extract useful insights about shark attacks.

I utilized Pandas to perform the data cleaning and transformation, ensuring that the final dataset was free of errors and inconsistencies. This project enabled me to develop my skills in data cleaning and prepare a high-quality dataset for analysis.

## 2. Objetivo

El objetivo consiste en limpiar el DataFrame lo máximo posible para obtener conclusiones según lo que interese, los requisitos mínimos es que no se pueden eliminar columnas y el mínimo de filas debe ser 6000. Esto complica el ejercicio ya que hay columnas y filas llenas de valores nulos o de valores irrelevantes. 

## 3. Distribución

En la carpeta Notebook hay dos archivos, ...ipnyb contiene todos los pasos que he seguido para la limpieza del dataFrame, en la última linea exporto el dataframe como un csv y lo guardo en la carpeta de data. El otro archivo...ipnyb lo he creado para la visualización de los datos por lo tanto importo el csv ya limpio, llamado cleaned_shark.csv.

## 4. Metodologia

Se comienza con una exploración inicial para ver a qué nos enfrentamos, se observa que la mayor parte de valores son nulos por lo tanto hay que tomar la decisión de cómo se va a tratar la mayoría de valores dependiendo de la columna. 

Como he tratado los valores nulos:
Rellenando con datos obtenidos de otras columnas
Transformando columnas y sacando otros datos relevantes
Hacer estimaciones o crear nuevas  categorías de información
rellenando con ‘Unknown’ ya que en algunos casos hacer estimaciones iba a provocar falsedad en las conclusiones 

Después de la exploración inicial voy columna tras columna analizando que tipo de datos hay, eliminando aquellos que no sirven y guardando en otras columnas los que podrían interesar más adelante. 

Una vez se han eliminado los valores nulos y aprovechado las columnas vacías, convierto una de las columnas en el índice ya que aunque no se pueden eliminar si que las puedo transformar.

Por lo tanto las columnas me quedarían así:

| Antes      | Después  |
|----------  |----------|
| Case Number| Cell 2   | 
| Date       | Cell 5   | 
| Year       | Cell 2   | 
| Type       | Cell 5   | 
| Country    | Cell 2   | 
| Area       | Cell 5   | 
| Location   | Cell 2   | 
| Activity   | Cell 5   | 
| Name       | Cell 2   | 
| Sex        | Cell 5   | 
| Age        | Cell 2   | 
| Injury     | Cell 5   | 

## 5. Resultados y analisis

Una vez llegados a este punto enumero qué análisis se podrían hacer a partir de los datos obtenidos:

- Relación entre actividad y lesión o si hubo muerte
- Temporada en la que más ataques se produzcan
- Frecuencia de ataques `por país
- Especies que produzcan más accidentes fatales

## 6. Conclusiones

## 7. Bibliografia



