
Imagina que necesitamos imprimir en pantalla la frase *¡Father!* dos veces. Podemos resolver esta tarea de la siguiente manera:

  ```python
print('Father!')
print('Father!')
```

En el caso más simple, esto funciona bien. Pero si la frase *Father!* se utiliza más de dos veces, y además en diferentes partes del programa, tendríamos que repetirla en todos los lugares, lo cual es incómodo. Los problemas con este enfoque comienzan cuando necesitamos cambiar la frase, lo cual ocurre con bastante frecuencia. Tendríamos que encontrar todos los lugares en donde se usa esta frase y realizar el reemplazo necesario.

Pero hay otra forma de hacerlo. Para evitar copiar la expresión, simplemente creamos una variable con ella:

```python
# greeting - se traduce como saludo
 greeting = 'Father!'
print(greeting)
print(greeting)
# => Father!
# => Father!
```

En la línea `greeting = 'Father!'` tomamos una variable con el nombre `greeting` y le asignamos el valor `'Father!'`. La variable apunta a los datos que hemos almacenado en ella. Gracias a esto, los datos se pueden utilizar múltiples veces sin duplicarlos constantemente.

Una vez que se ha creado la variable, se puede utilizar. Se inserta en los lugares donde solía estar nuestra frase. Cuando se ejecuta el código, el intérprete llega a la línea `print(greeting)` y reemplaza el contenido de la variable, y luego ejecuta el código.

Para el nombre de la variable se puede utilizar cualquier conjunto de caracteres válidos, que incluyen letras del alfabeto inglés, números y el guión bajo `_`. Sin embargo, no se puede colocar un número al principio. Los nombres de las variables son sensibles a mayúsculas y minúsculas, es decir, `hola` y `HOLA` son dos nombres diferentes para dos variables diferentes. En Python, la capitulación de letras es importante, nunca lo olvides.

El número de variables que se pueden crear es ilimitado. Los programas grandes contienen decenas y cientos de miles de nombres de variables. Así es como se ven dos variables dentro de un mismo programa:

  ```python
greeting1 = 'Father!'
print(greeting1)
print(greeting1)

greeting2 = 'Mother!'
print(greeting2)
print(greeting2)
```


Para que el programa sea fácil de leer, los programadores suelen crear variables lo más cerca posible del lugar donde se utilizan. Ahora necesitamos entender cómo modificarlas.
