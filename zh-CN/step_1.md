你可以使用海龟来编写文本。 

```python
turtle.write('Hello!')
```

设置海龟颜色来创建彩色文本：

```python
turtle.color('deep pink')
turtle.write('Hello!')
```

你还可以更改文本的字体和对齐方式。 

```python
style = ('Courier', 30, 'italic')
turtle.write('Hello!', font=style, align='center')
```

字体是一个包含以下元素的元组：
+ 字体名称，如“Arial”、“Courier”或“Times New Roman”
+ 以像素为单位的字体大小
+ 字体类型，可以是“normal”（普通）、“bold”（粗体）或“italic”（斜体）

要设置控制如何以海龟位置为基准来定位文本的对齐方式，请使用 `align` 参数。`align` 可设置为以下选项之一：“left”（左）、“center”（中）、“right”（右）

示例：
<iframe src="https://trinket.io/embed/python/52378ec006?start=result" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
