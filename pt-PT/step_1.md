Podes usar uma tartaruga para escrever texto.

```python
turtle.write('Olá!')
```

Define a cor da tartaruga para criar texto colorido:

```python
turtle.color('deep pink')
turtle.write('Olá!')
```

Também podes alterar a fonte e o alinhamento do texto.

```python
estilo = ('Courier', 30, 'italic')
turtle.write('Olá!', font=estilo, align= 'center')
```

A fonte é uma lista ordenada que contém:

+ O nome da fonte, como 'Arial', 'Courier' ou 'Times New Roman'
+ O tamanho da fonte em pixeis
+ O tipo de fonte, que pode ser 'normal', 'bold', ou 'italic'

Para definir o alinhamento que controla a forma como o texto é posicionado com base na posição da tartaruga, utiliza o parâmetro `align`. `align` pode ser configurado para uma destas opções: 'left', 'center', 'right'

Exemplo: <iframe src="https://trinket.io/embed/python/52378ec006?start=result" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>