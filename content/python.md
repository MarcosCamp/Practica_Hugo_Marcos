# Estructuras de Datos en Python

Las **estructuras de datos** son una de las partes fundamentales en cualquier lenguaje de programación. En este módulo, exploraremos algunas de las estructuras de datos más comunes en **Python**, como las listas, las tuplas, los diccionarios y los conjuntos. Cada una tiene características que las hacen útiles en diferentes situaciones.

## 1. Listas (Lists)

Las **listas** son colecciones ordenadas, mutables y pueden contener elementos de diferentes tipos. Puedes agregar, eliminar y modificar elementos dentro de una lista.

### Características:
- Ordenadas: Los elementos de una lista mantienen el orden en el que fueron agregados.
- Mutables: Puedes cambiar el contenido de una lista después de haberla creado.
- Pueden contener elementos duplicados.

### Ejemplo:

```python
# Crear una lista de números
numeros = [1, 2, 3, 4, 5]

# Agregar un número a la lista
numeros.append(6)

# Acceder a un elemento por su índice
print(numeros[2])  # Esto imprimirá el valor 3

# Eliminar un elemento por su valor
numeros.remove(4)

# Imprimir la lista modificada
print(numeros)
