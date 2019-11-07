Možeš koristiti turtle modul za pisanje teksta.

```python
turtle.write('Bok!')
```

Postavi boju kornjače da obojaš tekst:

```python
turtle.color('deep pink')
turtle.write('Bok!')
```

Također možeš promijeniti font i poravnavanje teksta.

```python
style = ('Courier', 30, 'italic')
turtle.write('Bok!', font=style, align='center')
```

Font je linija koja sadrži:

+ Naziv fonta, primjerice „Arial”, „Courier” ili „Times New Roman”
+ Veličinu fonta u pikselima
+ Tip fonta, koji može biti „normal” (normalan), „bold” (podebljan) ili „italic” (ukošen)

Upotrijebi parametar `align` (poravnanje) da postaviš poravnanje koje, na temelju položaja kornjače, određuje kako će tekst biti postavljen. Parametar `align` može se postaviti na jednu od ovih opcija: „left” (lijevo), „center” (centrirano), „right” (desno)

Na primjer: <iframe src="https://trinket.io/embed/python/52378ec006?start=result" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>