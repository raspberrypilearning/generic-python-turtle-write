Du kannst eine Schildkröte verwenden, um Text zu schreiben.

```python
turtle.write ('Hallo!')
```

Lege die Farbe der Schildkröte fest, um farbigen Text zu erstellen:

```python
turtle.color ('deep pink')
turtle.write ('Hallo!')
```

Du kannst auch die Schriftart und Ausrichtung des Textes ändern.

```python
style = ('Courier', 30, 'italic')
turtle.write ('Hallo!', font = style, align = 'center')
```

Die Schriftart ist ein Tupel mit:

+ Dem Schriftnamen wie 'Arial', 'Courier' oder 'Times New Roman'
+ Der Schriftgröße in Pixel
+ Der Schriftart, die normal ('normal'), fett ('bold') oder kursiv ('italic') sein kann

Um die Ausrichtung festzulegen, die die Position des Textes in Bezug zur Position der Schildkröte steuert, verwendest du den Parameter `align`. `align` kann auf eine der folgenden Optionen eingestellt werden: "left" (links), "center" (Mitte), "right" (rechts)

Beispiel: <iframe src="https://trinket.io/embed/python/52378ec006?start=result" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>