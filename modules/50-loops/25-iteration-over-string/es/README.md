
Con la ayuda de los bucles, no sólo se pueden procesar números, sino también cadenas de texto. Por ejemplo, se puede obtener un carácter específico por su índice, así como formar cadenas de texto en bucles.

A continuación se muestra un ejemplo de código que imprime las letras de cada palabra en una línea separada:

```python
def print_name_by_symbol(name):
    i = 0
    # Esta condición se cumplirá hasta el final de la cadena,
    # incluyendo el último carácter. Su índice es `length - 1`.
    while i < len(name):
        # Accedemos al carácter por su índice
        print(name[i])
        i = i + 1

name = 'Arya'
print_name_by_symbol(name)
# => 'A'
# => 'r'
# => 'y'
# => 'a'
```


Lo más importante en este código es establecer la condición correcta en `while`. Esto se puede hacer de dos formas: `i < len(name)` o `i <= len(name) - 1` - ambas conducirán al mismo resultado.
