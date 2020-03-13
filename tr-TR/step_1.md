Metin yazmak için bir turtle modülünü kullanabilirsiniz.

```python
turtle.write('Merhaba!')
```

Renkli metin oluşturmak için turtle modülünün rengini ayarlayın:

```python
turtle.color('deep pink')
turtle.write('Merhaba!')
```

Metnin yazı tipini ve hizalamasını da değiştirebilirsiniz.

```python
style = ('Courier', 30, 'italic')
turtle.write('Merhaba!', font=style, align='center')
```

Bu yazı tipi aşağıdakileri içeren bir demet(Demetler birden fazla veri türünü bir arada bulundurabilen virgüllerle veya parantez ile gösterilen immutable(değiştirilemeyen) veri tipleridir):

+ 'Arial', 'Courier' veya 'Times New Roman' gibi bir yazı tipi adı
+ Piksel cinsinden yazı tipi boyutu
+ 'Normal', 'kalın' veya 'italik' olabilen yazım türü

Turtle modülünün konumuna göre metnin nasıl konumlandırıldığını kontrol eden hizalamayı ayarlamak için `align` değişkenini kullanın. `align` değişkeni şu seçeneklerden birine ayarlanabilir: 'left' (sol), 'center' (merkez), 'right' (sağ)

Örneğin: 

<iframe src="https://trinket.io/embed/python/a3d0b54351?start=result" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>
