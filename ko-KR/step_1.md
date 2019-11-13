거북이를 사용하여 텍스트를 쓸 수 있습니다.

```python
turtle.write ('안녕!')
```

거북이의 색을 설정하여 색칠 된 텍스트를 쓸 수 있습니다.

```python
turtle.color('deep pink')
turtle.write('안녕!')
```

텍스트의 글꼴과 맞춤을 변경할 수도 있습니다.

```python
style = ('Courier', 30, 'italic')
turtle.write('안녕!', font=style, align='center')
```

글꼴은 다음을 포함하는 튜플입니다.

+ 'Arial', 'Courier'또는 'Times New Roman'과 같은 글꼴 이름
+ 글꼴 크기 (픽셀 단위)
+ 글꼴 유형: '보통', '굵게'또는 '기울임 꼴' 등

거북의 위치에 따라 텍스트의 위치를 ​​제어하는 ​​정렬을 설정하려면 `align` 매개 변수를 사용합니다. `align` 은 'left', 'center', 'right'중 하나의 옵션으로 설정할 수 있습니다.

예시: <iframe src="https://trinket.io/embed/python/7f968d2b90?start=result" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>