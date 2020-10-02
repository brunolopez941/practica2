# Practica2
## Descripción

En este proyecto tendrás que describir, para cada algoritmo, la complejidad computacional de cada uno de ellos, y tendrás que anotar el resultado del algoritmo para un conjunto de valores de entrada determinado.

### Algoritmo 1
```
Entradas:
x
y
------
resultado <- 1
for i form 1 to y:
  resultado <- resultado * x
return resultado
```

##### Resultados
Escribe en la siguiente sección, para el conjunto de entradas indicado, el resultado que daría el algoritmo.

|x|y|resultado|
|-|-|-|
|2|5|**32**|
|3|3|**27**|
|10|8|**100000000**|


##### Complejidad
Escribe en esta sección la complejidad computacional que coresponde con el algoritmo anterior en las diferentes notaciones que creas correspondientes (*O* y/o Ω y/o Θ).

**Tu respuesta aquí**

### Algoritmo 2
```
Entradas:
x
valores
------
for each val in valores:
  if val > x:
    return false
  else if val == x:
    return true
return false
```

##### Resultados
Escribe en la siguiente sección, para el conjunto de entradas indicado, el resultado que daría el algoritmo.

|x|valores|resultado|
|-|-|-|
|4|[1, 2, 4, 7, 9]|**Tu respuesta aquí**|
|9|[1, 3, 5, 6, 7]|**Tu respuesta aquí**|
|3|[5, 6, 7, 8, 9, 10]|**Tu respuesta aquí**|


##### Complejidad
Escribe en esta sección la complejidad computacional que coresponde con el algoritmo anterior en las diferentes notaciones que creas correspondientes (*O* y/o Ω y/o Θ).

**Tu respuesta aquí**

### Algoritmo 3
```
Entradas:
valores_x
valores_y
------
for each valx in valores_x:
  y_contiene_x <- false
  for each valy in valores_y:
    if valx == valy:
      y_contiene_x <- true
  if y_contiene_x == false:
    return false
return true
```

##### Resultados
Escribe en la siguiente sección, para el conjunto de entradas indicado, el resultado que daría el algoritmo.

|valores_x|valores_y|resultado|
|-|-|-|
|[1, 2, 3]|[1, 2, 3, 4, 5]|**Tu respuesta aquí**|
|[2, 4]|[7, 5, 2, 8, 3]|**Tu respuesta aquí**|
|[3, 5, 2]|[6, 5, 3, 7, 1, 2]|**Tu respuesta aquí**|


##### Complejidad
Escribe en esta sección la complejidad computacional que coresponde con el algoritmo anterior en las diferentes notaciones que creas correspondientes (*O* y/o Ω y/o Θ).

**Tu respuesta aquí**