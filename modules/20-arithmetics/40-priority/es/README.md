Supongamos que necesitamos calcular la siguiente expresión: `2 + 2 * 2`. Así es como se escribe:

```python
print(2 + 2 * 2)  # => 6
```

En las matemáticas escolares, existe el concepto de "prioridad de operación". La prioridad determina el orden en el que se deben realizar las operaciones. La multiplicación y la división tienen mayor prioridad que la suma y la resta, y la potenciación tiene la mayor prioridad de todas las operaciones aritméticas. Por ejemplo: `2 ** 3 * 2` se calculará como `16`.

Sin embargo, a menudo los cálculos deben realizarse en un orden diferente al de la prioridad estándar. En ese caso, se deben utilizar paréntesis para establecer la prioridad. Así se hacía en la escuela, por ejemplo: `(2 + 2) * 2`. Los paréntesis se pueden colocar alrededor de cualquier operación y pueden anidarse tantas veces como sea necesario. Aquí tienes algunos ejemplos:

```python
print(3 ** (4 - 2))  # => 9
print(7 * 3 + (4 / 2) - (8 + (2 - 1)))  # => 14
```

Lo más importante es asegurarse de que los paréntesis estén correctamente emparejados. Esto, a menudo, es la causa de errores no sólo para principiantes, sino también para programadores experimentados. Para mayor comodidad, coloca el paréntesis de apertura y cierre de inmediato, y luego escribe la parte interna. El editor en nuestro sitio web (y la mayoría de los otros editores de código) lo hacen automáticamente: escribes `(` y el editor agrega automáticamente `)`. Esto también se aplica a otros caracteres emparejados, como comillas. Hablaremos de ellos en futuras lecciones.

A veces, una expresión puede ser difícil de entender visualmente. En ese caso, se pueden colocar paréntesis sin afectar la prioridad:

```python
# Antes
print(8 / 2 + 5 - -3 / 2)  # => 10.5

# Después
print(((8 / 2) + 5) - (-3 / 2))  # => 10.5
```


Es importante recordar que el código se escribe para ser entendido por personas. Las personas leerán el código y las máquinas solamente lo ejecutarán. Para las máquinas, el código es correcto o incorrecto. No hay código "más" o "menos" comprensible para ellas.
