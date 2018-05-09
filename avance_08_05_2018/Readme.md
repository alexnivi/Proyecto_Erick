# Proyecto Final: Factorización Cholesky
## Cómputo en paralelo.
## Objetivo: 
### Realizar una implementación de la factorización de cholesky en alguna de las tecnologías de cómputo distribuido o compartido visto en clase.

### Implementación de la factorización de Cholesky:

Alejandro:

Utilizando las referencias de entregas anteriores y combinándola con consultas prácticas de foros en internet, se consiguió la implementación del algoritmo secuencial (3 for anidados) del algoritmo de la factorización cholesky.

Para poder dar énfasis en el trabajo y no perder tiempo en particularidades se utilizó un muy rápido y pequeño script en python para generar matrices simétricas positivas definidas y almacenarlas en un archivo .txt con los elementos ordenados de forma secuencial.

Este algoritmo recibirá la dimensión deseada de la matriz a generar con elementos aleatorios, pero asegurándose de cumplir con la condición de positividad y simetría para poder ser posible la factorización, esto mediante la generación de una matriz triangular de números aleatorios y posteriormente haciendo una multiplicación matricial de esta última por su transpuesta.

Se modificó la entrega del algoritmo de factrorización Cholesky de entregas anteriores para que en lugar de tener ejemplos pequeños directamente especificados dentro del script, el algoritmo en C pudiera recibir como standar input el .txt generado por el algoritmo auxiliar en python.

En la carpeta implementación se encontrará un ejemplo de la generación y factorización de una matris simétrica positiva definida de dimensión 50 x 50. Los archivos donde se encontrarán los resultados serán:
 - MATRIX.txt para encontrar la matriz de referencia.
 - matrizSPD.txt donde estará la misma matriz, aunque con sus elementos almacenados en una sola columna para ser ingresados de esta forma secuencialmente al algoritmo ```chol.out``
 - fact.txt donde se encontrará la matriz triangular que factoriza a la matriz generada inicialmente.

 Los pasos siguientes serán:
  - La implementación del generador de matrices positivas definidas en un algoritmo en C.
  - La integración del filtro de Kalman, la función de verosimilitud normal y el algoritmo de optimización para completar el ejercicio.
  - Tiempo de ejecución.
  - Repetición del proceso con una implementación en OpenMP.

  Referencias:
  - [https://en.wikipedia.org/wiki/C_mathematical_functions]
  - [https://www.tutorialspoint.com/c_standard_library/c_function_calloc.htm]
  - [https://www.tutorialspoint.com/cprogramming/c_return_arrays_from_function.htm]
  - [https://stackoverflow.com/questions/19752644/row-to-column-and-column-to-row-using-awk]

Equipo:

En esta fase el equipo se dedicó a la implementación práctica en C así como revisión y corrección de errores del algoritmo desarrollado en entregas anteriores.


El trabajo escrito también cooperativo está [aquí](https://docs.google.com/document/d/1rZKXnf_56cQ0r0dyJ_M_H3khKhs_tSdgW3_IPnS2EfI/edit)

En la carpeta [Referencias](https://www.dropbox.com/home/Cholesky-Theory) tenemos los artículos escritos.