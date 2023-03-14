# EDA 

## Análisis de las temperaturas en las capitales andaluzas

### Índice

#### :card_index_dividers: Carpetas 

**Data**
Carpeta repositorio con todos los archivos .csv que se han usado para el trabajo.

**Notebooks**
Carpeta repositorio con todos los notebooks que he usado, tanto de prueba como de trabajo para la extración de los datos.

**Utils**
Carpeta repositorio gráficos exportados del trabajo. También con el documento .ipynb donde realicé el código de extracción de la data.

#### :books: Librerias 

**Librerías**
import pandas as pd
import numpy as np
import seaborn as sns
from plotly.offline import init_notebook_mode, iplot, plot
import plotly as py
init_notebook_mode(connected=True)
import plotly.graph_objs as go
from wordcloud import WordCloud
import matplotlib.pyplot as plt
from sklearn.datasets import load_iris, load_boston

#### :computer: Code 

:page_facing_up: **Primera parte**

+ Limpieza de datos.
+ Crear nuevas columnas.
+ Conversión de formatos.
+ Eliminación de los NaN.

:bar_chart: **Gráficos**

+ Diferentes tipos de gráficos.
+ Sugiero ver la imagen exportada en la carpeta utils.

:clipboard: **Otros**

+ Hay un .describre() para tener información de la tabla
+ Existe también una tabla creada de forma semimanual para ver las máximas y mínimas de por cada provincia.


**Autoria**
Jorge Fernández