
**Las operaciones lógicas** son expresiones, por lo tanto, se pueden combinar con otras expresiones. Por ejemplo, queremos verificar si un número es par, es decir, si es divisible por dos. En programación, se utiliza el siguiente enfoque: se verifica el residuo de la división por dos:

* si el residuo es `0`, el número es par
* si el residuo no es `0`, el número es impar

El residuo de la división es un concepto simple pero importante en aritmética, álgebra, teoría de números y criptografía. Consiste en dividir un número en grupos iguales y si queda algo al final, ese es el residuo de la división.

Por ejemplo, repartimos caramelos equitativamente entre personas:

* 7 caramelos, 2 personas: 2 x 3 + residuo 1 — 7 no es divisible por 2
* 21 caramelos, 3 personas: 3 x 7 + residuo 0 — 21 es divisible por 3
* 19 caramelos, 5 personas: 5 x 3 + residuo 4 — 19 no es divisible por 5

El operador `%` calcula el residuo de la división:

* `7 % 2` → `1`
* `21 % 3` → `0`
* `19 % 5` → `4`

Vamos a combinar el operador lógico "igualdad" `==` y el operador aritmético `%` en una sola expresión y escribiremos una función para verificar si un número es par:

```python
def is_even(number):
    return number % 2 == 0

print(is_even(10))  # => True
print(is_even(3))   # => False
```

Las operaciones aritméticas tienen mayor prioridad que las operaciones lógicas. Esto significa que primero se calcula la expresión aritmética `numero % 2` y luego se compara el resultado con cero para verificar la igualdad.

Ahora vamos a escribir una función que recibe una cadena de texto y verifica si esa cadena comienza con la letra `a` en minúscula.

Algoritmo:

1. Obtener y guardar el primer carácter de la cadena de texto argumento
2. Comparar si el carácter es igual a la letra `a`
3. Devolver el resultado

```python
def is_first_letter_an_a(string):
    first_letter = string[0]
    return first_letter == 'a'

print(is_first_letter_an_a('orange'))  # => False
print(is_first_letter_an_a('apple'))   # => True
```


Para comprender lo que está sucediendo aquí, intente explicar el proceso de manera similar a cómo desglosamos el ejemplo de `is_even()`.

Ahora sabes que las operaciones de comparación se utilizan en programación junto con las operaciones aritméticas. Pero recuerda que la igualdad se representa con `==`. De esta manera, no confundirás esta operación con la asignación de un valor a una variable.
