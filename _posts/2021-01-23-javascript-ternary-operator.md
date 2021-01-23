---
published: false
---
Herkese selamlar, bugün JavaScript'in güzelliklerinden olan ternary operator'u inceleyeceğiz fakat ternary operator'u incelemeden önce farklı bir kaç örnek üzerinden ilerlemek istiyorum.

---
İsterseniz öncelikle değişken tanımlayarak başlayalım.

     let isOnline =  false

isOnline isimli değişkenimizi tanımladık ve değer olarak false değerini verdik.

    if  (isOnline){
	    console.log('User Online');
    }  else  {
	    console.log('User Offline');
    }

Daha sonra ise onu if-else ile kontrol ettik, burada yaptığımız şey eğer `isOnline` değişkeni true değerini almışsa konsola `'User Online'` yazısını yazdırıyoruz. Eğer istemiş olduğumuz koşulları sağlamazsa else bloğunun içerisindeki yazmış olduğumuz kodlar çalışacak.

Burada `isOnline` değişkenimizin değeri `false` olduğu için else bloğundaki kodlar çalışacak ve konsola `User Offline` şeklinde bir çıktı verecektir.

---
En basit örnekle bile if-else bloğu 5-6 satırlık bir alan kaplıyor fakat burada ternary operator devreye giriyor. Ternary operator kısaca tek satır içerisinde koşul yazmamıza olanak sağlıyor. İsterseniz ternary operator'ün nasıl çalıştığını yukarıdaki örnek üzerinden vermeye çalışayım.

    let isOnline =  false
Tekrardan isOnline değişkenimizi tanımlıyoruz ve bu sefer if-else kullanmak yerine direkt olarak ternary operator'ü kullanıyoruz.

    console.log(isOnline  ?  'User Online'  :  'User Offline');
Evet! İşte her şey bu kadar basit, tek bir satır içerisinde koşumuzu yazdık ve yine sonuç olarak `'User Offline'` yazısını aldık.

---
Ternary operator çoğu zaman bize büyük bir pratiklik kazandırıyor. Tek satır üzerinde sorgu yazmamızı sağlıyor ve bu bazen çok kullanışlı olabiliyor. Son olarak isterseniz ternary operator üzerindeki ? ve : ne anlama geliyor açıklayalım. 

Ternary operator'ü bir çok yerde kullanabilirsiniz. Örnekte göstermiş olduğum gibi konsola bir çıktı alırken veya bir değer return ederken. İstediğiniz yerde kullanabilirsiniz. Kullanım şekli ise şu şekilde;
 ```
 koşul ? doğruysaYapılacaklar : yanlışsaYapılacaklar
```

İlk başa koşulumuzu yazdıktan sonra ? işareti ekliyoruz ve eğer koşumuz true değerini alırsa çalışacak kod bloğumuzu ekliyoruz, daha sonra ise : işaretini ekliyor ve bu sefer eğer koşulumuz else bloğuna düşerse yani koşulumuz sağlanmazsa olacak kod bloğumuzu çalıştırıyoruz.

---
İşte ternary operator'ü kullanmak bu kadar basit ve pratik. Bir sonraki yazıda görüşmek üzere 🙂
