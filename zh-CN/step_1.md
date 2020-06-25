你可以使用turtle（海龟）来写文本

```python
turtle.write('你好!')
```

设置turtle的颜色，让你的文本内容五彩斑斓

```python
turtle.color('deep pink')#设置颜色为深粉红色
turtle.write('你好!')#输出文字‘你好!’
```

你还可以更改字体以及文本的对齐方式

```python
style = ('Courier', 30, 'italic')#设置字体格式为style=(‘Courier’字体,字号30, 'italic'斜体)
turtle.write('你好!', font=style, align='center')#以style的格式输出"你好!",位置居中
```

字体是一个元组，包括：

+ 字体格式的名称，比如‘Arial’，‘Courier’，或者‘Times New Roman’。
+ 字体的大小清晰度
+ 字体的格式类型，包括正常‘normal’，加粗'bold'，或者斜体'italic'。

用参数`align` ，去设置文本相对于turtle所在位置的对齐方式。 `align` 可以被设置成： 'left', 'center', 'right'，对应分别是‘左’，‘中’，‘右’的选择。

示例： 
<iframe src="https://trinket.io/embed/python/3298a24d0d?start=result" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>