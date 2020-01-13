Ти можеш використовувати turtle для виводу тексту.

```python
turtle.write('Привіт!')
```

Встановіть колір черепахи, щоб створити кольоровий текст:

```python
turtle.color('deep pink')
turtle.write('Привіт!')
```

Ти також можеш змінити шрифт і вирівнювання тексту.

```python
style = ('Courier', 30, 'italic')
turtle.write('Привіт!', font=style, align='center')
```

Шрифт являє собою кортеж, що містить:

+ Назва шрифту, наприклад "Arial", "Courier" або "Times New Roman"
+ Розмір шрифту в пікселях
+ Тип шрифту, який може бути "normal" (звичайний), "bold" (жирний) або "italic" (курсив)

To set the alignment which controls how the text is positioned based on the position of the turtle, use the `align` parameter. `align` може приймати наступні значення: "left" (ліво), "center" (центр), "right" (право)

Приклад: <iframe src="https://trinket.io/embed/python/52378ec006?start=result" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>