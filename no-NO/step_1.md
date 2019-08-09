Du kan bruke en skilpadde til å skrive tekst.

```python
turtle.write('Hei!')
```

Sett skillpaddens farge for å lage farget tekst:

```python
turtle.color('deep pink')
turtle.write('Hei!')
```

Du kan også endre skrift og justering av teksten.

```python
style = ('Courier', 30, 'italic')
turtle.write ('Hei!', font=style, align='center')
```

Skriften er en tuppel som inneholder:

+ Skriftnavnet som 'Arial', 'Courier' eller 'Times New Roman'
+ Skriftstørrelsen i piksler
+ Skrifttypen, som kan være 'normal', 'bold' (fet) eller 'italics' (kursiv)

For å angi justeringen som styrer hvordan teksten er plassert basert på turtleposisjonen, bruk `align` parameteren. `align` kan settes til en av disse alternativene: 'left' (venstre), 'center' (sentrert), 'right' (høyre)

Eksempel: <iframe src="https://trinket.io/embed/python/52378ec006?start=result" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>