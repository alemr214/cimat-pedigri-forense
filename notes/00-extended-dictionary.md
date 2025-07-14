# Diccionario de Variables: Datos Combinados

La base de datos combinada cuenta con un total de 879336 registros. Cada entrada corresponde a los resultados de la comparación entre un par víctima-familiar.

## FAM_Sample_info_id

Prefijo de la clave de familiar. Columna derivada de ```FAM_Sample_info```. Se calculó como el primer elemento de un split por espacios.

## FAM_Sample_info_rel

Sufijo de la clave de familiar. Columna derivada de ```FAM_Sample_info```. Se calculó como el segundo elemento de un split por espacios.

La lista de sufijos es:

- ' D'
- ' P',
- ' U',
- 'A',
- 'B',
- 'C',
- 'D',
- 'E',
- 'F',
- 'H',
- 'I',
- 'J',
- 'M',
- 'O',
- 'P',
- 'Q',
- 'R',
- 'S',
- 'T',
- 'U',
- 'X',
- 'Y',
- 'Z',
- 'o',
- None

## VIC_Sample_info_id

Prefijo de la clave de victima. Columna derivada de ```VIC_Sample_info```. Se calculó como el primer elemento de un split por espacios.

## VIC_Sample_info_re

Sufijo de la clave de victima. Columna derivada de ```VIC_Sample_info```. Se calculó como el segundo elemento de un split por espacios.

## Shared_Markers

Numero de marcadores compartidos. Mientras 



## k0

Numero de marcadores con ningun alelo compartido


## k1

Numero de marcadores con un alelo compartido


## k2

Numero de marcadores con dos alelo compartido


## Share_allele

Numero de alelos compartidos


## Value

LR


## True_positive

Categoria de Parentesco

## Marcadores

Set de datos


## Software

Herramienta de análisis por pares


## Datos

Tipo de datos Simulados / Reales


## Kinship

Tipo de parentesco Paternidad/Hermandad


## File

Archivo de donde se obtuvo 


## Hoja

Hoja de calculo 


## Sheet

Proporción


## Value_range

Categoria por Rangos