
Dentro de un bucle, al igual que dentro de una función, se pueden ejecutar instrucciones. Por lo tanto, dentro de un bucle se puede utilizar todo lo aprendido anteriormente, como por ejemplo, estructuras condicionales.

Imagina una función que cuenta cuántas veces aparece una letra en una oración. Aquí tienes un ejemplo de cómo funcion un bucle de esta forma:

```python
count_chars('El miedo corta más profundo que las espadas.', 'e')  # 4
# Si no se encuentra ninguna coincidencia, el resultado es 0
count_chars('Sansa', 'y')  # 0
```

Antes de ver el contenido de la función, piensa en lo siguiente:

* ¿Es esta operación una agregación?
* ¿Cuál será la condición para verificar la aparición de un carácter?

```python
def count_chars(string, char):
    index = 0
    count = 0
    while index < len(string):
        if string[index] == char:
            # Solamente contamos los caracteres que coinciden
            count = count + 1
        # El contador se incrementa en cualquier caso
        index = index + 1
    return count
```


Esta es una tarea de agregación. Aunque no cuenta todos los caracteres para calcular la suma, es necesario analizar cada carácter. La diferencia clave de este bucle con los que se han visto anteriormente es que contiene una condición en su cuerpo.

La variable `count` solo se incrementa cuando el carácter actual coincide con el carácter esperado. De lo contrario, esta función es típicamente una función agregada que devuelve la cantidad de caracteres necesarios.
