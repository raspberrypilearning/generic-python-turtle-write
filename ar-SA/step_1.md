You can use a turtle to write text.

```python
turtle.write('Hello!')
```

Set the turtle's color to create coloured text:

```python
turtle.color('deep pink')
turtle.write('Hello!')
```

You can also change the font and alignment of the text.

```python
style = ('Courier', 30, 'italic')
turtle.write('Hello!', font=style, align='center')
```

The font is a tuple containing:

+ The font name such as 'Arial', 'Courier', or 'Times New Roman'
+ The font size in pixels
+ The font type, which can be 'normal', 'bold', or 'italic'

To set the alignment which controls how the text is positioned based on the position of the turtle, use the `align` parameter. `align` can be set to one of these options: 'left', 'center', 'right'

Example: <iframe src="https://trinket.io/embed/python/52378ec006?start=result" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>