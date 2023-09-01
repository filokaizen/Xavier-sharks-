# Proyecto de limpieza de datos Sharks
## Herramiendas usadas: Pandas, seabor and matplot


![klk](.\Images/megalodon.jpg)

El objeto de este proyecto didáctico y educativo fue limpiar el siguiente dataframe. https://github.com/filokaizen/Xavier-sharks-/blob/main/Data/attacks.csv

Para ello se puso la restricción de NO eliminar el número de columnas, mínimo 23 columnas y de igual forma reducir el número de filas a 2500 o menos.

**Nuestro objetivo**:

Determinar en que países se han producido más ataques de tiburones, desde el año de 1950 hasta el año 2023.

Metodología:

+ Analizar el dataframe
+ Eliminar de manera global los valores duplicados  en filas 
+ Los valores de las columnas con valores repetidos,se sustituyen por repeated 
- Los valores datos nulos, se rellenan con unknow


Análisis: 

Las columnas date, case_number, case_number1, case_number2, hablan de fechas(cada una tiene un formato diferente). Por lo que se transformna a enteros para comparlas.

Las col 'href' y 'href_formula' estan duplicadas, por lo que en una de ellos la lleno con repeated

Las dos ultimas columnas 'unnamed:_22', 'unnamed:_23' las cambio de nombre a borrar y las relleno con unknow, ya que no aportan nada útil

<h2> Resultados obtenidos</h2>

Tras limpiar el dataframe  y extraer la información de una manera organizada, se llegó a la conclusión de que  los países de Estados Unidos, Australia y Sudafrica encabezan la lista de los ataques de tiburones, esto se puede deber a que existe un mayor registro sobre los ataques de tiburones.

![klk](.\Images/output.png)


