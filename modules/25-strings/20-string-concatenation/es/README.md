
En el desarrollo web, los programas operan constantemente con cadenas de texto. Todo lo que vemos en los sitios web está representado de alguna manera como texto. Este texto, en su mayoría, es dinámico, es decir, se obtiene a partir de diferentes partes que se unen.

Para unir cadenas de texto, es necesario realizar una **concatenación**:

```python
# El operador es el mismo que se utiliza para sumar números,
# pero aquí tiene un significado diferente (semántica)
print('Dragon' + 'stone')  # => Dragonstone
```

La concatenación de cadenas siempre se realiza en el mismo orden en el que se escriben los operandos. El operando izquierdo se convierte en la parte izquierda de la cadena, y el operando derecho en la parte derecha. Aquí hay algunos ejemplos adicionales:

```python
print('Kings' + 'wood')      # => Kingswood
print('Kings' + 'road')      # => Kingsroad
print("King's" + 'Landing')  # => King'sLanding
```

Como puedes ver, puedes concatenar cadenas incluso si se escriben con diferentes tipos de comillas.

Un espacio en blanco es un carácter igual que los demás, por lo que la cantidad de espacios en blanco que coloques en una cadena será la misma en la cadena resultante:

```python
# Colocamos un espacio en blanco en la parte izquierda
print("King's " + 'Landing')  # => King's Landing

# Colocamos un espacio en blanco en la parte derecha
print("King's" + ' Landing')  # => King's Landing
```
