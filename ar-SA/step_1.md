يمكنك استخدام turtle لكتابة النص.

```python
turtle.write('مرحباً!')
```

اضبط لون turtle لإنشاء نص ملون:

```python
turtle.color('deep pink')
turtle.write('مرحباً!')
```

يمكنك أيضًا تغيير نوع الخط ومحاذاة النص.

```python
style = ('Courier', 30, 'italic')
turtle.write('مرحباً!', font=style, align='center')
```

نوع الخط هو مجموعة تحتوي على:

+ اسم الخط مثل "Arial" أو "Courier" أو "Times New Roman"
+ حجم الخط بالبكسل
+ نمط الخط ، الذي يمكن أن يكون "طبيعيًا" أو "غامقًا" أو "مائل"

لضبط المحاذاة التي تُحدد موضع النص وفقًا لموضع السلحفاة، استخدم المتغير `align`. المتغير `align` يمكن أن يأخذ أحد القيم التالية: "left"، و"center"، و"right"

مثال: <iframe src="https://trinket.io/embed/python/52378ec006?start=result" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>