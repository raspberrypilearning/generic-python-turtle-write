आप पाठ लिखने के लिए तुर्त्ल का उपयोग कर सकते हैं।

```python
turtle.write('हैलो!')
```

रंगीन पाठ बनाने के लिए कछुए का रंग निर्धारित करें:

```python
turtle.color('deep pink')
turtle.write('हैलो!')
```

आप पाठ का फ़ॉन्ट और संरेखण भी बदल सकते हैं।

```python
style = ('Courier', 30, 'italic')
turtle.write('हैलो!', font=style, align='center')
```

फ़ॉन्ट एक टपल युक्त है:

+ फ़ॉन्ट का नाम जैसे 'एरियल', 'कूरियर', या 'टाइम्स न्यू रोमन'
+ पिक्सेल में फ़ॉन्ट आकार
+ फ़ॉन्ट प्रकार, जो 'सामान्य', 'बोल्ड' या 'इटैलिक' हो सकता है

संरेखण सेट करने के लिए जो नियंत्रित करता है कि तुर्त्ल की स्थिति के आधार पर पाठ कैसे स्थित है, `align` पैरामीटर का उपयोग करें।। `align` संरेखित इनमें से किसी एक विकल्प पर सेट किया जा सकता है: 'लेफ्ट', 'सेंटर', 'राइट'

उदाहरण: 
<iframe src="https://trinket.io/embed/python/8f30b4454a?start=result" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>
