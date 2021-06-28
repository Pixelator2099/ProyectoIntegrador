# Bloomberg Notas y aplicaciones con Python

En wikipedia la describen como : Bloomberg LP es una compañía estadounidense de asesoría financiera, software, data y media bursátil. Tiene una tercera parte del mercado, similar a Thomson Reuters. Fundada en 1981.

## Bloomberg BQNT

BQNT es un entorno de programación basado en computadoras Jupiter. Las computadoras Jupiter son un proyecto open source para ofrecer notebooks compartidas para empresas, aulas de clase o laboratorios de investigación.

Una de sus características es que permite separar el código en pequeño bloques llamados CHUNKS que pueden ejecutarse solo o en cadena, en su página web indican que otros lenguajes se pueden utilizar.

## Librerias recomendadas

Acceso a la base de datos 
import bql

Creación de objetos persistentes como label, listas, input, etc.
import ipywidgets as widgets

Manejador de datos y manipulación en memoria con objetos Data FRAME
import pandas as pd

Libreria de enfoque científico para la manipulación de arreglos
import numpy as np

Manejador de gráficos estadísticos
from matplotlib import pyplot as plt

Libreria para copiar objetos y romper la referencia
from copy import copy

Funciones estadísticas
import statistics

## Fundamentos BQL

Los comandos BQL tiene el formato 
LET ()
GET ()
FOR ()

En donde LET es un área para definir variables con el  formato #Var = CampoBQL
En donde GET es un área para indicar los campos a recuperar, por ejemplo bs_mkt_sec_other_st_invest() es un indicador que muestra los valores líquidos y otras inversiones a corto plazo.
En donde FOR es un área para indicar el universo a consultar. Pueder ser un índice, una empresa o un bono. Se deben consultar por el nombre del ticket, por ejemplo la empresa Tesla tiene el código "TSLA US Equity".

# Get - Campos comunes

'PX_LAST' 
'PX_OPEN' 
'PX_HIGH'
'PX_LOW'

TOT_RETURN_INDEX_NET_DVDS  en lugar de PX_LAST, indica el índice de retorno total entre dos días.

enterprise_value
sales_growth
total_return

# Técnicas de Análisis
Método William %R
0 Mercado sobrecomprado
-100 Mercado Sobrevendido
>-80 vender <-20

W_%R = ( PX_Max(YEAR) - PX_LAST ) / PX_Max(YEAR) - PX_Min(Year) 

### Investigaciones

[Análisis entre ESG / tamaño empresa y factores de rendimiento](https://gupea.ub.gu.se/bitstream/2077/65529/1/gupea_2077_65529_1.pdf)

[A study inthe effectiveness of predicting default using the Merton model during financial distress](https://gupea.ub.gu.se/bitstream/2077/35973/1/gupea_2077_35973_1.pdf)

## Links

Prueba Jupiter Notebook

https://jupyter.org/try

Ejecuta código desde GITHUB y compartelo

https://mybinder.org/

