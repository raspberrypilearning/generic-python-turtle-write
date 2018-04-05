आप लिखने के लिए टर्टल का उपयोग कर सकते हैं। 

```python
turtle.write('Hello!')
```

रंगीन टेक्स्ट बनाने के लिए टर्टल का रंग निर्धारित करें:

```python
turtle.color('deep pink')
turtle.write('Hello!')
```

आप फॉन्ट और टेक्स्ट के संरेखण में भी परिवर्तन कर सकते हैं। 

```python
style = ('Courier', 30, 'italic')
turtle.write('Hello!', font=style, align='center')
```

फॉन्ट tuple जिसमें यह शामिल है:
+ फॉन्ट के नाम जैसे 'Arial', 'Courier', या 'Times New Roman'
+ पिक्सल्स में फॉन्ट का आकार
+ फॉन्ट की किस्म, जो 'normal', 'bold', या 'italic' हो सकती है

वह संरेखण निर्धारित करने के लिए, जो टर्टल की स्थिति के आधार पर टेक्स्ट की स्थिति को नियंत्रित करता है, `align` पैरामीटर का उपयोग करें। `align` का उपयोग इनमें से के लिए किया जा सकता है: ‘बायाँ’, ‘केंद्र’, ‘दायाँ'

उदाहरण:
<iframe src="https://trinket.io/embed/python/52378ec006?start=result" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
