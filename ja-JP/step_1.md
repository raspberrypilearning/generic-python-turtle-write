turtle(タートル)を使ってテキストを書くことができます。

```python
turtle.write('こんにちは！')
```

タートル(かめ)の色を設定して、色付きのテキストを作成します。

```python
turtle.color('deep pink')
turtle.write('こんにちは！')
```

テキストのフォントと配置を変更することもできます。

```python
style = ('Courier', 30, 'italic')
turtle.write('こんにちは！', font=style, align='center')
```

フォントは以下を含むタプルです。

+ 'Arial'、 'C​​ourier'、 'Times New Roman'などのフォント名
+ ピクセル単位のフォントサイズ
+ 'normal'(通常)、 'bold'(太字)、または 'italic'(斜体)のフォントタイプ

タートルの位置を基に、テキストをどう配置するかを決めるには、 `align` パラメータを使います。 `align` は、 'left'(左)、 'center'(中央)、 'right'(右)のいずれかを設定できます。

例： 
<iframe src="https://trinket.io/embed/python/7bb1d4fd1d?start=result" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>