Español

# PLN-2022-1C

TP de la materia mas Notebooks



Vimos conda que es un entorno virtual como un contenedor donde instalaremos solo lo que necesitaremos . Podemos manejar versiones especificas de python, etc

La bueno y porque usamos jupyter notbook es porque los resultados se guardan en memoria por lo que por ejemplo volver a cargar un dataset



### Librerias mas usadas

````python
import matplotlib.pyplot as plt
import pandas as pd #this is how I usually import pandas
import sys #only needed to determine Python version number
import matplotlib #only needed to determine Matplotlib version number
````


### ATAJOS

````python
import pandas as pd
x=pd.DataFrame()

# Elegimos las funciones que vamos a importar de pandas
from pandas import DataFrame, read_csv
x=DataFrame()
````





### FEATURES 

#### NLTK

Natural Language Toolkit : NLTK es una plataforma líder para crear programas de Python para trabajar con datos de lenguaje humano

````shell
# Resource punkt not found.
  Please use the NLTK Downloader to obtain the resource:

import nltk
nltk.download('punkt')
  
For more information see: https://www.nltk.org/data.html
````

Esto es porque nos falta datos

#### Instalación de datos NLTK

NLTK viene con muchos corpus, gramáticas de juguete, modelos entrenados, etc. Se publica una lista completa en: https://www.nltk.org/nltk_data/

#### Instalador interactiva

Ejecute el intérprete de Python y escriba los comandos

```python
import nltk
nltk.download()
```

<img src="C:\Users\GIANPIER\AppData\Roaming\Typora\typora-user-images\image-20220508221515270.png" alt="image-20220508221515270" style="zoom:50%;" />



Podemos instalar una collection de paquetes de datos, o bien ir a la sección de **Corpora** y elegir específicamente el que iremos a usar

https://www.nltk.org/data.html







````python
# El operador """_""" toma el enter no hay necesidad de poner \n

text = """ HOLA
Salte de linea
Salete de nuevo """
````



