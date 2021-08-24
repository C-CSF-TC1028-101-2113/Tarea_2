# Cuadrante
**Decisiones - Número de cuadrante donde se encuentra un número (grados) entre 0 y 360**

Escribe un programa que lea un número entero que se encuentre entre 0 y 360 que representa los grados del plano cartesiano y que muestre como resultado el número de cuadrante en donde se encuentra: 

- el cuadrante 1 esta entre 0 y 90 grados. 
- el cuadrante 2 esta entre 90 y 180 grados. 
- el cuadrante 3 esta entre 180 y 270 grados.
- el cuadrante 4 esta entre 270 y 360 grados.

En caso de que el grado caiga en un eje, tu programa debe mostrar la palabra `"eje"`.
En caso de que el grado sea menor a cero o mayor a 360,  tu programa debe mostrar la palabra `"excede"`.

**Entrada**
- Un número entero que representa una cantidad de grados.

**Salida**
- La palabra cuadrante (en minúsculas) seguida del número de cuadrante correspondiente (por ejemplo: `cuadrante 2`), o bien alguna de las palabras `eje` o `excede`.

Estos son algunos ejemplos de ejecución del programa. La salida del programa debe de ser exactamente de la siguiente forma:

```plaintext
Introduce los grados: -10
excede

Introduce los grados: 90
eje

Introduce los grados: 45
cuadrante 1

Introduce los grados: 215
cuadrante 3
```
