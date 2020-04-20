# Coronavirus-Data
Data actual de Coronavirus a nivel mundial
En el archivo Code se encuentra el código escrito en Python que permite obtener la data actualizada a nivel mundial dehttps://pomber.github.io/covid19/timeseries.json.


El codigo es una función que te permite obtener la data actual en dos versiones:
Si en la función get_coronavirus_data(opcion) reemplazamos opcion por 1 obtendremos la tabla de la siguiente forma:
## TABLA 01
![image](https://user-images.githubusercontent.com/36561152/79738680-afa03580-82c2-11ea-95d2-3920310c995c.png)
La tabla 01 se  puede descargar e importarlo a Stata, útil para trabajar a nivel de Panel Data debido a que ya está en formato long.
De igual manera, si se reemplaza la opción por 2 obtendremos la tabla de la siguiente forma:
## TABLA 02
https://user-images.githubusercontent.com/36561152/79739471-d743cd80-82c3-11ea-804c-ae37fd33e2f6.png
La tabla 02, es útil para tener una perspectiva horizontal de los países y su evolución. 

## Descargar tabla
Ahora, para descargar esta tabla, primero tendríamos que fijar nuestra ubicación donde querramos que se ubique este archivo
import os
import pandas as pd
os.chdir("C:\\Users\\CESAR\\Downloads\\TODO\\TODO\\New folder\\Consultant - Copy")
