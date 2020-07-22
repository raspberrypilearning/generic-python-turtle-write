ಪಠ್ಯವನ್ನು ಬರೆಯಲು ನೀವು turtle ಬಳಸಬಹುದು.

```python
turtle.write('Hello!')
```

ಬಣ್ಣದ ಪಠ್ಯವನ್ನು ರಚಿಸಲು turtle's ಬಣ್ಣವನ್ನು ಹೊಂದಿಸಿ:

```python
turtle.color('deep pink')
turtle.write('Hello!')
```

ನೀವು ಪಠ್ಯದ ಫಾಂಟ್ ಮತ್ತು ಜೋಡಣೆಯನ್ನು ಸಹ ಬದಲಾಯಿಸಬಹುದು.

```python
style = ('Courier', 30, 'italic')
turtle.write('Hello!', font=style, align='center')
```

ಫಾಂಟ್ ಒಳಗೊಂಡಿರುವ tuple ಆಗಿದೆ:

+ 'Arial', 'Courier', or 'Times New Roman' ನಂತಹ ಫಾಂಟ್ ಹೆಸರು
+ ಫಾಂಟ್ ಗಾತ್ರ ಪಿಕ್ಸೆಲ್‌ಗಳಲ್ಲಿ
+ ಫಾಂಟ್ ಪ್ರಕಾರ, 'normal', 'bold', or 'italic' ಅದುಆಗಿರಬಹುದು

Turtle ಸ್ಥಾನವನ್ನು ಆಧರಿಸಿ ಪಠ್ಯವನ್ನು ಹೇಗೆ ಇರಿಸಲಾಗಿದೆ ಎಂಬುದನ್ನು ನಿಯಂತ್ರಿಸುವ ಜೋಡಣೆಯನ್ನು ಹೊಂದಿಸಲು, `align` ನಿಯತಾಂಕವನ್ನು ಬಳಸಿ. `align` ಅನ್ನು ಈ ಆಯ್ಕೆಗಳಲ್ಲಿ ಒಂದಕ್ಕೆ ಹೊಂದಿಸಬಹುದು: 'left', 'center', 'right'

ಉದಾಹರಣೆ: 

<iframe src="https://trinket.io/embed/python/52378ec006?start=result" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>