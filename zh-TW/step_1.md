你可以用烏龜來寫文字。

```python
turtle.write('你好!')
```

設定烏龜的顏色來創造彩色文字：

```python
turtle.color('deep pink')
turtle.write('你好!')
```

您還可以更改文字的字體和對齊方式。

```python
style = ('Courier', 30, 'italic')
turtle.write('你好!', font=style, align='center')
```

字體是包含以下內容的元組：

+ 字體名稱，例如'Arial'，'Courier'或'Times New Roman'
+ 字體大小，以像素為單位
+ 字體類型，可以是“正常”，“粗體”或“斜體”

根據烏龜的位置設置對齊方式來控制文字的位置，請使用 `align` 參數。 `align` 可以設置為以下選項之一：'left'，'center', 'right'

範例： <iframe src="https://trinket.io/embed/python/52378ec006?start=result" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>