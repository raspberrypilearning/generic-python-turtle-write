يمكنك استخدام السلحفاة لكتابة نص. 

```
turtle.write('Hello!')
```

عيِّن لون السلحفاة لتنشئ نصًا ملونًا:

```
turtle.color('deep pink')
turtle.write('Hello!')
```

يمكنك أيضًا تغيير خط النص ومحاذاته. 

```
style = ('Courier', 30, 'italic')
turtle.write('Hello!', font=style, align='center')
```

يكون الخط عبارة عن مجموعة بيانات مترابطة تحتوي على:
+ اسم الخط، مثل 'Arial' أو 'Courier' أو 'Times New Roman'
+ حجم الخط بوحدة البكسل
+ نوع الخط، ويمكن أن يكون 'normal' أو 'bold' أو 'italic'

لتعيين المحاذاة التي تحدد موضع النص وفقًا لموضع السلحفاة، استخدم المَعلمة `align`. ويمكن تعيين المَعلمة `align` إلى أحد الخيارات التالية: 'left', 'center', 'right'

مثال:
<iframe src="https://trinket.io/embed/python/52378ec006?start=result" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
