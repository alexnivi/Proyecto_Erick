#Implementación de algoritmos

 - gen_mat.py:
	Se creó este script como apoyo, esto para generar matrices positivas definidas de manera simple en python.
	Se ejecuta con el comando:
```python gen_mat.py $n$```

donde se debe sustituir $n$ por la dimensión de la matriz cuadrada positiva definida a generar.

El resultado se almacenará en el archivo:
```matrizSPD.txt```
que será el insumo del algoritmo de factorización de cholesky:
```chol.c```

el cual imporime en primer lugar la matriz a factorizar y posteriormente la matriz factor.
