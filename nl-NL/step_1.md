Je kunt een turtle (schildpad) gebruiken om tekst te schrijven.

```python
turtle.write('Hallo!')
```

Stel de kleur van de schildpad in om gekleurde tekst te maken:

```python
turtle.color('deep pink')
turtle.write('Hallo!')
```

Je kunt ook het lettertype en de uitlijning van de tekst wijzigen.

```python
style = ('Courier', 30, 'italic')
turtle.write('Hallo!', font=style, align='center')
```

Het lettertype is een tuple met:

+ De naam van het lettertype, zoals 'Arial', 'Courier' of 'Times New Roman'
+ De lettergrootte in pixels
+ Het lettertype, dat 'normal' (normaal), 'bold' (vet) of 'italic'(cursief) kan zijn

Om de uitlijning in te stellen die bepaalt op basis van de positie van de schildpad waar de tekst wordt geplaatst, gebruik je de parameter `align`. `align` kan op een van deze opties worden ingesteld: 'left' (links), 'center' (gecentreerd), 'right' (rechts)

Voorbeeld: 

<iframe src="https://trinket.io/embed/python/c11e4e3137?start=result" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>
