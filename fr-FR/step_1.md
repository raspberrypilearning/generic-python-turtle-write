Tu peux utiliser une tortue pour écrire du texte.

```python
turtle.write('Bonjour !')
```

Définis la couleur de la tortue pour créer un texte coloré :

```python
turtle.color('deep pink')
turtle.write('Bonjour !')
```

Tu peux également modifier la police et l'alignement du texte.

```python
style = ('Courier', 30, 'italic')
turtle.write('Bonjour !', font=style, align='center')
```

La police est un tuple contenant :

+ Le nom de la police tel que « Arial », « Courier » ou « Times New Roman »
+ La taille de la police en pixels
+ Le type de police, qui peut être « normal », « gras » ou « italique »

Pour définir l'alignement qui contrôle le positionnement du texte en fonction de la position de la tortue, utilise le paramètre `align`. `align` peut être défini sur l'une de ces options : 'left', 'center', 'right'

Exemple : <iframe src="https://trinket.io/embed/python/52378ec006?start=result" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>