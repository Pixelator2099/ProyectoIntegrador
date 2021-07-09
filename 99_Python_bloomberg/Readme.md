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

1. algopy	algopy	0.5.7	Algorithmic differentiation and Taylor polynomial approximations
2. bqfunc	bqfunc	0.6.0	Bloomberg library for financial closed-form expressions
1. mpmath	mpmath	1.1.0	Library for arbitrary-precision floating-point arithmetic
1. networkx	networkx	2.3	Creation, manipulation and study of the structure, dynamics and functions of complex networks
1. nltk	nltk	3.4.4	Natural Language Toolkit
1. numdifftools	numdifftools	0.9.39	Solves automatic numerical differentiation problems2. 
1. numexpr	numexpr	2.6.9	Fast numerical expression evaluator for NumPy
1. numpy	numpy	1.16.4	Array processing for numbers, strings, records and objects
1. openpyxl	openpyxl	2.6.2	Read/write Excel 2010 xlsx/xlsm files
1. pandas	pandas	0.25.0	Data structures and data analysis
1. patsy	patsy	0.5.1	Describe statistical models and for building design matrices
1. pytables	tables	3.5.2	Manage hierarchical datasets
1. scikit-image	skimage	0.15.0	Image processing routines for SciPy
1. scikit-learn	sklearn	0.21.2	Machine learning library
1. scipy	scipy	1.3.0	Scientific library
1. sqlalchemy	sqlalchemy	1.3.6	Python SQL toolkit and object relational mapper
1. statsmodels	statsmodels	0.10.1	Statistical modeling and econometrics
1. sympy	sympy	1.4	Library for symbolic mathematics
1. xlrd	xlrd	1.2.0	Extract data from Microsoft Excel spreadsheet files
1. xlwt	xlwt	1.3.0	Create spreadsheet files compatible with MS Excel 97/2000/XP/2003 XLS files

Visualización

1. bokeh	bokeh	1.3.2	Interactive visualization library for web browsers
1. bqplot	bqplot	0.12.25	Bloomberg library for plotting in the Jupyter notebook
1. bqviz	bqviz	2.2.0	Bloomberg visualization wrapper for bqplot
1. bqwidgets	bqwidgets	2.0.0	Bloomberg library for interactive HTML widgets in the Jupyter notebook
1. cycler	cycler	0.10.0	Cycles for Matplotlib
1. ipyleaflet	ipyleaflet	0.13.6	Jupyter / Leaflet bridge enabling interactive maps in the notebook
1. ipywidgets	ipywidgets	7.6.3	Interactive HTML widgets for Jupyter Notebook
1. matplotlib	matplotlib	3.1.1	2D plotting library
1. pillow	pillow	6.1.0	Imaging library
1. plotly	plotly	4.14.1	2D/3D interactive plotting library
1. seaborn	seaborn	0.9.0	High-level interface for drawing statistical graphics. Based on matplotlib.

Bloomberg

1. PyBQL	bql	0.106.0	Python API to access the Bloomberg Query Language
1. h5py	h5py	2.9.0	Interface to HDF5 library
1. hdf5	hdf5	1.10.4	Data model, library and file format to store and manage data
1. python	python	3.7.1	Python programming language
1. requests	requests	2.22.0	HTTP library for Python



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

# Get Parámetros comunes

FA_PERIOD_TYPE= tipo de listado de datos por ejemplo diario, mensual, anual, etc.

FA_ACT_EST_DATA = muestra datos actuales o estimados o ambos.

FA_PERIOD_REFERENCE=RANGE(2018,2025) rango de fechas de la consulta de datos.

# Técnicas de Análisis
Método William %R
0 Mercado sobrecomprado
-100 Mercado Sobrevendido
> mayor -80 vender menos a <-20 comprar

W_%R = ( PX_Max(YEAR) - PX_LAST ) / PX_Max(YEAR) - PX_Min(Year) 

# Otraas técnicas

[Entropic value at risk](https://en.wikipedia.org/wiki/Entropic_value_at_risk)

Maximización de r2 (Para el riesgo)

Heterocedasticidad condicional autorregresiva (ARCH)

[Regímenes de riesgo en el mercado de acciones colombiano](http://www.scielo.org.co/pdf/soec/n30/n30a14.pdf)

### Investigaciones

[Análisis entre ESG / tamaño empresa y factores de rendimiento](https://gupea.ub.gu.se/bitstream/2077/65529/1/gupea_2077_65529_1.pdf)

[A study inthe effectiveness of predicting default using the Merton model during financial distress](https://gupea.ub.gu.se/bitstream/2077/35973/1/gupea_2077_35973_1.pdf)

Es posible que si llegaste hasta aqupi estes buscando modelos para crear Factor Model o factores de predicción para la valoracíón. La teoría básica es crear modelos de regresíon linear, exponencial o factorial que permitan acercarse a predecir un momento de tiempo. Uno de los postulados es el modelo propuesto por el Nobel Robert Merton llamdo ICAPM en 1973 como una extensión del modelo de valoración de activos - capital asset pricing model (CAPM). 
En los siguientes enlace incluyo foros que se encuentren vigentes sobre el tema. 

[How to build a factor model?](https://quant.stackexchange.com/questions/17125/how-to-build-a-factor-model)

## Links

Prueba Jupiter Notebook

https://jupyter.org/try

Ejecuta código desde GITHUB y compartelo

https://mybinder.org/

