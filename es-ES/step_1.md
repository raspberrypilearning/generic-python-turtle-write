Puedes usar una tortuga para escribir texto.

```python
turtle.write('¡Hola!')
```

Establece el color de la tortuga para crear texto en color:

```python
turtle.color('deep pink') # rosa intenso
turtle.write('¡Hola!')
```

También puedes cambiar la fuente y la alineación del texto.

```python
estilo = ('Courier', 30, 'italic') # fuente, tamaño, cursiva
turtle.write('¡Hola!', font = estilo, align = 'center') # centrado
```

La fuente es una tupla que contiene:

+ El nombre de la fuente, como 'Arial', 'Courier' o 'Times New Roman'
+ El tamaño de la fuente en píxeles
+ El tipo de fuente, que puede ser 'normal', 'bold' o 'italic' (normal, negrita o cursiva)

Para establecer la alineación que controla cómo se posiciona el texto en función de la posición de la tortuga, usa el parámetro `align` (alineación). `align` se puede establecer en una de estas opciones: 'left', 'center', 'right' (izquierda, centro, derecha)

Ejemplo: 

<iframe src="https://trinket.io/embed/python/58e35de686?start=result" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>