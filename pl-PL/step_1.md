Możesz użyć żółwia, aby napisać tekst.

```python
turtle.write("Witaj!")
```

Ustaw kolor żółwia, aby utworzyć kolorowy tekst:

```python
turtle.color('deep pink')
turtle.write('Witaj!')
```

Możesz także zmienić czcionkę i wyrównanie tekstu.

```python
style = ('Courier', 30, 'italic')
turtle.write('Witaj!', font=style, align='center')
```

Parametrowi font przypisujemy wartość zmiennej style, która zawiera:

+ Nazwę czcionki, np. 'Arial', 'Courier' lub 'Times New Roman'
+ Rozmiar czcionki w pikselach
+ Wybrany typ czcionki: 'normal', 'bold' lub 'talic' (odpowiednio: normalna, pogrubiona lub kursywa)

Użyj parametru `align`, aby ustawić sposób wyrównania tekstu względem położenia żółwia. Parametr `align` można ustawić na jedną z następujących opcji: "left", "center", "right" (odpowiednio: lewo, środek, prawo)

Przykład: <iframe src="https://trinket.io/embed/python/e6f89ac86c?start=result" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>