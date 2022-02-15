# NLP Amazon Reviews

Bu datasette Amazon'da bir ürün için yapılan yorumlar üzerinden metin madenciliği adımları gerçekleştirilerek metin sınıflandırma ve duygu analizi yapılacaktır.

##### Odaklanılacak değişkenler
* reviewText : yapılan yorum
* overall : ürüne verilen puan


##### Amaç : Bağımsız değişken olan yorumlardan(text) ölçülebilirlik özelliğine sahip olan, matematiksel işlemler yapabileceğimiz, makine öğrenmesi modelleri uygulayabileceğimiz değişkenler üretmektir(Yani elimizdeki metni, lineer cebir dünyasında işlenebilecek hale getirmeliyiz). Daha sonra yapılan yorumun pozitif mi negatif mi olduğunu tahmin eden bir metin sınıflandrıma modeli kurulacaktır.


Yaygın kullanılan kelime vektörü oluşturma yöntemlerinden olan

* Count Vectors
* TF-IDF Vectors

kullanılmıştır.
