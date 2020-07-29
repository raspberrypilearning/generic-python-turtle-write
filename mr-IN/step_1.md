मजकूर लिहिण्यासाठी तुम्ही turtle चा वापरू शकता.

```python
turtle.write('Hello!')
```

रंगीत मजकूर तयार करण्यासाठी turtle चा रंग सेट करा:

```python
turtle.color('deep pink')
turtle.write('Hello!')
```

तुम्ही मजकूराचा font आणि alignment देखील बदलू शकता.

```python
style = ('Courier', 30, 'italic')
turtle.write('Hello!', font=style, align='center')
```

Font हे एक tuple आहे ज्यामध्ये:

+ 'Arial', 'Courier', or 'Times New Roman' सारख्या fonts चे नाव
+ Font चा आकार pixels मध्ये
+ Font प्रकार, जो 'normal', 'bold', or 'italic' असू शकतो

Turtle च्या स्थानाच्या आधारे मजकूर कसे स्थित आहे हे नियंत्रित करणारे alignment सेट करण्यासाठी,`align` मापदंड वापरा. या पर्यायांपैकी एक `align` सेट केले जाऊ शकते: 'left', 'center', 'right'

उदाहरणः 

<iframe src="https://trinket.io/embed/python/52378ec006?start=result" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>