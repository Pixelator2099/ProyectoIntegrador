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

## Links

Prueba Jupiter Notebook

https://jupyter.org/try

Ejecuta código desde GITHUB y compartelo

https://mybinder.org/
