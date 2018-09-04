Podemos usar a tartaruga para escrever o texto.

```python
turtle.write ('Olá!')
```

Defina a cor da tartaruga para criar um texto colorido:

```python
turtle.color('deep pink')
turtle.write ('Olá!')
```

Também podemos alterar a fonte e o alinhamento do texto.

```python
style = ('Courier', 30, 'italic')
turtle.write ('Olá!', font=style, align='center')
```

A fonte é uma tupla contendo:

+ O nome da fonte, como 'Arial', 'Courier' ou 'Times New Roman'
+ Definimos o tamanho da fonte em pixels
+ O tipo de fonte, que pode ser 'normal', 'bold'(negrito) ou 'italic'(itálico)

Para definir o alinhamento que controla como o texto é posicionado com base na posição da tartaruga, use o parâmetro `align(alinhar)`. O `align(alinhar)` pode ser definido para uma destas opções: 'left'(à esquerda), 'center'(centralizado), 'right'(à direita)

Exemplo: <iframe src="https://trinket.io/embed/python/f41e0305c3?start=result" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>