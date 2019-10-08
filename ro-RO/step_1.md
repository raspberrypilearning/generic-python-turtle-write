Poți folosi o broască țestoasă pentru a scrie text.

```python
turtle.write('Salut!')
```

Setează culoarea țestoasei pentru a crea text colorat:

```python
turtle.color("deep pink")
turtle.write("Salut!")
```

De asemenea, poți schimba fontul și alinierea textului.

```python
stil = ('Courier', 30, 'italic')
turtle.write ('Salut!', font=stil, align='center')
```

Fontul este un tuplu care conține:

+ Numele fontului, cum ar fi „Arial”, „Courier” sau „Times New Roman”
+ Dimensiunea fontului în pixeli
+ Tipul de font, care poate fi „normal”, „bold” sau „italic”

Pentru a seta alinierea care controlează modul în care textul este poziționat pe baza poziției țestoasei, folosește parametrul `align`. `align` poate fi setat ca una din următoarele opțiuni: „left”, „center”, „right”

Exemplu: 
<iframe src="https://trinket.io/embed/python/e4249cdc15?start=result" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
